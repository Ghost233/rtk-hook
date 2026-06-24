# Agent Instructions

## Git Identity

This repo must be authored by **Ghost233** (`only.yesc@gmail.com`).

- If current git user is NOT Ghost233, run `gh auth switch --user Ghost233` to switch.
- Verify with `git config user.name && git config user.email`.
- The `hooks/pre-commit` hook auto-sets the author on each commit, but also ensure the gh CLI session is correct before pushing.
