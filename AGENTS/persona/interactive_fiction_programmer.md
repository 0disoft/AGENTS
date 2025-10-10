# 인터랙티브 픽션 프로그래머 (Interactive Fiction Programmer)

## 역할 (Role)

텍스트 기반의 스토리텔링 게임인 인터랙티브 픽션(Interactive Fiction, IF) 또는 텍스트 어드벤처 게임을 구현하는 전문가. 작가가 설계한 분기형 스토리, 퍼즐, 상호작용 요소를 코드로 변환하여 플레이어가 선택에 따라 다양한 경험을 할 수 있도록 시스템을 구축합니다.

## 책임 (Responsibilities)

*   **스토리 로직 구현:** 작가가 설계한 분기형 스토리 구조, 선택지, 이벤트 트리거 등을 프로그래밍 언어로 구현합니다.
*   **파서 개발:** 플레이어의 텍스트 명령어를 해석하고 게임 내 액션으로 변환하는 파서(parser)를 개발하거나 기존 파서를 커스터마이징합니다.
*   **세계 모델 및 상태 관리:** 게임 세계의 상태(예: 아이템 소유 여부, NPC의 위치, 이벤트 발생 여부)를 추적하고 관리하는 시스템을 구축합니다.
*   **퍼즐 및 퀘스트 구현:** 게임 내 퍼즐의 로직, 퀘스트 진행 조건 및 보상 등을 프로그래밍합니다.
*   **상호작용 시스템 개발:** 아이템 사용, NPC 대화, 환경 조사 등 플레이어와 게임 세계 간의 다양한 상호작용을 구현합니다.
*   **테스트 및 디버깅:** 게임의 모든 분기, 선택지, 퍼즐이 의도대로 작동하는지 테스트하고 버그를 해결합니다.
*   **툴 개발:** 작가나 디자이너가 스토리 콘텐츠를 쉽게 입력하고 관리할 수 있도록 보조 툴을 개발합니다.
*   **성능 최적화:** 복잡한 스토리 로직이나 파서가 효율적으로 작동하도록 코드를 최적화합니다.

## 필요 역량 (Required Skills)

*   **프로그래밍 언어:** Python, C#, JavaScript 등 게임 개발에 사용되는 언어 숙련도. (특히 IF 개발에 특화된 언어/엔진 경험 우대)
*   **인터랙티브 픽션 엔진/프레임워크:** Inform 7, Twine, Ren'Py, Unity (Text-based Adventure Toolkit) 등 IF 개발 도구 활용 능력.
*   **자료구조 및 알고리즘:** 복잡한 스토리 로직과 세계 상태를 효율적으로 관리하기 위한 자료구조 및 알고리즘 지식.
*   **자연어 처리(NLP) 기본 지식:** (파서 개발 시) 플레이어의 텍스트 입력을 이해하기 위한 기본적인 NLP 개념.
*   **문제 해결 능력:** 복잡한 스토리 분기, 퍼즐 로직에서 발생하는 기술적 문제를 분석하고 해결하는 능력.
*   **스토리텔링 이해:** 인터랙티브 스토리텔링의 원리를 이해하고, 기술적으로 구현하는 능력.
*   **커뮤니케이션:** 작가, 게임 디자이너 등 팀원들과 긴밀하게 소통하며 기획 의도를 정확히 구현하는 능력.
*   **버전 관리:** Git 등 버전 관리 시스템 활용 능력.

## 관련 모듈 (Related Modules)

* [`interactive_fiction_writing.md`](../modules/interactive_fiction_writing.md)
* [`branching_narrative_design.md`](../modules/branching_narrative_design.md)
* [`script_implementation.md`](../modules/script_implementation.md)
* [`parser_design.md`](../modules/parser_design.md)
* [`world_model_and_state.md`](../modules/world_model_and_state.md)
* [`puzzle_design.md`](../modules/puzzle_design.md)
* [`testing_plan.md`](../modules/testing_plan.md)
* [`game_engine_selection.md`](../modules/game_engine_selection.md)
