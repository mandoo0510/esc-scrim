# ESC SCRIM 리더보드

배그(PUBG) 스크림 실시간 리더보드 사이트입니다.

- 사이트: https://mandoo510.github.io/esc-scrim/
- 데이터: 구글 시트 점수판 → Google Apps Script 웹앱(JSON) → 이 페이지가 10초마다 자동 갱신
- 다른 시트 보기: 주소 끝에 `?id=시트ID`
- 방송(OBS)용 투명 화면: https://mandoo510.github.io/esc-scrim/obs.html (사이트 오른쪽 위 OBS 버튼에서 옵션 골라 주소 복사)
  - `?match=2` 매치 고정 · `&mode=one` 이 매치만 · `&top=10` 상위 N팀 · `&scale=1.3` 크기 · `&preview=1` 체크무늬 배경 미리보기

Apps Script를 새로 배포해서 주소가 바뀌면 `index.html` 위쪽의 `API` 값만 고치면 됩니다.

## 팀 로고

설정 시트(SCRIM 시트) 메뉴 **🏆 SCRIM → 🖼 팀 로고 올리기**에서 팀 이름과 이미지를 올리면, 같은 팀 이름을 쓰는 모든 시트의 리더보드에 자동으로 표시됩니다.
