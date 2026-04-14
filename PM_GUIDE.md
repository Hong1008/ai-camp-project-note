# PM Operation Guide (PM_GUIDE.md)

이 문서는 홍 님이 부트캠프 프로젝트를 효율적으로 관리하고, 저(AI PM)와 최상의 시너지를 내기 위한 가이드라인입니다.

## 1. 프로젝트 초기화 (New Project)
1. `projects/` 디렉토리에 팀 프로젝트 레포지토리를 서브모듈로 추가합니다.
   ```bash
   git submodule add <repository-url> projects/<project-name>
   ```
2. `templates/project_brief.md`를 복사하여 프로젝트의 비전과 목표를 수립합니다.
3. `README.md`의 **Active Project Status** 표를 업데이트합니다.

## 2. 데일리 루틴 (Daily Routine)
- **오전 (Planning)**: 저에게 오늘의 목표를 말씀해 주세요. `daily_log.md` 템플릿을 사용하여 계획을 세웁니다.
- **오후 (Execution & Sync)**: 작업 중 발생하는 문제나 기술적 의문사항은 언제든 제게 질문해 주세요. (예: "서브모듈의 환경 변수 설정법이 궁금해", "이 API의 에러 처리를 어떻게 하면 좋을까?")
- **저녁 (Review)**: `daily_log.md`를 마무리하고 오늘 배운 점을 기록합니다.

## 3. 회고 및 고도화 (Retrospective & Polishing)
- 스프린트나 프로젝트가 끝날 때마다 `sprint_retro.md`를 작성합니다.
- 작성된 코드를 제게 보여주시면, **AGENTS.md**에 명시된 원칙(Modern Stack, Security, Scalability)에 따라 코드 리뷰를 진행합니다.

## 4. 커뮤니케이션 룰
- **질문 시**: 배경과 현재 상태를 함께 알려주시면 더 정확한 PM 가이드가 가능합니다.
- **코드 수정 시**: 단순한 코드 복사보다는 "왜 이렇게 수정하는지"에 대한 설명을 요청해 주세요.

---

> 이 가이드는 고정된 것이 아니며, 우리가 협업하며 필요에 따라 발전시켜 나갈 것입니다.
