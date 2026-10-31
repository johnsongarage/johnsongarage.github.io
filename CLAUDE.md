# CLAUDE.md

존슨거라지(Johnson Garage) 홈페이지 저장소. 단일 정적 사이트(`index.html`, 대표 소개 `about/`)이며 GitHub Pages로 `https://johnsongarage.github.io/`에 배포된다.

## 사업 본부 연동 (kery27/hq)

이 프로젝트는 가르시아의 사업 본부 저장소 `kery27/hq`와 연결되어 있다.

- 세션을 시작할 때: `kery27/hq`를 세션에 추가하고 `STRATEGY.md`, `DECISIONS.md` 최근 항목,
  `projects/homepage.md`를 읽는다. 지금 방향과 어긋나는 작업이면 먼저 말한다.
- 작업을 마칠 때 (의미 있는 진척이 있었을 때만):
  - `projects/homepage.md`의 "현재 상태"와 "남은 일"을 갱신한다.
  - 사업 방향에 영향을 주는 결정(범위·가격·고객·중단/재개)은 `DECISIONS.md` 맨 위에 추가한다.
  - 커밋 메시지는 `[homepage] 무엇을` 형식으로 hq에 푸시한다.
- 고객 실데이터·개인정보·비밀번호는 hq에 절대 쓰지 않는다.
