# CLAUDE.md

## Skills

Installed in `.claude/skills/`:

- `stop-slop` — run on any copy, content or prose before delivering it.
- `ui-ux-pro-max` — use for any landing page, dashboard, app UI or design system work.
- `task-observer` — invoke before the first tool call of every session.
- `find-skills` — use when asked to find or suggest skills for a task.

## Task Observer storage

Sessions here run in disposable cloud containers. Keep the observation log
and staged skill updates inside this repo so they survive:

- Observations: `skill-observations/observation-log/`
- Proposed skill updates: `skill-updates/`

Commit and push both folders at the end of any session that wrote to them.
