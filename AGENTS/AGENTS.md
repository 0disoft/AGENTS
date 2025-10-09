# AGENTS 플레이북 시스템 (AGENTS Playbook System)

이 폴더는 LLM 에이전트와 협력하여 아이디어를 구체적인 창작물로 만들어나가기 위한 모듈형 플레이북 시스템입니다.

## 핵심 원칙 (Core Principles)

에이전트는 아래의 핵심 원칙에 따라 모든 작업을 수행하여, 작업의 일관성, 안정성, 그리고 지속성을 보장해야 합니다.

### 1. 상태 중심 워크플로우: [`AGENTS/project_status.md`](./project_status.md)

모든 작업은 [`AGENTS/project_status.md`](./project_status.md) 파일을 중심으로 이루어집니다. 이 파일은 프로젝트의 전체 순서도이자, 현재 상태를 기록하는 유일한 진실의 원천(Single Source of Truth)입니다.

- **시작**: 에이전트는 항상 [`AGENTS/project_status.md`](./project_status.md) 파일을 읽는 것으로 작업을 시작합니다.
- **작업 수행**: 파일에 정의된 '전체 워크플로우'를 확인하고, '미시작' 또는 '진행 중' 상태인 첫 번째 단계를 찾아 작업을 수행합니다.
- **상태 업데이트**: 각 단계(Phase)가 완료되면, 에이전트는 즉시 [`AGENTS/project_status.md`](./project_status.md) 파일의 해당 항목 상태를 '완료'로 변경하고, 다음 단계의 상태를 '진행 중'으로 업데이트합니다.

### 2. 명확성 (Clarity)

사용자의 요구사항이 모호할 경우, 추측하여 진행하지 않고 반드시 명확한 질문을 통해 의도를 파악합니다.

### 3. 계획성 (Planning)

[`AGENTS/project_status.md`](./project_status.md)에 정의된 계획을 따르되, 각 단계의 세부 실행 계획은 필요시 사용자에게 간략히 공유하고 동의를 얻은 후 실행합니다.

### 4. 점진적 실행 (Iteration)

작업을 가능한 작은 단위로 나누어, 한 번에 하나씩 실행하고 검증하며 점진적으로 결과물을 완성해 나갑니다.

## 시작하는 방법 (How to Start)

1. **에이전트가 [`AGENTS/project_status.md`](./project_status.md) 파일을 엽니다.** 이 파일이 모든 작업의 시작점입니다.
2. 에이전트는 '전체 워크플로우'에서 완료되지 않은 첫 번째 단계를 확인합니다.
3. **(최초 실행 시)** "Phase 0: 프로젝트 종류 선택" 단계의 액션에 따라, 에이전트가 [`select_project_type.md`](./select_project_type.md) 파일의 내용을 안내하여 프로젝트 종류를 선택합니다.
4. 선택이 완료되면, 에이전트는 [`AGENTS/project_status.md`](./project_status.md)의 "Phase 0"을 '완료'로 업데이트하고 "Phase 1"을 시작합니다.

## 폴더 구조 (Folder Structure)

- **[`AGENTS/project_status.md`](./project_status.md)**: **(가장 중요)** 프로젝트의 전체 순서도이자 현재 상태를 나타내는 대시보드 파일입니다.
- **[`AGENTS/select_project_type.md`](./select_project_type.md)**: 프로젝트의 종류를 선택하기 위한 안내서입니다.
- **[`playbooks/`](./playbooks/)**: 각 창작물 유형별 세부 실행 계획들이 저장되어 있습니다. `project_status.md`의 각 단계(Phase)는 이 플레이북들을 참조할 수 있습니다.
- **[`modules/`](./modules/)**: 재사용 가능한 개별 작업 단위들이 저장되어 있습니다.
