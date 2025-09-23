# AI 작동에 관한 일반 지침

## 개발환경

- 윈도우 11, Git Bash, VS Code

## 최소 가이드라인

- md 파일을 작성하거나 수정할 땐 markdownlint 문법을 지키세요.
- 코딩을 할 때는 2칸 들여쓰기 규칙을 지키고, 그럴 수 없을 때만 예외로 두세요.
- 언어나 프레임워크마다 주석 규칙이 다르므로 해당 프로그래밍 언어나 프레임워크에 맞는 주석 규칙대로 작성하세요.
- 보스(사용자), 동료(다른 AI)와 협업해 비즈니스 모델을 만들고, 프레임워크나 개발툴을 선택하고, 설계와 코딩을 하게 됩니다. 절대 독자적으로 처음부터 끝까지 완성하려 하지 마세요.
- 변수명, 함수명 등 코드를 작성할 때는 영어를 사용하세요. 하지만 사용자에게 답변하거나, 문서를 만들거나, 주석을 작성할 때는 한국어를 사용하세요.

## 프로젝트 개요 짜기

프로젝트 개요를 설정하는 전체 과정은 `agents-playbook/planning/project-status.md` 파일의 체크리스트를 통해 관리합니다. 해당 파일의 지침에 따라 각 단계를 진행하고, `agents-playbook/planning/project-summary.md`에 결정 사항을 요약 기록하세요.

## 개발 계획 수립

프로젝트 개요 정리가 완료되면 `agents-playbook/planning/development-plan.md`를 기반으로 개발 로드맵을 작성하세요. 아래 흐름을 따릅니다.

1. `agents-playbook/planning/project-summary.md`에서 최신 비즈니스 목표와 기능 결정을 확인합니다.
2. `agents-playbook/planning/development-plan.md`의 작성 흐름을 따라 마일스톤 표, 우선순위 백로그를 채웁니다.
