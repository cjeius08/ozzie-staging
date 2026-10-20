# Ozzie Staging Source & Isolation

## Active root (Visual Home pilot)
- Repository: `cjeius08/ozzie-staging`
- Branch: `main`
- File: `index.html`
- URL: `https://cjeius08.github.io/ozzie-staging/`
- Mode: **standalone static mock**, no production authentication or Supabase calls.

## Retained older staging app
- Repository: `cjeius08/zoom-support-navigator`
- Branch: `staging`
- Snapshot: `4d913da19bd00fa0c08aefebd3179917801f1f2f` (September 2026)
- URL: `https://cjeius08.github.io/ozzie-staging/legacy/`
- Build: `VITE_STAGING_MODE=true` with Vite base `/ozzie-staging/legacy/`

## Safety
- Live production `main` in `zoom-support-navigator` is **not** used or modified by staging deploys.
- This preview is intended to review the Visual Home / Classic Home layout and sample workflows before approval.
- Original deployment setup retained in `backup/staging-original-before-visual-home-20261020`.
