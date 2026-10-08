# Yana Brand Guidelines

**Yana, by Your Curated Holiday Planner.** Curated travel. A smarter way to save for it.

This guide defines how Yana should look, feel and sound across web, mobile and marketing. The palette, developer tokens and UI principles come from "Yana – Product Vision & Roadmap", v1.0 (September 2026). Typography and voice carry over from the earlier YCHP guidelines until the final design system is confirmed.

> **What changed:** the earlier gold / navy / ivory palette, which was taken from the YCHP crest, is replaced for the product interface by the **Yana blue palette** below. The crest is now the parent YCHP mark (see Section 5).

---

## 1. Brand essence

> Turn "one day" into "we're going", by helping people discover, save for and book exceptional travel.

Yana is built for African travellers first, with global destinations and global ambition. It should feel **contemporary and universal**, not themed around a single country, language or idea of what "Africa" looks like.

**Yana should feel fresh, optimistic and premium, never grandstanding.** It is not a budget travel app. It is a luxury travel platform that gives people a more realistic way to fund and organise exceptional trips, and it must stay accessible enough to use every week while saving.

| Pillar | What it means in practice |
|---|---|
| **Curated, not cluttered** | A considered set of stays, offers and experiences, never an endless grid. |
| **Save your way** | Travel as progress over time, not one large, all-at-once expense. |
| **Travel together** | Group saving that is easy to organise, fund and understand. |
| **Premium, still welcoming** | Luxury in the experience and design, without feeling exclusive or intimidating. |

Closer to: **Luxury Escapes** (calm, premium, edited). Actively avoid: **Agoda / Trip.com** (dense, promotional, overwhelming).

---

## 2. Colour palette

Blue is the signature: bright enough to feel like travel and possibility, grounded by a deeper ocean tone for trust and financial moments.

| Colour | Hex | Primary use |
|---|---|---|
| **Yana Blue** | `#18A6C9` | Hero brand colour, highlights, icons, progress |
| **Yana Blue Deep** | `#0B7E99` | Primary actions where stronger contrast is needed |
| **Deep Tide** | `#123E52` | Navigation, headings, wallet and trust moments |
| **Soft Blue** | `#DDF4F8` | Selected states, cards and gentle backgrounds |
| **Yana Sand** | `#E8D8C3` | Warm secondary accent |
| **Warm Ivory** | `#FAF8F4` | Primary app background |
| **Ink** | `#19282E` | Primary text |
| **Slate** | `#66777D` | Secondary text |
| **Mist** | `#E5EBED` | Borders, dividers and disabled states |

### How the palette should behave

- **Light interface first.** Warm Ivory and white dominate the canvas.
- **Blue punctuates, it doesn't flood.** Yana Blue creates recognition and optimism; don't use it on every surface.
- **Deep Tide carries trust.** Headings, navigation and wallet moments.
- **Sand supports.** It is a secondary accent, not a second hero colour.

### Developer colour tokens

| Token | Value |
|---|---|
| `brand.primary` | `#18A6C9` |
| `brand.primaryStrong` | `#0B7E99` |
| `brand.deep` | `#123E52` |
| `brand.tint` | `#DDF4F8` |
| `brand.sand` | `#E8D8C3` |
| `surface.background` | `#FAF8F4` |
| `surface.card` | `#FFFFFF` |
| `text.primary` | `#19282E` |
| `text.secondary` | `#66777D` |
| `border.default` | `#E5EBED` |
| `state.success` | `#328267` |
| `state.warning` | `#C98935` |
| `state.error` | `#C65353` |

### Accessibility reference (WCAG 2.1 contrast ratios)

Use Yana Blue mainly as a brand and accent colour. For small white text on buttons, use **Yana Blue Deep** or **Deep Tide**.

| Pairing | Ratio | Result |
|---|---|---|
| Ink on Warm Ivory | 14.30:1 | AAA, body text |
| Ink on White | 15.17:1 | AAA, body text |
| White on Deep Tide | 11.43:1 | AAA, body text |
| Deep Tide on Warm Ivory | 10.78:1 | AAA, body text |
| Deep Tide on Soft Blue | 10.00:1 | AAA, body text |
| Ink on Yana Sand | 10.87:1 | AAA, body text |
| White on Yana Blue Deep | 4.71:1 | AA, body text and buttons |
| Slate on White | 4.67:1 | AA, body text |
| White on `state.success` | 4.64:1 | AA, body text |
| Yana Blue Deep on Warm Ivory | 4.44:1 | AA large text / UI only. On white cards it rises to 4.71:1 |
| White on `state.error` | 4.41:1 | AA large text / UI only |
| Slate on Warm Ivory | 4.40:1 | AA large text / UI only. Prefer Slate on white cards for small text |
| White on Yana Blue | 2.86:1 | Decorative or large display only, never small text |
| Yana Blue on Warm Ivory | 2.70:1 | Icons, progress and decoration only |
| White on `state.warning` | 2.95:1 | Avoid. Use Ink text on warning fills |

---

## 3. UI principles

| Principle | In practice |
|---|---|
| **Calm by default** | Generous white space, strong photography, restrained promotional density. |
| **Progress feels good** | Wallet states celebrate momentum without gamifying people's finances. |
| **Luxury is in the edit** | Fewer, better options. Avoid visual noise and false urgency. |
| **Human language** | Plain, warm copy. No banking jargon unless legally required. |

**The wallet rule:** the wallet should feel motivating, not like internet banking. Progress, destination imagery and trip milestones should carry as much visual weight as balances.

**Merchandising rule:** destination-based and retargeted promotions should feel editorial and relevant. Advertising can exist inside Yana, but it should never make the interface feel like a discount marketplace.

---

## 4. Typography

*Carried over from the earlier YCHP guidelines; to be confirmed with the final design system.*

| Role | Style direction | Example pairing |
|---|---|---|
| **Display / headings** | Elegant, high-contrast serif for hero moments, property names and collection titles. | *Playfair Display*, *Canela* or *Cormorant* |
| **Body / UI** | Clean humanist sans, legible at small sizes on mobile for prices, filters, forms and dashboards. | *Inter*, *Söhne* or *Avenir Next* |
| **Numerals / prices** | Tabular figures from the body typeface, medium weight, Ink or Deep Tide. | Inter (tabular lining figures) |

**Rule of thumb:** if it's a decision point (a price, a date, a button label) it's set in the sans. If it's setting a mood (a hero headline, a curated collection title) it can use the serif.

---

## 5. Logo

### Yana mark

A dedicated Yana logo has not been supplied yet. Until it is, set **Yana** as a wordmark in Deep Tide or Ink, with the endorsement line *by Your Curated Holiday Planner* beneath it in Slate.

### YCHP parent mark

![YCHP logo](../../assets/brand/logo.jpg)

The YCHP crest (a Y · C · H monogram with a crown and a small aircraft) is the parent company mark. Its gold and ivory colours belong to the crest artwork only and are not part of the Yana interface palette.

- **Clear space:** keep a margin around the crest equal to the height of the crown on all sides.
- **Minimum size:** 120px wide on screen, or 25mm in print, for the full lock-up. Below that, use the crest alone.
- **Backgrounds:** use the crest on Warm Ivory or white. On Deep Tide, use a reversed ivory/white version. Never place it on a busy photograph without a solid or scrim behind it.
- **Don't** recolour, stretch, skew or add effects to the crest, or crowd it with badges and promotional stickers.

---

## 6. Voice and tone

- **Plain over clever.** Say what something does in the fewest natural words. No travel-industry or banking jargon.
- **Encouraging, never patronising.** The audience is capable; they simply haven't booked *this kind* of trip before.
- **Show the path.** Make the next step obvious: "Start saving", "See your curated stays", "3 payments left".
- **Calm, not urgent.** No countdown timers or "only 2 rooms left" pressure.
- **Universal, not themed.** Avoid clichés about any single country or about "Africa".
- **Written for translation.** English and French from day one, so avoid idiom-heavy phrasing. Prices show in local currency, with USD and ZAR required.

---

## 7. Applying the brand across the product

| Surface | Notes |
|---|---|
| **Marketing site and onboarding** | Fullest expression: Warm Ivory canvas, serif headlines, Yana Blue highlights, aspirational but approachable photography of real people and real trips. |
| **Search and booking** | Brand recedes in favour of clarity: Ink on Warm Ivory and white cards, Yana Blue Deep for primary actions, generous space so results never feel like a dense list. |
| **Wallet and Group Saving** | The emotional core. Deep Tide for trust moments, Yana Blue for progress bars and milestones, destination imagery given as much weight as balances. |
| **Partner dashboard and admin** | Utility first: Ink and Slate on white cards, Mist borders, state colours for status, blue used sparingly. |
| **Retargeting and destination ads** | Editorial, not promotional. One destination or deal per creative. |
