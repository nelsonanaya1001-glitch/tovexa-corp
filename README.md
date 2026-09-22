# Tovexa One Corp — Landing Page

Single-file landing page. No build step — open `index.html` in a browser.

**Structure:** nav → hero → product categories → about → fulfillment → FAQ → contact → footer.

## Editing
- All colors and fonts live in the `:root` block at the top of `index.html`.
- Placeholders still to replace: phone `(305) 000-0000`, address `1234 NW Example Ave`, email `info@tovexaone.com`.
- The contact form currently shows an alert on submit — needs wiring to a real handler.

## Local preview
```
python3 -m http.server 8787
```
