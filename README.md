<p align="center">
  <img src="assets/brand/logo.jpg" alt="YCHP — Your Curated Holiday Planner" width="220">
</p>

<h1 align="center">Yana</h1>

<p align="center">
  <strong>by Your Curated Holiday Planner</strong><br>
  <em>Curated travel. A smarter way to save for it.</em>
</p>

---

## What Yana is

Yana is a curated travel platform designed to make exceptional holidays feel achievable, not intimidating. It combines selected luxury stays and experiences with a built-in wallet that lets people save toward travel over time, on their own or together with family and friends.

It launches with five tabs: **Hotels · Deals · Curation · Experiences · Wallet** (personal and group saving). Flights, car hire and an AI travel assistant follow once the launch foundation is stable.

> **The Yana promise:** turn "one day" into "we're going".

## Documentation

📖 **Read the docs: <https://delviss.github.io/YCHP/>**

The documentation is a [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) site built from [`docs/`](docs/) and organised into six sections:

| Section | Covers |
|---|---|
| **Home** | Overview, getting started for travellers and property owners |
| **Platform** | Features, the Yana Wallet & Group Saving, users & access |
| **Trust & Safety** | Property verification, cancellations & refunds, wallet regulation, legal |
| **Business** | Market, differentiators, commission, phases, roadmap, decisions, success metrics |
| **Brand** | Colour & tokens, UI principles, typography, logo, voice & tone, applying the brand |
| **Development** | How we work, local setup, contributing to the docs |

Two companion documents referenced throughout are maintained separately:

- **Product Requirements Document** — every feature described in full, for the whole team.
- **Technical Requirements Document** — the build approach for web and mobile.

## Brand at a glance

| | |
|---|---|
| **Yana Blue** `#18A6C9` | Hero brand colour, highlights, progress |
| **Deep Tide** `#123E52` | Navigation, headings, wallet and trust |
| **Warm Ivory** `#FAF8F4` | Primary app background |

Full palette, developer tokens, contrast guidance and usage rules in the [Brand › Colour Palette](docs/brand/colour.md).

## Repository structure

```
mkdocs.yml        Site config and navigation
requirements.txt  Python dependencies for the docs site
docs/             Documentation pages (Markdown)
assets/brand/     Logo and brand imagery
```

## Run the docs locally

```bash
pip install -r requirements.txt
mkdocs serve
```

Every push to `main` builds the site and deploys it to GitHub Pages.
