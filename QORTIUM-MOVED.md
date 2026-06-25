# Qortium Core has moved to the QortiumDev org

Heads up 👋 — this repository is a fork of **`QuickMythril/qortium`**, which is being
retired. Active Qortium Core development now lives in the **QortiumDev** organization:

- **Canonical Core repo:** https://github.com/QortiumDev/qortium-core
- **All Qortium projects:** https://github.com/QortiumDev

The issue tracker on this fork is disabled, so this docs-only PR is just a heads-up.
`QuickMythril/qortium` will be deleted once forks have had a chance to re-point.

## Re-pointing this fork

GitHub can't change a fork's upstream, so pick whichever fits:

- **Keep this repo, just update your git remotes** to the new canonical repo:
  ```
  git remote set-url origin https://github.com/QortiumDev/qortium-core.git
  # or, if you track it as 'upstream':
  git remote set-url upstream https://github.com/QortiumDev/qortium-core.git
  git fetch --all
  ```
- **Or re-fork from the new home** — fork https://github.com/QortiumDev/qortium-core
  to get a fresh fork linked to the canonical repo (copy over any local branches you
  still need first).

Your existing code and history here are unaffected either way. Merging this PR just
leaves a durable pointer in your repo — feel free to close it instead if you prefer.

— QuickMythril
