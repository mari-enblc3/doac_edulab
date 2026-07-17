# DOAC English Lab

화·수·목 영어 학습 루틴을 위한 웹앱. DOAC(The Diary of a CEO) 영상을 인물별 인터뷰 스크립트(한글 병기)로 보고, 형광펜으로 모르는 표현을 모아 단어장을 만들고, summary·speaking을 준비/세션 진행한다.

- **빌드 없음** — `index.html` 단일 파일 (React + Tailwind + Inter/Pretendard, CDN). GitHub Pages에 그대로 서빙.
- **저장** — 브라우저 localStorage (기기별). 

## 사용법
1. `+ 영상 추가 → 스크립트 JSON`에 `packets/*.json` 내용을 붙여넣기 (또는 `데모 체험`).
2. 학습: 대본에서 모르는 표현 드래그 → 🖍 형광펜 → **단어 정리 → 단어장**.
3. 단어장에서 뜻/예문 채우기, chapter 마스터 체크.
4. Summary 작성 → 수정본 저장. 세션 탭에서 단어시험/Summary 리뷰/Speaking.

## 새 영상 대본 만들기
`대본만들기.md` 참고. (Claude에게 유튜브 링크를 주면 인터뷰 스크립트 JSON 생성)

## 패킷
- `packets/daniel-kokotajlo-ai.json` — "No One Is Ready For What's Coming" (Daniel Kokotajlo), Part 1.
