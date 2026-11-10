# Adagio 작업 규칙

- 사이트는 `index.html` 한 파일 + `audio/*.mp3`로 된 정적 사이트다. GitHub Pages(main, root)로 배포한다.
- 같은 사이트가 claude.ai 아티팩트(https://claude.ai/artifact/EGXriY1HUhaADL38ur5eiN)로도 게시되어 있다. 아티팩트 쪽 원본은 문서 뼈대(`<!doctype>`, `<head>`) 없이 `<title>`부터 시작하고, 저장소의 `index.html`은 그 내용을 head/body 뼈대로 감싼 것이다.
- **변경할 때마다**:
  1. 버전을 올린다 (상단 `#ver`, 하단 `.ver-foot`, 감상 화면 `.stage-ver`, 정보 화면 제목 `#infoT`).
  2. 정보 화면 '업데이트 기록'(`ol.hist`) 맨 위에 새 항목을 추가하고 `li.cur`를 옮긴다.
  3. `CHANGELOG.md` 맨 위에 같은 내용을 추가한다.
  4. 아티팩트를 다시 게시하고, 이 저장소 `main`에 커밋·푸시한다.
- 음원은 퍼블릭 도메인/CC0/CC BY 계열만 쓰고, README 표와 사이트의 곡별 크레딧(`CREDIT`)을 함께 갱신한다.
- 사용자와의 대화는 한국어로 한다.
