# Agent Instructions

## Git Identity

This repo must be authored by **Ghost233** (`only.yesc@gmail.com`).

- `hooks/pre-commit` aborts commit if author/committer isn't Ghost233.
- Verify with `git log -1 --format='Author: %an <%ae>%nCommitter: %cn <%ce>'`.
- Before push, ensure gh CLI session is correct: `gh auth status`.
