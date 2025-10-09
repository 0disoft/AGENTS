# 모듈 가이드 (Modules Guide)

이 디렉토리에는 프로젝트를 구성하는 재사용 가능한 작업 단위인 '모듈'이 저장되어 있습니다. 각 모듈은 특정 작업을 수행하기 위한 지침이나 템플릿을 포함합니다.

## 모듈 목록 (알파벳 순)

- **[`api_design.md`](./api_design.md)**: 프론트엔드와 백엔드가 통신할 API의 명세를 설계합니다.
- **[`api_documentation_plan.md`](./api_documentation_plan.md)**: 다른 개발자들이 API를 쉽게 사용하도록 문서를 작성하고 관리할 계획을 세웁니다.
- **[`app_store_submission_plan.md`](./app_store_submission_plan.md)**: Apple App Store 및 Google Play Store 등록 계획을 수립합니다.
- **[`architecture.md`](./architecture.md)**: 프로젝트의 기술적 구조와 설계 원칙을 정의합니다.
- **[`auto_update_strategy.md`](./auto_update_strategy.md)**: 사용자 편의를 위한 자동 업데이트 기능의 구현 전략을 설계합니다.
- **[`background_jobs.md`](./background_jobs.md)**: 이메일 발송, 데이터 집계 등 시간이 오래 걸리는 작업을 백그라운드에서 처리하는 방식을 설계합니다.
- **[`browser_compatibility_plan.md`](./browser_compatibility_plan.md)**: Chrome, Firefox, Safari, Edge 등 타겟 브라우저별 호환성 확보 계획을 수립합니다.
- **[`caching_strategy.md`](./caching_strategy.md)**: 반복적인 요청에 대한 응답 속도 향상을 위해 캐시(Cache) 적용 전략을 수립합니다.
- **[`character_development.md`](./character_development.md)**: 주인공, 조력자, 적대자 등 주요 인물들의 성격, 배경, 목표를 설정합니다.
- **[`ci_cd_pipeline.md`](./ci_cd_pipeline.md)**: 지속적 통합 및 배포 파이프라인을 설계합니다.
- **[`command_structure_design.md`](./command_structure_design.md)**: CLI 도구의 명령어, 하위 명령어, 옵션 및 인수 구조를 설계합니다.
- **[`configuration_management.md`](./configuration_management.md)**: 사용자가 도구의 설정을 저장하고 관리하는 방식(예: `~/.config` 내 파일)을 설계합니다.
- **[`cover_art_and_illustration.md`](./cover_art_and_illustration.md)**: 작품의 표지 및 삽화에 대한 콘셉트와 계획을 세웁니다.
- **[`data_management.md`](./data_management.md)**: 데이터베이스, 스키마, ORM 등 데이터 처리 및 저장 방식을 결정합니다.
- **[`data_preprocessing_and_feature_engineering.md`](./data_preprocessing_and_feature_engineering.md)**: 데이터를 정제하고 모델이 학습하기 좋은 형태로 가공(피처 엔지니어링)합니다.
- **[`data_sourcing_and_collection.md`](./data_sourcing_and_collection.md)**: 모델 훈련에 필요한 데이터를 수집하고 확보하는 방안을 계획합니다.
- **[`database_schema_design.md`](./database_schema_design.md)**: 데이터베이스의 테이블 구조와 관계를 상세하게 설계합니다.
- **[`editing_and_revision.md`](./editing_and_revision.md)**: 완성된 원고의 문법, 문체, 스토리 개연성 등을 수정하고 퇴고합니다.
- **[`exploratory_data_analysis.md`](./exploratory_data_analysis.md)**: 수집된 데이터를 탐색하고 분석하여 인사이트를 도출합니다. (EDA)
- **[`extension_architecture.md`](./extension_architecture.md)**: 백그라운드 스크립트, 콘텐츠 스크립트, 팝업 등 확장 프로그램의 구조를 설계합니다.
- **[`idea_development.md`](./idea_development.md)**: 작품의 핵심 아이디어, 주제, 로그라인을 구체화합니다.
- **[`implementation_plan.md`](./implementation_plan.md)**: 실제 코드 개발에 대한 단계별 실행 계획을 수립합니다.
- **[`infrastructure_planning.md`](./infrastructure_planning.md)**: 서버, 배포, CI/CD 등 인프라 구축 계획을 세웁니다.
- **[`local_storage_plan.md`](./local_storage_plan.md)**: 오프라인 지원 등을 위한 디바이스 내부 데이터 저장 전략을 수립합니다.
- **[`logging_monitoring.md`](./logging_monitoring.md)**: 서비스 운영 중 발생할 수 있는 오류 로깅 및 성능 모니터링 방안을 수립합니다.
- **[`market_research.md`](./market_research.md)**: 타겟 시장, 사용자, 경쟁 환경을 분석하여 프로젝트의 방향성을 설정합니다.
- **[`ml_ops_and_monitoring.md`](./ml_ops_and_monitoring.md)**: 배포된 모델의 성능 저하(Drift)를 감지하고, 재학습 파이프라인을 구축하는 등 MLOps 방안을 설계합니다.
- **[`model_deployment_strategy.md`](./model_deployment_strategy.md)**: 완성된 모델을 실제 서비스에서 사용할 수 있도록 배포하는 전략(API, 배치 등)을 수립합니다.
- **[`model_evaluation.md`](./model_evaluation.md)**: 훈련된 모델의 성능을 다양한 평가지표를 통해 객관적으로 측정합니다.
- **[`model_selection.md`](./model_selection.md)**: 문제에 가장 적합한 머신러닝 모델(회귀, 분류 등)의 종류를 선택합니다.
- **[`model_training_and_tuning.md`](./model_training_and_tuning.md)**: 선택된 모델을 데이터로 훈련시키고, 최적의 성능을 내도록 하이퍼파라미터를 튜닝합니다.
- **[`monetization_strategy.md`](./monetization_strategy.md)**: 유료/무료 모델, 외전 판매 등 수익화 전략을 결정합니다.
- **[`native_os_integration.md`](./native_os_integration.md)**: 파일 시스템 접근, OS 알림 등 네이티브 운영체제 기능 연동 계획을 수립합니다.
- **[`output_formatting_plan.md`](./output_formatting_plan.md)**: 테이블, 색상, 진행률 표시줄 등 사용자가 보기 좋은 터미널 출력 형식을 계획합니다.
- **[`packaging_distribution_plan.md`](./packaging_distribution_plan.md)**: 각 운영체제에 맞는 설치 파일(.exe, .dmg 등) 패키징 및 배포 계획을 수립합니다.
- **[`payment_gateway.md`](./payment_gateway.md)**: 결제 시스템 연동에 필요한 사항을 계획하고 설계합니다.
- **[`permissions_and_security.md`](./permissions_and_security.md)**: `manifest.json`에 명시할 권한을 최소한으로 요청하고, 보안 위협에 대비하는 계획을 세웁니다.
- **[`platform_and_promotion.md`](./platform_and_promotion.md)**: 웹소설을 연재할 플랫폼(시리즈, 문피아 등)을 선정하고, 홍보 계획을 수립합니다.
- **[`platform_selection.md`](./platform_selection.md)**: iOS, Android, 크로스플랫폼 등 개발할 플랫폼을 결정합니다.
- **[`plot_and_outline.md`](./plot_and_outline.md)**: 발단-전개-위기-절정-결말의 전체 줄거리와 챕터별 세부 구성을 설계합니다.
- **[`problem_definition.md`](./problem_definition.md)**: 해결하고자 하는 문제를 정의하고, 성공을 측정할 지표를 설정합니다.
- **[`push_notification_strategy.md`](./push_notification_strategy.md)**: 사용자 재방문 및 상호작용을 위한 푸시 알림 전략을 설계합니다.
- **[`rate_limiting_plan.md`](./rate_limiting_plan.md)**: 서비스 안정성을 위해 사용자 또는 IP별 API 요청 횟수를 제어하는 전략을 설계합니다.
- **[`security_audit.md`](./security_audit.md)**: 애플리케이션의 보안 취약점을 점검하고 강화 방안을 계획합니다.
- **[`serialization_schedule.md`](./serialization_schedule.md)**: 독자들을 위해 주 몇 회, 어떤 요일에 연재할지 계획을 수립합니다.
- **[`state_management.md`](./state_management.md)**: 프론트엔드 애플리케이션의 복잡한 상태 관리 전략을 수립합니다.
- **[`tech_stack_selection.md`](./tech_stack_selection.md)**: 프로젝트에 사용할 프로그래밍 언어, 프레임워크, 라이브러리를 선정합니다.
- **[`testing_plan.md`](./testing_plan.md)**: 프로젝트의 안정성을 보장하기 위한 테스트 전략과 범위를 정의합니다.
- **[`ui_ux_design.md`](./ui_ux_design.md)**: 사용자 경험(UX)과 사용자 인터페이스(UI)를 설계합니다.
- **[`user_authentication.md`](./user_authentication.md)**: 사용자 회원가입, 로그인 등 인증 로직을 설계합니다.
- **[`user_stories.md`](./user_stories.md)**: 사용자 관점의 요구사항과 기능 시나리오를 구체적으로 작성합니다.
- **[`webstore_submission_plan.md`](./webstore_submission_plan.md)**: Chrome 웹 스토어, Firefox Add-ons 등 각 마켓플레이스 등록 및 검수 과정을 계획합니다.
- **[`world_building.md`](./world_building.md)**: 작품의 배경이 되는 세계관, 시대, 사회, 규칙 등을 설계합니다.
- **[`writing_and_drafting.md`](./writing_and_drafting.md)**: 설정과 줄거리에 따라 실제 원고를 집필합니다.
