# MoA Frontend
MoA(인플루언서 댓글 선착순 플리마켓) 모바일 웹 화면 레포.

## 레포 구성 (moamarket)
| 레포 | 내용 |
|---|---|
| [Backend](https://github.com/moamarket/Backend) | Spring Boot API, 기획과 설계 문서(`docs/`), 하네스 |
| Frontend (여기) | 모바일 웹 화면 |
| [Infra](https://github.com/moamarket/Infra) | 배포 설정 (배포 시작 때 채움) |

## 지금 상태
- 프레임워크는 아직 안 정함. 화면은 목데이터로 먼저 만든다 (Backend `docs/requirements.md` D-42).
- 화면 흐름 기준: `prototype/moa-prototype.html` (브라우저로 열면 됨).
- API 모양은 Backend `docs/features/*.md` 3장.

## 처음 클론했다면
```
git config core.hooksPath .githooks
```
커밋 메시지 형식(`type : 변경`)과 develop, main 직접 푸시를 검사하는 hook이 켜진다.
