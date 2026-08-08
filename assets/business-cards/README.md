# Blu-I-Tech — Business Cards

Double-sided cards for 4 team members, rebuilt on the **real** Blu-I-Tech brand
(refined "B" mark, Poppins wordmark with the "-I-" accent, brand palette, and the
"Technology. Built for business." tagline). The originals used an incorrect logo
(a "B" with a play-triangle) and a generic wordmark — replaced here.

## Layout
- **Front** (shared by all): reversed logo + tagline lockup, centred on the brand gradient.
- **Back** (per person): horizontal lockup, name, title, and contact details (email · website · location).

## People
| Person | Title | Email |
|--------|-------|-------|
| Vukile Dinga | Founder · Director · Managing Director | vukile@bluitech.co.za |
| Philane Msibi | Founder · Director · Chief Technology Officer | philane@bluitech.co.za |
| Nkosinathi Nkosi | Product Designer | nkosinathi@bluitech.co.za |
| Charles Machete | Founder · Director · Chief Digital Officer | charles@bluitech.co.za |

Company: **Blu-I-Tech (Pty) Ltd** · bluitech.co.za · South Africa

## Print specs
- **Trim size:** 90 × 50 mm (standard SA business card)
- **Bleed:** 3 mm all sides → artboard **96 × 56 mm**
- **Safe area:** 4 mm inside trim (all text sits inside it)
- **Colour:** RGB (convert to CMYK at the printer if required; the brand blues are chosen to reproduce well)
- No phone numbers were on the originals — add a `phone` line if wanted (icon already supported).

## Files
| Folder | Contents |
|--------|----------|
| `pdf/` | **Print-ready** 2-page PDFs (page 1 = front, page 2 = back) at 96×56 mm, 600 DPI. Send these to the printer. |
| `svg/` | Vector masters — `front.svg` + one `<name>-back.svg` each. Fully editable. |
| `png/` | 600 DPI raster exports (96×56 mm). |
| `preview.png` | This overview image. |

## Editing / regenerating
Text is outlined vector (Poppins SemiBold / Medium — SIL OFL), so there's no font
dependency. To change details, edit the `svg/` masters, or regenerate from the
brand assets in `../brand/`. Fonts and the build script are not committed here;
ask if you want the generator added.
