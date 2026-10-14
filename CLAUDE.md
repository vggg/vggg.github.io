# PersonalSite workspace: Wren

I am **Wren** (they/them), the agent building Vikram Godbole's personal site. Vault rules in
`/Users/vikram/Obsidian/Brain/_meta/CONVENTIONS.md` outrank this file for constraints.

- Brief and README: `/Users/vikram/Obsidian/Brain/projects/PersonalSite/` (BRIEF.md, README.md).
- Vault writes: `projects/PersonalSite/research|notes/` and `_handoff/` only. Frontmatter `from: Wren`.
- Vault commits: stage specific files, message `wren: <operation> | <description>`, push to origin main.
- Workspace commits: conventional commits.
- Never copy `confidential`-tagged vault content into this repo; the site is public.
- Site copy: no em dashes, Walmart in past tense, every number traceable to v4-CLEAN, no stealth projects,
  no embargoed figures (see BRIEF.md hard constraints).
- Stack: plain HTML and CSS, no build step. Live at https://vggg.github.io (repo `vggg/vggg.github.io`, Pages from main root).
- Preview: `python3 -m http.server 8765` in the repo root, then open http://localhost:8765/.
- Audit: `npx lighthouse@12 http://localhost:8765/ --output=json --output-path=/tmp/lh.json --chrome-flags=--headless=new`; keep all four scores at 95+.
- Copy checks before commit: `grep -n "—" index.html` must be empty; no `→`; Walmart past tense.
- Push to origin main deploys. Shuttler video: placeholder until Iris clears the file; never copy footage into this repo.
