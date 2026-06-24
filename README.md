# rtk-hook

Codex plugin marketplace for the RTK `PreToolUse` hook.

This migrates RTK's old Codex `AGENTS.md` / `RTK.md` guidance into a standard
Codex plugin hook. It does not patch RTK itself.

The hook reads `rules.json`. Any shell command that is not already prefixed
with `rtk` is blocked with a retry suggestion.

## Install

```sh
codex plugin marketplace add /Users/admin/code/rtk-hook
codex plugin add rtk-hook@rtk-hook
```

Start a new Codex thread, then run `/hooks` and trust the `RTK Hook` hook.

## Update

```sh
codex plugin add rtk-hook@rtk-hook
```

Start a new thread after updating. If the hook changed, trust it again with `/hooks`.
