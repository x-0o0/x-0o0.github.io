# x-0o0.github.io

Casebook 문서 사이트의 옛 주소(`https://x-0o0.github.io/casebook-legal/…`)를 새 주소(`https://casebook.whitemason.club/…`)의 같은 경로로 넘겨주는 저장소예요. 다른 내용은 두지 않아요.

- 배포: `main` 브랜치 루트를 GitHub Pages가 그대로 올려요(빌드 없음, `.nojekyll`).
- `casebook-legal/` 아래 파일 하나가 옛 주소 하나예요. 각 파일은 같은 경로 + 검색어 + `#앵커`를 새 주소로 넘겨요(`location.replace`, 보조로 meta refresh).
- `404.html`은 페이지가 없는 옛 경로를 같은 규칙으로 넘겨요. `/casebook-legal` 밖의 경로는 넘기지 않아요.
- 루트(`/`)는 일부러 404로 둬요. `index.html`을 만들지 않아요.

## 지킬 것

- 옛 경로 `/casebook-legal/…`의 폴더 · 파일 이름을 바꾸거나 지우지 않아요. App Store와 예전 링크가 이 경로를 써요.
- 새 블로그 글마다 페이지를 더하지 않아요. 이전(2026-10-12) 뒤 공개한 글은 옛 주소에 있었던 적이 없고, 옛 모양 주소로 와도 `404.html`이 새 주소로 넘겨요. 이미 있는 글 페이지는 그대로 둬요.
- 작업 시작 전과 푸시 바로 전에 `git pull --ff-only`를 해요. force push는 하지 않아요.
- 푸시한 뒤 `https://x-0o0.github.io/casebook-legal/<경로>`가 200이고 새 주소로 넘어가는지 확인해요.
