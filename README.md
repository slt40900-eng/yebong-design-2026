# 예봉초 통합 설계 연수 사이트

2026 경기도교육청 찾아가는 교육과정-수업-평가 통합 설계 연수 · 남양주예봉초 2회차(3~4차시, 2026. 11. 11.) 자료 사이트입니다.

- 사이트: https://yebong-design-2026.netlify.app (연수안 8쪽 QR이 가리키는 주소)
- 게시: `main` 브랜치에 올리면 Netlify가 저장소 맨 위 폴더를 그대로 다시 게시합니다(빌드 없음, `netlify.toml`).
- 검색 제외: `index.html`의 `noindex` 메타, `robots.txt`, `_headers`(Netlify 전용).

## 폴더
- `index.html` — 페이지 전체(글 · 스타일 · 스크립트). 링크와 자료 목록은 스크립트 맨 위 `LINKS`, `FILES`, `MATS`에 있습니다.
- `files/` — 내려받는 한글(.hwpx) · PDF. 내려받을 때 이름은 `FILES`의 `name`.
- `slides/`, `thumbs/` — 교안 쪽 그림(크게 보기 1281×720, 작은 그림 384×216). 교안 PDF에서 다시 만듭니다.
- `fonts/` — 페이지에 쓰인 글자만 남긴 Pretendard(글을 새로 넣으면 다시 만들어야 할 수 있음).
