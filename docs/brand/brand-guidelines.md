# YCHP Brand Guidelines

**Your Curated Holiday Planner** — a travel booking platform that makes a great holiday feel reachable.

This guide defines the visual identity derived from the YCHP logo, and the tone of voice the platform should carry across web, mobile and marketing. It is the reference for anyone designing or writing anything that carries the YCHP name.

---

## 1. Brand essence

> YCHP turns "I could never afford that" into "I have been saving, and it is booked."

YCHP exists for a large, growing group of middle- and upper-class travellers — starting in Africa — who can afford to travel internationally but haven't yet, because travel *feels* out of reach: intimidating, cluttered, aimed at someone else. The brand's job is to make travel feel **curated, warm and achievable**, never sterile or exclusive.

Three words guide every design and copy decision:

| Word | What it means in practice |
|---|---|
| **Curated** | A considered shortlist, never an overwhelming grid. Quality over quantity everywhere — copy, imagery, layout. |
| **Warm** | Inviting and human, not cold luxury. The platform should feel like a knowledgeable friend, not a gatekeeper. |
| **Guided** | Every screen should help someone move from "someday" to "booked" — clear next steps, no dead ends. |

Reference points the brand should feel closer to: **Luxury Escapes** (calm, premium, edited). Reference points to actively avoid: **Agoda / Trip.com** (dense, promotional, overwhelming).

---

## 2. Colour palette

Colours are extracted directly from the YCHP logo (antique gold monogram and crest on an ivory ground) plus the deep navy used as the brand's supporting ink tone.

### Primary

| Swatch | Name | Hex | RGB | Use |
|---|---|---|---|---|
| 🟫 | **YCHP Gold** | `#B8804A` | 184, 128, 74 | Logo, icon accents, dividers, decorative moments. The signature brand colour — use with intention, not as a body-text colour. |
| ⬛ | **YCHP Navy** | `#14263D` | 20, 38, 61 | Primary text colour, headlines, the platform's "trust" colour. Doubles as the dark mode / footer background. |
| ⬜ | **YCHP Ivory** | `#F5EDE0` | 245, 237, 224 | Primary background. Warm, not stark white — this is what makes the brand feel welcoming rather than clinical. |

### Supporting tints & shades

| Swatch | Name | Hex | Use |
|---|---|---|---|
| 🟤 | Gold — Deep | `#8C5F35` | Body copy set in gold (links, small labels), hover/pressed states for gold buttons. Passes AA contrast on Ivory. |
| 🟡 | Gold — Light | `#C8975C` | Highlights on dark backgrounds, subtle gradients, illustration accents. |
| ⚪ | Warm White | `#FAF6EF` | Card surfaces sitting on top of Ivory backgrounds; keeps hierarchy without introducing pure white. |
| ◽ | Ink — 70% | `#3E4E60` | Secondary text, captions, placeholder text on light backgrounds. |
| ▫️ | Hairline | `#E4D9C6` | Borders, dividers, table lines on Ivory/Warm White surfaces. |

### Usage rules

- **Ivory is the default canvas.** Pure white (`#FFFFFF`) is reserved for photography crops and rare high-contrast UI needs — it should never be the dominant background, or the brand starts reading as a generic booking site.
- **Navy carries the words.** Body copy, navigation and buttons default to Navy on Ivory — this is what makes the platform feel calm and readable at booking-flow density.
- **Gold is a spotlight, not a wash.** Use it for the logo, section dividers, icon strokes, badges ("Verified", "Curated Pick"), and primary CTA fills — never as a large body-text colour or a full-bleed background behind long text.
- **Never** place plain Gold (`#B8804A`) text on Ivory — the contrast ratio (2.9:1) fails accessibility. Use Gold — Deep (`#8C5F35`) instead wherever gold text is needed (4.75:1, passes AA).

### Accessibility reference (WCAG contrast ratios)

| Pairing | Ratio | Passes |
|---|---|---|
| Navy on Ivory | 13.15:1 | AAA (body text) |
| Navy on White | 15.28:1 | AAA (body text) |
| Gold — Deep on Ivory | 4.75:1 | AA (body text) |
| Gold on Navy | 4.53:1 | AA (large text/UI only) |
| White on Navy | 15.28:1 | AAA (body text) |
| Gold on Ivory | 2.9:1 | Decorative / large display only |

---

## 3. Typography

The logo's crest lettering is a refined serif with high contrast strokes — that heritage, trustworthy feel should carry into headings. Body copy needs to stay highly legible across dense booking flows on small screens, so it switches to a clean humanist sans.

| Role | Style direction | Example web-safe pairing |
|---|---|---|
| **Display / Headings** | Elegant, high-contrast serif — the same register as the logotype. Used for hero moments, property names, section titles. | *Playfair Display*, *Canela*, or *Cormorant* |
| **Body / UI** | Warm, humanist sans-serif. Optimised for prices, filters, forms, dashboards — must stay legible at small sizes on mobile. | *Inter*, *Söhne*, or *Avenir Next* |
| **Numerals / Prices** | Tabular figures from the body typeface, medium weight, Navy — prices must never compete visually with Gold accents. | Inter (tabular lining figures) |

**Rule of thumb:** if it's a decision point (a price, a date, a button label) it's set in the sans. If it's setting a mood (a hero headline, a curated collection title) it can use the serif.

---

## 4. Logo

![YCHP logo](../../assets/brand/logo.jpg)

The mark is a monogram of **Y · C · H** set inside a crest, topped with a crown and finished with a small aircraft silhouette — crown for aspiration, aircraft for travel, monogram for the personal, curated feel. Below it, the wordmark **YOUR CURATED HOLIDAY PLANNER** with the **HOLIDAY PLANNER** tag set in tracked-out small caps.

### Usage

- **Clear space:** keep a margin around the mark equal to the height of the crown on all sides — never let UI chrome, photography or text touch the crest.
- **Minimum size:** the full lock-up (crest + wordmark) should not run smaller than 120px wide on screen, or 25mm in print. Below that, use the crest mark alone.
- **Backgrounds:** the full-colour gold-on-ivory lock-up is the default. On dark (Navy) surfaces, use a reversed version: ivory/white crest and wordmark. Never place the gold mark on a busy photograph without a solid or scrim behind it.
- **Don't:**
  - Don't recolour the crest outside the Gold/Navy/Ivory system.
  - Don't stretch, skew, or add drop shadows/outer glows beyond what's in the source mark.
  - Don't set the wordmark in a different typeface than the source lock-up.
  - Don't crowd the mark with competing badges, ribbons or promotional stickers.

---

## 5. Voice & tone

The Product Vision document itself is written in plain, warm, jargon-free language — that's deliberate, and the product's voice should match:

- **Plain over clever.** Say what something does in the fewest natural words. No travel-industry jargon, no forced excitement.
- **Encouraging, never patronising.** The audience is confident and capable — they simply haven't booked *this kind* of trip before. Copy should build confidence, not oversimplify.
- **Show the path, not just the destination.** Because the core emotional job is turning "someday" into "booked," copy should always make the next step obvious — "Start saving," "See your curated stays," "3 payments left."
- **Calm, not urgent.** Avoid countdown-timer, "only 2 rooms left" pressure tactics that feel like the cluttered sites YCHP is deliberately not.
- **Two launch languages:** English and French, with local currency display (South African Rand and US Dollar required at minimum) — copy should be written for straightforward, accurate translation, avoiding idiom-heavy phrasing.

---

## 6. Applying the brand across the product

| Surface | Notes |
|---|---|
| **Marketing site & app onboarding** | Full expression of the brand — Ivory canvas, serif headlines, gold crest, aspirational but approachable photography (real people, real trips — not stock luxury clichés). |
| **Search & booking flow** | Brand recedes in favour of clarity — Navy text on Ivory/Warm White, Gold reserved for CTAs and "Curated Pick" badges, generous white(ivory)space so results never feel like a dense list. |
| **Wallet / Group Savings ("Stokvel")** | Warmest expression of the brand — this is the emotional core of the product. Progress bars, contribution avatars and milestones can use Gold generously here to celebrate progress. |
| **Property owner dashboard & admin** | Utility-first — Navy/Ink text on Warm White cards, Gold used sparingly for status and verification badges only. |
| **Retargeting / destination ads** | Keep the calm, curated feel even in performance marketing — avoid cluttered ad templates; let one destination or deal breathe per creative. |
