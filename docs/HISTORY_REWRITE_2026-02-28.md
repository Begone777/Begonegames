# History Rewrite Record (2026-02-28)

## Purpose

Perform a full repository history cleanup and reinitialize the project as a fresh baseline containing only the three active web games.

## Scope

Kept content:

- `WebGames/two-player-power-duel.html`
- `WebGames/red-light-green-light.html`
- `WebGames/survival-campfire-game.html`
- `README.md`
- `docs/HISTORY_REWRITE_2026-02-28.md`

Removed content:

- All previous project files not listed above
- Previous commit history references from `main` (via history rewrite)

## Operational Notes

- A local safety branch was created before rewrite:
  - `backup/pre-history-purge-2026-02-28-2106`
- `main` is force-updated to the new root commit.
- Existing collaborators with old clones must re-sync using a fresh clone or hard reset.

## Important GitHub retention caveat

Force-pushing rewritten history removes old commits from branch references, but underlying objects may remain on hosting infrastructure until GitHub garbage collection and retention processes complete.
