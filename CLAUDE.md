# Double Shot Latte - Fork Maintenance

## Fork Relationship

- **Origin (push)**: `cameronsjo/double-shot-latte`
- **Upstream (pull)**: `obra/double-shot-latte`

## Syncing Upstream

```bash
git fetch upstream
git merge upstream/main
```

## Where Customizations Live

- `README.md` — re-owned header
- `CLAUDE.md` — this file (fork-only)
- Hook logic modifications

## What Not to Touch When Merging

- `.claude-plugin/plugin.json` version bumps — accept upstream
- Core hook evaluation logic in hooks/ — accept upstream unless intentionally diverged
