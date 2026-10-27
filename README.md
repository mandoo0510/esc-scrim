# ESC SCRIM 리더보드

배그(PUBG) 스크림 실시간 리더보드 사이트입니다.

- 사이트: https://mandoo510.github.io/esc-scrim/
- 데이터: ESC SCRIM 구글 시트 점수판 → Google Apps Script 웹앱(JSON) → 이 페이지가 10초마다 자동 갱신
- 다른 시트 보기: 주소 끝에 `?id=시트ID`
- 방송(OBS)용 투명 화면: https://mandoo510.github.io/esc-scrim/obs.html (사이트 오른쪽 위 OBS 버튼에서 옵션 골라 주소 복사)
  - `?match=2` 매치 고정 · `&mode=one` 이 매치만 · `&top=10` 상위 N팀 · `&scale=1.3` 크기 · `&bg=0.7` 배경 진하기(기본 0.55 반투명) · `&max=10` 약자로 바꿀 이름 길이(기본 8자 초과 → 단어 첫 글자, 예: 404 Error → 4E) · `&preview=1` 체크무늬 배경 미리보기

Apps Script를 새로 배포해서 주소가 바뀌면 `index.html` 위쪽의 `API` 값만 고치면 됩니다.

## 관리자

- 관리자 페이지: https://mandoo510.github.io/esc-scrim/admin.html
- 최초 관리자 계정은 ESC SCRIM 시트 메뉴 **🏆 SCRIM → 👑 최초 관리자 계정 만들기**에서 만듭니다.
- 최초 관리자는 관리자 페이지의 **관리자 계정** 탭에서 다른 관리자 계정을 만들고, 비밀번호 재설정 · 삭제를 할 수 있습니다.
- 로그인한 관리자만 OBS 방송 주소와 팀 로고 올리기를 쓸 수 있습니다. (비밀번호는 해시로만 저장)
