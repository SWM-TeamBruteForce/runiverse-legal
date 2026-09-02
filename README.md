# runiverse-legal

Runiverse의 법적 고지 문서. GitHub Pages로 배포한다.

| 파일 | 주소 | 용도 |
|---|---|---|
| `index.html` | `/` | 문서 목록 |
| `privacy.html` | `/privacy.html` | 개인정보처리방침 — **항상 현재 시행 중인 방침** |
| `account-deletion.html` | `/account-deletion.html` | 계정·데이터 삭제 안내 (Google Play 요건) |
| `privacy/archive/index.html` | `/privacy/archive/` | 이전 방침 목록 |

배포 주소: https://swm-teambruteforce.github.io/runiverse-legal/

## URL을 바꾸지 말 것

`privacy.html`과 `account-deletion.html`의 주소는 **앱(`LegalLinks` 상수)과 Google Play 콘솔에 등록되어 있다.** 파일명을 바꾸면 이미 배포된 앱에서 링크가 죽는다. 방침을 개정할 때도 이 두 파일의 주소는 그대로 두고 내용만 교체한다.

## 개정 절차

방침 §12에서 **시행 전 공지**와 **이전 방침 열람**을 약속했다. 시행일에 `privacy.html`을 덮어쓰기만 하면 사전 공지가 되지 않는다.

1. **시행 전** — `privacy.html`은 기존 내용을 그대로 두고, 상단에 변경 내용과 새 시행일을 안내한다. 이용자의 권리에 중대한 영향을 주는 변경이면 시행일 30일 전부터 띄운다.
2. **스냅샷** — 시행일이 오면 기존 `privacy.html`을 `privacy/archive/<기존 시행일>.html`로 복사한다. 파일명은 `2026-09-02.html` 형식.
3. **목록 갱신** — `privacy/archive/index.html`의 표에 기존 버전의 적용 종료일을 적고, 새 버전 행을 추가한다.
4. **교체** — `privacy.html`을 새 내용으로 바꾸고 시행일을 갱신한다.
5. **앱·콘솔** — 건드리지 않는다. URL이 그대로이기 때문이다.

**아카이브에 올린 스냅샷은 고치지 않는다.** 오탈자를 발견해도 덮어쓰지 말고 정정 사실을 따로 표시한다. 그래야 그때 무엇을 고지했는지가 남는다.

## 계정삭제 안내는 아카이빙하지 않는다

법정 문서가 아니고(Google Play는 삭제 경로 제공만 요구한다), 페이지 안에서 이력 보관을 약속하지도 않았다. 내용은 방침 §5의 요약이라 개정 이력은 방침 아카이브에 남는다.

## 개인정보 보호책임자

성명과 연락처는 `privacy.html` §11에 있다. 바뀌면 그 절을 고친다 — 방침 개정에 해당하므로 위 절차를 따른다.
