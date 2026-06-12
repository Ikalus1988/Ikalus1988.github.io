# Ikalus1988 Personal Site v2.2

Zero-Dep personal technical harbor for Ikalus1988.

This package contains a static GitHub Pages-ready personal website plus the approved v2.2 proposal/spec/acceptance documents.

## Package Layout

```text
ikalus1988-personal-site-v2.2-package/
├── README.md
├── site/
│   ├── index.html
│   ├── manifest.json
│   └── llms.txt
└── docs/
    ├── SUMMARY.md
    ├── PROPOSAL.md
    ├── SPEC.md
    └── ACCEPTANCE.md
```

## Site Files

Copy everything under `site/` to the root of your GitHub Pages repository.

Required deployed files:

```text
index.html
manifest.json
llms.txt
```

Recommended repository name:

```text
Ikalus1988.github.io
```

## Local Preview

Open this file directly in a browser:

```text
site/index.html
```

No build step, package manager, backend, database, CMS, external font, or third-party UI framework is required.

## Deployment Notes

1. Create or open the GitHub Pages repository.
2. Copy these files into the repository root:
   - `site/index.html`
   - `site/manifest.json`
   - `site/llms.txt`
3. Commit and push to `main`.
4. Enable GitHub Pages from the repository root if it is not already enabled.
5. Visit `https://Ikalus1988.github.io`.

## Release Checklist

Before public launch:

- [ ] Open `index.html` locally and verify Profile, Artifacts, Case Studies, and Terminal.
- [ ] Test Terminal commands: `help`, `about`, `misaka`, `rag`, `logs`, `contact`, `neofetch`, `pulse`, `clear`, `exit`.
- [ ] Verify `/manifest.json` is valid JSON.
- [ ] Verify `/llms.txt` is reachable.
- [ ] Check mobile width around 375px for no horizontal overflow.
- [ ] Verify `https://misakanet.org/journey/` fallback behavior after deployment.
- [ ] Confirm whether `bot@misakanet.org` can receive email; if not, keep it marked as planned or replace it.
- [x] Snapshot commit placeholder replaced with real SHA `a99fbd6`.

## Current Known Placeholders

- `bot@misakanet.org` is currently marked as planned and should be verified before public launch.
- Snapshot commit fingerprint is `a99fbd6` (initial commit of this repo).
- Two Case Studies are marked `Draft / Coming in Q3`.

## Design Documents

The approved v2.2 documents are included in `docs/`:

- `SUMMARY.md`: compact project entrypoint and current release boundaries.
- `PROPOSAL.md`: identity, narrative, information architecture, and non-goals.
- `SPEC.md`: visual rules, Profile, Terminal, iframe, Snapshot, machine-readable surfaces, performance/accessibility.
- `ACCEPTANCE.md`: release red lines, non-blocking items, and test scenarios.

## Core Identity

Auditable Knowledge Systems Builder.

I build small, auditable, long-running knowledge systems for swarm intelligence, industrial RAG, decentralized knowledge, and automation-resistant engineering.
