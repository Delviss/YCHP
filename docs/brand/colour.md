# Colour Palette

Colours are extracted directly from the YCHP logo (antique gold monogram and crest on an ivory ground) plus the deep navy used as the brand's supporting ink tone.

---

## Primary

| Swatch | Name | Hex | RGB | Use |
|---|---|---|---|---|
| <span class="swatch" style="background:#B8804A"></span> | **YCHP Gold** | `#B8804A` | 184, 128, 74 | Logo, icon accents, dividers, decorative moments. The signature brand colour; use with intention, not as a body-text colour |
| <span class="swatch" style="background:#14263D"></span> | **YCHP Navy** | `#14263D` | 20, 38, 61 | Primary text colour, headlines, the platform's "trust" colour. Doubles as the dark mode / footer background |
| <span class="swatch" style="background:#F5EDE0"></span> | **YCHP Ivory** | `#F5EDE0` | 245, 237, 224 | Primary background. Warm, not stark white; this is what makes the brand feel welcoming rather than clinical |

---

## Supporting Tints & Shades

| Swatch | Name | Hex | Use |
|---|---|---|---|
| <span class="swatch" style="background:#8C5F35"></span> | **Gold — Deep** | `#8C5F35` | Body copy set in gold (links, small labels), hover/pressed states for gold buttons. Passes AA contrast on Ivory |
| <span class="swatch" style="background:#C8975C"></span> | **Gold — Light** | `#C8975C` | Highlights on dark backgrounds, subtle gradients, illustration accents |
| <span class="swatch" style="background:#FAF6EF"></span> | **Warm White** | `#FAF6EF` | Card surfaces sitting on top of Ivory backgrounds; keeps hierarchy without introducing pure white |
| <span class="swatch" style="background:#3E4E60"></span> | **Ink — 70%** | `#3E4E60` | Secondary text, captions, placeholder text on light backgrounds |
| <span class="swatch" style="background:#E4D9C6"></span> | **Hairline** | `#E4D9C6` | Borders, dividers, table lines on Ivory/Warm White surfaces |

---

## Usage Rules

- **Ivory is the default canvas.** Pure white (`#FFFFFF`) is reserved for photography crops and rare high-contrast UI needs. It should never be the dominant background, or the brand starts reading as a generic booking site.
- **Navy carries the words.** Body copy, navigation and buttons default to Navy on Ivory; this is what makes the platform feel calm and readable at booking-flow density.
- **Gold is a spotlight, not a wash.** Use it for the logo, section dividers, icon strokes, badges ("Verified", "Curated Pick"), and primary CTA fills; never as a large body-text colour or a full-bleed background behind long text.

!!! warning "Never put plain Gold text on Ivory"
    The contrast ratio of Gold (`#B8804A`) on Ivory is **2.9:1**, which fails accessibility. Use **Gold — Deep** (`#8C5F35`) instead wherever gold text is needed (**4.75:1**, passes AA).

---

## Accessibility Reference (WCAG Contrast Ratios)

| Pairing | Ratio | Passes |
|---|---|---|
| **Navy on Ivory** | 13.15:1 | AAA (body text) |
| **Navy on White** | 15.28:1 | AAA (body text) |
| **Gold — Deep on Ivory** | 4.75:1 | AA (body text) |
| **Gold on Navy** | 4.53:1 | AA (large text/UI only) |
| **White on Navy** | 15.28:1 | AAA (body text) |
| **Gold on Ivory** | 2.9:1 | Decorative / large display only |
