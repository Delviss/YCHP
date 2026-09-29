# Contributing to the Docs

---

## Repository Structure

```
mkdocs.yml               Site config and navigation
requirements.txt         Python dependencies
docs/
  index.md               Home → Overview
  getting-started/       Home → For Travellers / Property Owners
  features/              Platform → Features
  wallet/                Platform → Wallet
  users-access/          Platform → Users & Access
  *.md                   Trust & Safety and Business pages
  brand/                 Brand
  development/           Development
  assets/                Logo and images
  stylesheets/extra.css  YCHP theme (Gold / Navy / Ivory)
```

---

## Adding a Page

1. Create a Markdown file in the right folder under `docs/`.
2. Add it to the `nav:` section of `mkdocs.yml`.
3. Run `mkdocs build --strict` to check for broken links.
4. Open a pull request against `main`. Once merged, the site deploys automatically.

---

## Writing Style

Follow [Voice & Tone](../brand/voice-tone.md): plain, warm and jargon-free.

| Element | Use for |
|---|---|
| `!!! note` | Decisions |
| `!!! info` | Context and timing |
| `!!! warning` | Things that are in progress or must be avoided |
| `!!! tip` | Helpful pointers |
| Mermaid | Flows and timelines |
