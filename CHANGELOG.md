# Changelog

## 0.1.6 - 2026-01-06
- Backup: stronger KDF-based encryption (legacy compatible), streaming export, and include media_rel/rec_cache.
- Backup restore: foreign_keys handling fixed and file import/export path handling hardened.
- Session history retention for events and snapshots to keep DB size bounded.
- Search: surface errors on failures, filter adult titles in online search, and auto-create session for actions after restore.

## 0.1.5 - 2025-12-30
- Automatic offline support: pause online operations, show offline status, and retry titles when back online.
- Update flow improvements: retry check, UI synced with install result, download/hash errors, and no PackageInstaller session leaks.
- Encrypted backup/restore with UI and stats.
- Prefetch/recommended: per-source pools, rotation, stale locks, recommended priority, and a single seed.
- AniList adjustments: global throttling, cooldown sync, and rate limit headers.
- Ladder: history replay, atomicity, and top-X insertion fixes.
- Search: escape LIKE wildcards.
- Stability/tooling: PyBridge robust to invalid JSON, scheduler probe, and side-by-side debug install.

## 0.1.4 - 2025-12-23
- Display compact tags (genres and relevant tags) on the browse cards.
- New anime selection criterion: Recommended.
- Auto-check for updates on app launch.
- New watchlist flow.
- Reordered buttons on the home screen.
- Fix auto-update issue

## 0.1.3 - 2025-12-23
- Share Top-10 ranking as a story-friendly image.
- In-app update download/install flow with SHA-256 verification and User-Agent fix.
- Eval undo starts disabled and only enables after an action.
- Ladder fixes (render title crash and finalize insert position).
- Elo undo import fix.
- Backfill by IDs now processes all items.
- Reset now clears eval locks.
- Performance: batch/transaction improvements for bootstrap and consolidate.
- Android migration and cleanup of legacy root Python files.

## 0.1.2 - 2025-12-22
- Selection criteria for AniList fetching (Popularidad/Aleatorio).
- Non-blocking prefetch to avoid running out of cards.
- UI polish and aesthetic updates.

## 0.1.1 - 2025-12-11
- First public release package with in-app update metadata.

## 0.1.0 - 2025-12-11
- Initial prototype release.
