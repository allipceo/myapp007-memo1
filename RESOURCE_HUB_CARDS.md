# MyApp007 - Resource Hub (자산 카드)

이 프로젝트에서 추출된 재사용 가능 자산 카드들입니다.

---

### [Card A] MyApp007 Memo SSOT v3.1 (A: Spec/Design)
1) 제목: MyApp007 Memo SSOT v3.1 (A)
2) 요약: 게이트 기반(Gate 0-11) 소형 앱 개발 프로세스 완주 모델
3) 사용 조건: S등급(HTML 1파일) 프로젝트 전용 / 프로세스 엄격 준수 필수
4) 사용 방법: (1) Gate 0-7 승인 (2) M1-M3 구현 및 증거 확보 (3) Gate 11 자산화
5) 증거 링크: [README.md](https://github.com/allipceo/myapp007-memo1/blob/main/README.md)
6) 원본 링크: `MyApp007-001_memo1 앱개발 ssot v3.1.md`
7) 버전: v1.0 / SHA d090244

---

### [Card B] LocalStorage CRUD + XSS-Safe Rendering (B: Code Asset)
1) 제목: LocalStorage CRUD + XSS-Safe Rendering (B)
2) 요약: 보안이 강화된 브라우저 로컬 저장소 메모 관리 패턴
3) 사용 조건: Vanilla JS 전용 / innerHTML 절대 금지(textContent 필수)
4) 사용 방법: (1) try-catch 기반 save/load (2) innerHTML 구조 생성 후 (3) textContent로 데이터 주입
5) 증거 링크: [index.html#L235-L310](https://github.com/allipceo/myapp007-memo1/blob/main/index.html)
6) 원본 링크: `MyApp007-001_memo1 앱개발 ssot v3.1.md`
7) 버전: v1.0 / SHA d090244

---

### [Card D] Local-First App 운영 및 장애 복구 런북 (D: Operational Asset)
1) 제목: Local-First App 운영 및 장애 복구 런북 (D)
2) 요약: 서버 없는 JS 앱의 데이터 손상 및 보안 장애 대응 로직
3) 사용 조건: localStorage 사용 앱 / 데이터 복원 로직 구현 전제
4) 사용 방법: (1) JSON 파싱 실패 시 자동 초기화 (2) Quota 초과 시 사용자 안내 (3) XSS 회귀 테스트 수행
5) 증거 링크: [RUNBOOK.md](https://github.com/allipceo/myapp007-memo1/blob/main/RUNBOOK.md)
6) 원본 링크: `MyApp007-001_memo1 앱개발 ssot v3.1.md`
7) 버전: v1.0 / SHA d090244
