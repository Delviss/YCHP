<p align="center">
  <img src="assets/brand/logo.jpg" alt="YCHP — Your Curated Holiday Planner" width="220">
</p>

<h1 align="center">Your Curated Holiday Planner (YCHP)</h1>

<p align="center">
  <em>YCHP turns "I could never afford that" into "I have been saving, and it is booked."</em>
</p>

---

## What YCHP is

YCHP is a travel booking platform that makes a great holiday feel reachable. Instead of a long, cluttered list of rooms, YCHP hand-picks stays and deals, lets people save toward a trip over time, and guides travellers from the first idea to a confirmed booking.

At launch, the heart of the platform is **hotels and other places to stay**. Around that core, YCHP adds three things ordinary booking sites don't offer together: curated (not overwhelming) choices, deals beyond the room — dining, spa, activities — and a built-in savings wallet, usable alone or as a group.

## Documentation

📖 **Read the docs: <https://delviss.github.io/YCHP/>**

The documentation is a [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) site built from [`docs/`](docs/) and organised into six sections:

| Section | Covers |
|---|---|
| **Home** | Overview, getting started for travellers and property owners |
| **Platform** | Features, the Savings Wallet & Group Savings (Stokvel), users & access |
| **Trust & Safety** | Property verification, cancellations & refunds, wallet regulation, legal |
| **Business** | Market, differentiators, commission, phases, roadmap, decisions, success metrics |
| **Brand** | Colour, typography, logo, voice & tone, applying the brand |
| **Development** | How we work, local setup, contributing to the docs |

Two companion documents referenced throughout are maintained separately:

- **Product Requirements Document** — every feature described in full, for the whole team.
- **Technical Requirements Document** — the build approach for web and mobile.

## Brand at a glance

| | |
|---|---|
| 🟫 **Gold** `#B8804A` | Logo, accents, badges |
| ⬛ **Navy** `#14263D` | Text, headlines, trust |
| ⬜ **Ivory** `#F5EDE0` | Primary background |

Full palette, contrast guidance and usage rules in the [Brand › Colour Palette](docs/brand/colour.md).

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
