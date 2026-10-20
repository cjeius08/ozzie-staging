# Ozzie Staging — Visual Home Review

This is an **isolated, non-production** GitHub Pages staging website for Ozzie for Ogletree.

- **[Visual Home prototype](https://cjeius08.github.io/ozzie-staging/)** — visual-first vs. classic Home toggle, sample search scenarios, dummy guided troubleshooting, day/night, and approved-call-flow demonstration.
- **[Previous September dummy Ozzie app](https://cjeius08.github.io/ozzie-staging/legacy/)** — preserved original staging build, not the October production version.
- **[Live production Ozzie](https://cjeius08.github.io/zoom-support-navigator/)** — separate; never modified by this repository.

The Visual Home prototype is standalone static HTML; its actions use mock/sample content only. It does **not** sign in, query Supabase, save feedback, or change user data.

Deployment: GitHub Actions on staging repo `main` uploads `index.html` at the root and copies the older staging-branch build under `/legacy/`. To restore the former root experience, the deployment workflow and HTML are backed up at branch `backup/staging-original-before-visual-home-20261020`.
