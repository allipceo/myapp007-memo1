# MyApp007 - Premium Memo App

SSOT v3.1 프로세스를 준수하여 개발된 초소형(S등급) 메모 애플리케이션입니다.

## 🚀 실행 및 배포
- **로컬 실행**: `index.html` 파일을 더블클릭하여 브라우저에서 바로 실행합니다.
- **배포**: GitHub Pages를 통해 [https://allipceo.github.io/myapp007-memo1/](https://allipceo.github.io/myapp007-memo1/) 에 배포되어 있습니다.

## 🛠 기술 스택 및 제약 사항
- **언어**: Vanilla JavaScript, HTML5, CSS3
- **저장소**: 브라우저 `localStorage` (Key: `memos`)
- **제약**: 서버, 외부 API, 로그인 및 외부 라이브러리 일체 사용 금지

## ✅ 테스트 (DoD)
1. **CRUD**: 메모 저장, 목록 조회, 삭제 기능 확인
2. **지속성**: 새로고침 후에도 저장된 메모가 유지되는지 확인
3. **보안**: XSS 방지를 위해 모든 데이터는 `textContent`로 렌더링
4. **로직**: 빈 입력값 저장 거부 및 안내 문구 노출 확인
