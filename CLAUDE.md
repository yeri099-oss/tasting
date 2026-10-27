# 작업 규칙

- 변경 사항은 작업 브랜치에 커밋한 뒤, 항상 `main` 브랜치에도 바로 push 한다 (`git push origin HEAD:main`).
  사이트(GitHub Pages)가 `main`에서 배포되므로 따로 PR을 만들지 않는다.
- push 전에 `git fetch origin main`으로 최신 `main`을 받아 합친 뒤 올린다 (force-push 금지).
