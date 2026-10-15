# x-0o0.github.io

Casebook 문서 사이트의 옛 주소(`https://x-0o0.github.io/casebook-legal/…`)를 새 주소(`https://casebook.whitemason.club/…`)의 같은 경로로 넘겨주는 페이지만 있어요.

- `casebook-legal/` 아래에 주요 페이지와, 이전(2026-10-12) 전에 공개한 블로그 글의 넘겨주기 페이지가 있어요. 이전 뒤에 이미 만든 글 페이지 3개(10월 12일 · 10월 13일 개발일지, 앱 구조 글)도 그대로 둬요.
- 새 글에는 페이지를 만들지 않아요. 새 글을 포함해 그 밖의 경로는 `404.html`이 같은 규칙으로 넘겨줘요.
- 검색어와 `#앵커`(예: `#support`, `#p11`)도 그대로 넘겨줘요. JavaScript가 꺼져 있으면 meta refresh로 넘겨주고, 이때는 앵커가 빠져요.
- 루트(`https://x-0o0.github.io/`)는 일부러 비워 둬요(404).
- 문서 사이트 원본: whitemason/casebook-pages
