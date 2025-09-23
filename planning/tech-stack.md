# 기술 스택 가이드

> [!NOTE]
> 이 문서는 프로젝트에 사용할 기술 스택 옵션을 제공하는 가이드입니다. 이 목록을 바탕으로 프로젝트의 성격과 목표에 맞는 기술들을 논의하고 결정하세요. 최종 결정된 내용은 `project-summary.md`의 '테크 스택' 섹션에 요약합니다.

모든 섹션은 AI가 프로젝트의 요구사항에 맞춰 최적의 조합을 제안하거나 결정할 수 있는 영역입니다.

## [AI] 개발 유형

- 웹 애플리케이션 / 사이트
- 모바일 애플리케이션
- 데스크톱 애플리케이션
- 게임
- 기타
- 사용안함

## [AI] 프론트엔드

- **프레임워크**
  - Astro
  - SvelteKit
  - QwikCity
  - 기타
  - 사용안함
- **스타일링**
  - 바닐라 CSS
  - UnoCSS
  - Tailwind CSS
  - shadcn/svelte
  - 기타
  - 사용안함

## [AI] 백엔드

- **프레임워크**
  - Elysia
  - Hono
  - 기타
  - 사용안함

## [AI] 런타임 환경 및 언어

- Bun
- Deno
- Node.js (pnpm)
- 기타
- 사용안함

## [AI] 데이터베이스

- **관계형 (Relational)**
  - PostgreSQL
  - SQLite
  - 기타
  - 사용안함
- **BaaS / 서버리스**
  - Supabase (PostgreSQL)
  - Neon (PostgreSQL)
  - Vercel Postgres (PostgreSQL)
  - Turso (libSQL/SQLite)
  - Cloudflare D1 (SQLite)
  - CockroachDB
  - 기타
  - 사용안함
- **ORM**
  - Prisma
  - Drizzle
  - 기타
  - 사용안함

## [AI] 크로스 플랫폼

- Tauri (Rust)
- Flutter (Dart)
- 기타
- 사용안함

## [AI] 게임 개발

- Phaser (TypeScript)
- Flame (Flutter)
- 기타
- 사용안함

## [AI] 데브옵스 및 배포

- **컨테이너**
  - Docker
  - 기타
  - 사용안함
- **배포 플랫폼**
  - Cloudflare Workers
  - Vercel
  - Netlify
  - Fly.io
  - Render
  - Railway
  - 기타
  - 사용안함
- **CI/CD**
  - GitHub Actions
  - 기타
  - 사용안함

## [AI] 서비스

- **인증**
  - Better-Auth - 오픈소스 기반의 경량 인증 및 사용자 관리 솔루션.
  - 기타
  - 사용안함
- **결제**
  - 포트원 - 국내외 주요 PG사 결제 시스템을 하나의 API로 통합 제공하는 서비스.
  - Paddle - SaaS 및 디지털 상품 판매자를 위한 종합 결제 대행(MOR) 서비스.
  - Lemon Squeezy - 디지털 상품 및 SaaS 판매자를 위한 올인원 이커머스 플랫폼 (MOR).
  - Creem - 인디 해커 및 SaaS 창업자를 위한 글로벌 결제 처리 및 세금 규정 준수 자동화 서비스 (MOR).
  - 부트페이 - 다양한 PG사를 통합하여 저렴한 수수료로 제공하는 개발자용 결제 연동 API.
  - Gumroad - 크리에이터가 디지털 상품을 판매할 수 있게 하는 이커머스 플랫폼.
  - 기타
  - 사용안함
- **후원**
  - GitHub Sponsors - 개발자에게 가장 접근성 높은 수수료 0% 후원 도구.
  - Buy Me a Coffee - '커피 한 잔' 컨셉으로 가벼운 일회성 후원을 유도하는 서비스.
  - Ko-fi - 수수료 0% 옵션과 강력한 상점 기능을 갖춘 다기능 후원 플랫폼.
  - Patreon - 월간 구독 기반의 안정적인 수익 모델과 팬 커뮤니티 구축에 특화.
  - Toonation - 라이브 스트리머를 위한 TTS, 룰렛 등 방송 연동 기능에 독보적.
  - Open Collective - 오픈소스 프로젝트의 자금 흐름을 투명하게 관리하는 데 최적화.
  - Liberapay - 익명 정기 기부에 특화되었으며 플랫폼 수수료가 없는 서비스.
  - Donorbox - 비영리 단체를 위한 전문적인 모금 기능과 CRM을 제공하는 솔루션.
  - 기타
  - 사용안함

## [AI] 기타 주요 툴

- **정적 코드 분석 / 포매팅**
  - ESLint
  - Prettier
  - Biome.js
  - 기타
  - 사용안함
- **빌드 툴 / 번들러**
  - Vite
  - esbuild
  - 기타
  - 사용안함
- **단위/통합 테스팅**
  - Vitest
  - Jest
  - 기타
  - 사용안함
- **엔드투엔드 테스팅**
  - Playwright
  - 기타
  - 사용안함
- **상태 관리 (프론트엔드)**
  - Zustand
  - Jotai
  - XState
  - 기타
  - 사용안함
- **유효성 검사**
  - Zod
  - ArkType
  - 기타
  - 사용안함
- **모노레포 관리**
  - Turborepo
  - Nx
  - 기타
  - 사용안함
- **API 클라이언트**
  - Bruno
  - 기타
  - 사용안함
- **분석**
  - PostHog
  - Plausible
  - Umami
  - 기타
  - 사용안함
