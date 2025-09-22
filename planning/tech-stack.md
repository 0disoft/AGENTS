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

## [AI] 프론트엔드

- **프레임워크**
  - Astro
  - SvelteKit
  - QwikCity
- **스타일링**
  - 바닐라 CSS
  - UnoCSS
  - Tailwind CSS

## [AI] 백엔드

- **프레임워크**
  - Elysia
  - Hono

## [AI] 런타임 환경 및 언어

- Bun
- Deno
- Node.js (pnpm)

## [AI] 데이터베이스

- **관계형 (Relational)**
  - PostgreSQL
  - SQLite
- **BaaS / 서버리스**
  - Supabase (PostgreSQL)
  - Neon (PostgreSQL)
  - Vercel Postgres (PostgreSQL)
  - Turso (libSQL/SQLite)
  - Cloudflare D1 (SQLite)
  - CockroachDB
- **ORM**
  - Prisma
  - Drizzle

## [AI] 크로스 플랫폼

- Tauri (Rust)
- Flutter (Dart)

## [AI] 게임 개발

- Phaser (TypeScript)
- Flame (Flutter)

## [AI] 데브옵스 및 배포

- **컨테이너**
  - Docker
- **배포 플랫폼**
  - Cloudflare Workers
  - Vercel
  - Netlify
  - Fly.io
  - Render
  - Railway
- **CI/CD**
  - GitHub Actions

## [AI] 서비스

- **결제**
  - 포트원
  - Paddle
  - Lemon Squeezy
  - Creem
  - 부트페이
  - Gumroad
- **후원**
  - GitHub Sponsors
  - Buy Me a Coffee
  - Ko-fi
  - Patreon

## [AI] 기타 주요 툴

- **정적 코드 분석 / 포매팅**
  - ESLint
  - Prettier
  - Biome.js
- **빌드 툴 / 번들러**
  - Vite
  - esbuild
- **단위/통합 테스팅**
  - Vitest
  - Jest
- **엔드투엔드 테스팅**
  - Playwright
- **상태 관리 (프론트엔드)**
  - Zustand
  - Jotai
  - XState
- **유효성 검사**
  - Zod
  - ArkType
- **모노레포 관리**
  - Turborepo
  - Nx
- **API 클라이언트**
  - Bruno
- **분석**
  - PostHog
  - Plausible
  - Umami
