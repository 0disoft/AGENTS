# AGENTS 플레이북 시스템 (AGENTS Playbook System)

이 폴더는 LLM 에이전트와 협력하여 코딩 중심의 작업을 단계별로 진행하기 위한 간결한 워크플로우 허브입니다.

## 핵심 원칙 (Core Principles)

에이전트는 다음 원칙에 따라 작업 흐름을 정리합니다.

### 1. 명확성 (Clarity)

- 요구사항이 모호하면 진행 전에 반드시 질문해 의도를 확인합니다.

### 2. 계획성 (Planning)

- 작업을 실행하기 전에 필요한 단계와 예상 결과를 간단히 계획하고 사용자와 공유합니다.

### 3. 점진적 실행 (Iteration)

- 작업을 작은 단위로 나누어 순차적으로 검증하면서 진행합니다.

## 시작하는 방법 (How to Start)

1. 기본적으로 터미널에서 전달된 최신 요청을 확인합니다.
2. 사용자가 명시적으로 지시한 경우에만 [`AGENTS/request.md`](./request.md)를 열어 추가 정보를 확인합니다.
3. 필요한 경우 요청 내용을 보완하거나 명확히 합니다.
4. 작업을 수행하면서 중간 결과와 결정을 [`AGENTS/response.md`](./response.md)에 정리합니다.

## LLM과의 상호작용 (Interaction with LLM)

- **질문/요청**: 평소에는 터미널을 통해 직접 요청이 전달됩니다. 사용자가 명시적으로 지시하면 [`AGENTS/request.md`](./request.md)를 확인합니다.
- **조언/답변**: LLM이 제공한 답변, 피드백, 다음 단계 제안은 [`AGENTS/response.md`](./response.md)에 기록합니다.

## 폴더 구조 (Folder Structure)

- **[`AGENTS/AGENTS.md`](./AGENTS.md)**: 이 폴더의 사용 지침입니다.
- **[`AGENTS/request.md`](./request.md)**: 사용자나 에이전트가 LLM에게 전달할 질문 또는 요청을 정리합니다.
- **[`AGENTS/response.md`](./response.md)**: LLM이 제공한 조언이나 답변을 보관합니다.
- **[`AGENTS/requests/`](./requests/)**: 날짜별·주제별 사용자 요청 문서를 아카이브합니다.
- **[`AGENTS/responses/`](./responses/)**: 각 요청에 대한 LLM 답변과 회고를 저장합니다.
- **[`AGENTS/plans/`](./plans/)**: 프로젝트별 계획, 체크리스트, 마일스톤을 정리합니다.
- **[`AGENTS/research/`](./research/)**: 기술 조사, 참고 링크, 벤치마킹 자료를 저장합니다.
- **[`AGENTS/snippets/`](./snippets/)**: 재사용할 코드 블록이나 명령어 조각을 보관합니다.
- **[`AGENTS/templates/`](./templates/)**: 비교표, 보고서 형태 등 재사용 가능한 문서 템플릿을 모읍니다.
- **[`AGENTS/logs/`](./logs/)**: 일자별 작업 로그와 결정 기록을 정리합니다.
- **[`AGENTS/assets/`](./assets/)**: 로고, 색상 팔레트, 이미지 등 공용 자료를 관리합니다.
