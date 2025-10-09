# 자바스크립트 암호화 전략 요약 (JavaScript Encryption Strategy)

## 실패 지점 우선 차단 (Failure-Point-First Prevention)

Node.js, Deno, Bun 등 멀티 런타임 환경에서는 내장 기능을 우선 활용해 의존성
리스크를 줄여야 한다.

- 패스워드 해싱 시 Argon2id(Argon2id)를 사용하고 RFC 9106 권고에 따라 최소
  64MiB 이상의 메모리를 설정해 TMTO(Time-Memory Trade-Off) 공격에 대비한다.
- 데이터 암호화는 Nonce(Nonce) 재사용 방지를 위해
  XChaCha20-Poly1305(XChaCha20-Poly1305)의 192비트 Nonce 공간을 활용한다.
- 키 파생은 HKDF(HKDF)를 이용해 info 파라미터로 도메인 분리를 명확히
  적용한다.

## 권장 기술 스택 (Recommended Stack)

- **패스워드 해싱 (Password Hashing)**
  - 기본: `@node-rs/argon2`
  - 대안: Node v24+는 `node:crypto`, Bun은 `Bun.password`, Deno(서버리스)는
    `npm:libsodium-wrappers`
- **데이터 암호화 (Data Encryption)**
  - 기본: `@noble/ciphers`의 XChaCha20-Poly1305
  - 대안: 최고 성능이 필요하면 `npm:libsodium-wrappers`
- **키 분기 (Key Derivation)**
  - 기본: `@noble/hashes`의 HKDF
  - 대안: `node:crypto` 또는 Web Crypto API

## 실행 지침 (Actionable Guidance)

- 다중 환경 호환을 유지하려면 `@node-rs/argon2`, `@noble/ciphers`,
  `@noble/hashes` 조합으로 통일한다.
- Nonce 관리 실수를 예방하기 위해 구조적으로 XChaCha20-Poly1305를 선택하고
  재사용 점검 로직을 포함한다.
- HKDF info 파라미터에 용도 태그를 명시해 키 도메인 분리를 강제한다.
- 알고리즘 선택보다 운영 정책과 설정값을 문서화하고 자동화해 반복 실수를
  방지한다.
