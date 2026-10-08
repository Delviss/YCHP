# Colour Palette

Blue is the signature: bright enough to feel like travel and possibility, grounded by a deeper ocean tone for trust and financial moments.

---

## Palette

| Swatch | Name | Hex | Primary use |
|---|---|---|---|
| <span class="swatch" style="background:#18A6C9"></span> | **Yana Blue** | `#18A6C9` | Hero brand colour, highlights, icons, progress |
| <span class="swatch" style="background:#0B7E99"></span> | **Yana Blue Deep** | `#0B7E99` | Primary actions where stronger contrast is needed |
| <span class="swatch" style="background:#123E52"></span> | **Deep Tide** | `#123E52` | Navigation, headings, wallet and trust moments |
| <span class="swatch" style="background:#DDF4F8"></span> | **Soft Blue** | `#DDF4F8` | Selected states, cards and gentle backgrounds |
| <span class="swatch" style="background:#E8D8C3"></span> | **Yana Sand** | `#E8D8C3` | Warm secondary accent |
| <span class="swatch" style="background:#FAF8F4"></span> | **Warm Ivory** | `#FAF8F4` | Primary app background |
| <span class="swatch" style="background:#19282E"></span> | **Ink** | `#19282E` | Primary text |
| <span class="swatch" style="background:#66777D"></span> | **Slate** | `#66777D` | Secondary text |
| <span class="swatch" style="background:#E5EBED"></span> | **Mist** | `#E5EBED` | Borders, dividers and disabled states |

---

## How the Palette Should Behave

- **Light interface first.** Warm Ivory and white dominate the canvas.
- **Blue punctuates, it doesn't flood.** Yana Blue creates recognition and optimism.
- **Deep Tide carries trust.** Headings, navigation and wallet moments.
- **Sand supports.** It is a secondary accent, not a second hero colour.

!!! tip "Colour balance"
    Aim for a light interface first. Let the blue punctuate the experience rather than flooding every surface.

---

## Developer Colour Tokens

| Token | Value |
|---|---|
| `brand.primary` | <span class="swatch" style="background:#18A6C9"></span> `#18A6C9` |
| `brand.primaryStrong` | <span class="swatch" style="background:#0B7E99"></span> `#0B7E99` |
| `brand.deep` | <span class="swatch" style="background:#123E52"></span> `#123E52` |
| `brand.tint` | <span class="swatch" style="background:#DDF4F8"></span> `#DDF4F8` |
| `brand.sand` | <span class="swatch" style="background:#E8D8C3"></span> `#E8D8C3` |
| `surface.background` | <span class="swatch" style="background:#FAF8F4"></span> `#FAF8F4` |
| `surface.card` | <span class="swatch" style="background:#FFFFFF"></span> `#FFFFFF` |
| `text.primary` | <span class="swatch" style="background:#19282E"></span> `#19282E` |
| `text.secondary` | <span class="swatch" style="background:#66777D"></span> `#66777D` |
| `border.default` | <span class="swatch" style="background:#E5EBED"></span> `#E5EBED` |
| `state.success` | <span class="swatch" style="background:#328267"></span> `#328267` |
| `state.warning` | <span class="swatch" style="background:#C98935"></span> `#C98935` |
| `state.error` | <span class="swatch" style="background:#C65353"></span> `#C65353` |

---

## Accessibility Reference (WCAG 2.1 Contrast Ratios)

!!! warning "Small white text needs the deeper blues"
    Use Yana Blue mainly as a brand and accent colour. For small white text on buttons, use **Yana Blue Deep** or **Deep Tide** to preserve contrast.

| Pairing | Ratio | Result |
|---|---|---|
| **Ink on Warm Ivory** | 14.30:1 | AAA, body text |
| **Ink on White** | 15.17:1 | AAA, body text |
| **White on Deep Tide** | 11.43:1 | AAA, body text |
| **Deep Tide on Warm Ivory** | 10.78:1 | AAA, body text |
| **Deep Tide on Soft Blue** | 10.00:1 | AAA, body text |
| **Ink on Yana Sand** | 10.87:1 | AAA, body text |
| **White on Yana Blue Deep** | 4.71:1 | AA, body text and buttons |
| **Slate on White** | 4.67:1 | AA, body text |
| **White on `state.success`** | 4.64:1 | AA, body text |
| **Yana Blue Deep on Warm Ivory** | 4.44:1 | AA large text / UI only (4.71:1 on white cards) |
| **White on `state.error`** | 4.41:1 | AA large text / UI only |
| **Slate on Warm Ivory** | 4.40:1 | AA large text / UI only; prefer Slate on white cards for small text |
| **White on Yana Blue** | 2.86:1 | Decorative or large display only |
| **Yana Blue on Warm Ivory** | 2.70:1 | Icons, progress and decoration only |
| **White on `state.warning`** | 2.95:1 | Avoid; use Ink text on warning fills |
