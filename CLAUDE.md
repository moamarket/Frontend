# MoA Frontend 작업 규칙 (Claude용)

규칙, 결정 로그, 기능 문서, 하네스는 모두 Backend 레포(moamarket/Backend)에 있다. 작업 전에 그 레포의 `CLAUDE.md`와 `docs/STATUS.md`를 먼저 읽는다.

- 화면 흐름은 `prototype/moa-prototype.html`을 따른다.
- 화면은 목데이터로 먼저 만든다 (D-42). 목데이터 모양은 Backend `docs/features/*.md` 3장의 API 응답을 따른다.
- git 규칙은 Backend와 같다: 이슈 → `[type]/#번호` 브랜치(develop에서) → `type : 변경` 커밋 → develop으로 PR. Claude trailer 금지. 이슈, PR, 댓글은 Claude가 만들지 않고 초안만 준다.
- 짧고 쉬운 한국어, 가운뎃점(·) 금지.
