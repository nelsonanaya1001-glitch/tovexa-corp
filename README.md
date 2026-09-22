# Tovexa One Corp — Landing Page

Single-page wholesale/sourcing landing page (same structure as Voltiva Wholesale and Elevat8 Sourcing):
nav → hero → product categories → about → fulfillment features → FAQ → contact form → footer.

Three looks to choose from — open `index.html` to compare:

| Folder | Look |
|---|---|
| `demo-1/` | **Midnight** — full dark navy, red accents (like Elevat8) |
| `demo-2/` | **Paper** — white page, navy serif headlines, red CTAs (like Voltiva) |
| `demo-3/` | **Banner** — angled navy→red hero band, light body |

## Editing
- Each `demo-N/index.html` is self-contained (no build step). Colors and fonts are in the `:root` block at the top.
- `_src/` holds the shared pieces the demos were built from (`body.html` content, `base.css` layout, `theme-N.css`). Once you pick a demo you can delete `_src/` and the other two folders.
- Placeholders to replace: phone `(305) 000-0000`, address `1234 NW Example Ave`, email `info@tovexaone.com`.
- The contact form currently just shows an alert — wire it to Formspree / your API when ready.
