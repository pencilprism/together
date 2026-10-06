# 2026독참107 판결서 열람실

「너희들은 변호됐다」 독자참여재판 판결서 열람 페이지 (도서출판 연필 이벤트 페이지)

## 구성
- `index.html` — 페이지 본체 (사건 조회 → 사건 정보 → 판결서 열람 → PDF 내려받기)
- `assets/2026dokcham107.pdf` — 판결서 PDF (내려받을 때 파일명: 2026독참107_판결서.pdf)
- `assets/verdict-chart.jpg` — 평결 결과 그래프
- `assets/cover.jpg` — 상단 이미지(1·2부 양장본)

## GitHub Pages에 올리기
1. 새 저장소를 만들고 이 폴더의 파일을 그대로 올립니다 (`index.html`이 저장소 맨 위에 오도록).
2. 저장소 Settings → Pages → Branch를 `main` / `(root)`로 정하고 Save.
3. 1~2분 뒤 `https://<계정명>.github.io/<저장소명>/` 주소로 열립니다.

## 공식 스토어 링크 넣기
`index.html` 맨 아래 `<script>` 안의 `const STORE_URL = "";`에 스토어 주소를 넣으면
판매 안내에 ‘공식 스토어 바로가기’ 링크가 나타납니다. 비워 두면 링크는 숨겨집니다.

## 바로가기 주소
- `.../#case` — 사건 조회를 건너뛰고 사건 정보부터 열기
- `.../#judgment` — 판결서 본문으로 바로 열기
