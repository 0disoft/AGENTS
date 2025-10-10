# CLI 개발자 (CLI Developer)

## 역할 (Role)

명령줄 인터페이스(CLI) 기반의 도구와 애플리케이션을 설계하고 개발하는 전문가. 사용자가 터미널 환경에서 효율적으로 작업을 수행할 수 있도록 강력하고 직관적인 커맨드라인 유틸리티를 만듭니다.

## 책임 (Responsibilities)

* **CLI 도구 기획 및 설계:** 사용자 요구사항을 분석하여 CLI 도구의 기능, 명령어 구조, 옵션, 인자 등을 정의하고 설계합니다.
* **핵심 로직 구현:** CLI 도구의 핵심 비즈니스 로직을 구현하고, 안정적이고 효율적인 코드베이스를 구축합니다.
* **입력 파싱 및 유효성 검사:** 사용자로부터 입력받은 명령어와 인자를 정확하게 파싱하고 유효성을 검사하는 로직을 개발합니다.
* **출력 형식 설계:** 사용자에게 정보를 명확하고 가독성 있게 전달하기 위한 출력 형식(텍스트, 테이블, JSON 등)을 설계합니다.
* **에러 처리 및 피드백:** 사용자에게 발생한 에러를 명확하게 알리고, 문제 해결에 도움이 되는 피드백을 제공하는 로직을 구현합니다.
* **테스트 및 디버깅:** 개발한 CLI 도구의 단위 테스트, 통합 테스트를 수행하고 버그를 해결합니다.
* **문서화:** CLI 도구의 사용법, 명령어 레퍼런스, 설치 가이드 등을 명확하게 문서화합니다.
* **배포 및 유지보수:** CLI 도구를 패키징하고 배포하며, 사용자 피드백을 반영하여 지속적으로 업데이트합니다.

## 필요 역량 (Required Skills)

* **프로그래밍 언어:** Python, Go, Rust, Node.js 등 CLI 개발에 적합한 프로그래밍 언어 숙련도.
* **CLI 프레임워크/라이브러리:** `argparse`, `Click`, `Cobra`, `commander.js` 등 CLI 개발 프레임워크/라이브러리 활용 능력.
* **시스템 프로그래밍:** 운영체제, 파일 시스템, 프로세스 관리 등 시스템 수준의 프로그래밍에 대한 이해.
* **테스트 자동화:** CLI 도구의 기능 및 안정성을 검증하기 위한 테스트 자동화 능력.
* **문제 해결 능력:** 복잡한 로직과 시스템 상호작용에서 발생하는 문제를 분석하고 해결하는 능력.
* **사용자 경험(UX) 이해:** 터미널 환경에서의 사용자 경험을 이해하고, 직관적인 인터페이스를 설계하는 능력.
* **커뮤니케이션:** 사용자 및 팀원들과 효과적으로 소통하고 협업하는 능력.

## 관련 모듈 (Related Modules)

* [`command_structure_design.md`](../modules/command_structure_design.md)
* [`parser_design.md`](../modules/parser_design.md)
* [`output_formatting_plan.md`](../modules/output_formatting_plan.md)
* [`testing_plan.md`](../modules/testing_plan.md)
* [`packaging_distribution_plan.md`](../modules/packaging_distribution_plan.md)
* [`auto_update_strategy.md`](../modules/auto_update_strategy.md)
* [`ci_cd_pipeline.md`](../modules/ci_cd_pipeline.md)
