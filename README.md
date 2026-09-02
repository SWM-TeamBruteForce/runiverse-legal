# runiverse-legal

Runiverse의 법적 고지 문서. https://swm-teambruteforce.github.io/runiverse-legal/

| 파일 | 용도 |
|---|---|
| `privacy.html` | 개인정보처리방침 — 항상 현재 시행 중인 것 |
| `account-deletion.html` | 계정·데이터 삭제 안내 (Google Play 요건) |
| `privacy/archive/index.html` | 이전 방침 목록 |
| `index.html` | 문서 목록 |

## URL을 바꾸지 말 것

앞의 두 파일 주소는 **앱 `LegalLinks` 상수와 Google Play 콘솔에 등록돼 있다.** 파일명을 바꾸면 배포된 앱에서 링크가 죽는다. 개정할 때도 주소는 그대로 두고 내용만 교체한다.

## 개정 절차

방침 §12에서 시행 전 공지와 이전 방침 열람을 약속했다. **시행일에 덮어쓰기만 하면 사전 공지가 안 된다.**

1. 시행 전 — `privacy.html`은 기존 내용을 두고 상단에 변경 내용과 새 시행일을 안내한다. 중대한 변경이면 30일 전부터.
2. 시행일 — 기존 `privacy.html`을 `privacy/archive/<기존 시행일>.html`로 복사 (`2026-09-02.html` 형식)
3. `privacy/archive/index.html` 표에 기존 버전 종료일을 적고 새 행 추가
4. `privacy.html`을 새 내용으로 교체, 시행일 갱신

**아카이브 스냅샷은 고치지 않는다.** 오타를 찾아도 덮어쓰지 말고 정정 사실을 따로 표시한다.

계정삭제 안내는 아카이빙하지 않는다 — 법정 문서가 아니고 내용이 방침 §5의 요약이라 이력이 방침 아카이브에 남는다.

## 커밋 메시지

시행일이 바뀌는 변경인지가 갈려야 한다. 개정은 사전 공지 의무가 붙고 오타 수정은 안 붙는다.

```
개정: 만 14세 조항 신설 (시행 2026-10-01)
수정: 오타 — 몫→못
추가: 이용약관
```
