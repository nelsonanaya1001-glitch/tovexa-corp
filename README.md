# Tovexa One Corp — Landing Page

Single-file landing page. No build step — open `index.html` in a browser.

**Structure:** nav → hero → product categories → about → fulfillment → FAQ → contact → footer.

## Editing
- All colors and fonts live in the `:root` block at the top of `index.html`.
- Placeholders still to replace: phone `(305) 000-0000`, address `1234 NW Example Ave`, email `info@tovexaone.com`.
- The contact form opens the visitor's email app with the inquiry pre-filled (same approach as Voltiva). Change the `INBOX` constant in the script at the bottom to reroute it.

## Local preview
```
python3 -m http.server 8787
```
