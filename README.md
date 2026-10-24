# ESC SCRIM 리더보드

배그(PUBG) 스크림 실시간 리더보드 사이트입니다.

- 사이트: https://mandoo510.github.io/esc-scrim/
- 데이터: 구글 시트 점수판 → Google Apps Script 웹앱(JSON) → 이 페이지가 10초마다 자동 갱신
- 다른 시트 보기: 주소 끝에 `?id=시트ID`
- 방송(OBS)용 투명 화면: 주소 끝에 `?obs=1`
- 특정 매치 고정: `?match=2`

Apps Script를 새로 배포해서 주소가 바뀌면 `index.html` 위쪽의 `API` 값만 고치면 됩니다.
