# MyApp007 - Decision Log (핵심 결정 기록)

본 프로젝트 개발 과정에서 내려진 주요 기술적 결정 사항입니다.

## [Decision 1] 단일 파일(Single-file) 아키텍처 채택
- **결정**: `index.html` 하나에 HTML/CSS/JS를 모두 포함.
- **이유**: 소형 프로젝트(S등급)로서 외부 의존성을 배제하고 배포 및 유지보수의 편의성을 극대화하기 위함.

## [Decision 2] localStorage를 활용한 데이터 관리
- **결정**: 서버 연동 없이 브라우저 `localStorage`를 SSOT(Source of Truth)로 사용.
- **이유**: 서버 비용 및 관리 오버헤드를 제로화하고, 로컬 환경에서 즉각적인 반응성을 제공하기 위함.

## [Decision 3] textContent 기반의 엄격한 보안 렌더링
- **결정**: `innerHTML` 사용을 전면 금지하고 모든 사용자 입력값은 `textContent`를 통해 주입.
- **이유**: 소형 앱에서도 발생할 수 있는 XSS 공격을 원천 차단하고 보안 품질을 확보하기 위함.
