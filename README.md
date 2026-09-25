# Tovexa One Corp — Landing Page

Single-page wholesale/sourcing site. No build step — `index.html` plus the `images/` folder.

**Structure:** nav → hero (slideshow) → product categories → about → fulfillment → FAQ → contact → footer.

## Editing
- Colors and fonts: the `:root` block at the top of `index.html`.
- Contact form opens the visitor's email app with the inquiry pre-filled (same as Voltiva).
  Change the `INBOX` constant in the script at the bottom to reroute it.
- **Still a placeholder:** the email `info@tovexaone.com` (appears in the contact block, footer, and `INBOX`).
- Logo is a generated "T1" mark — replace when a real logo exists.

## Images
`images/` holds 12 optimized photos (640px, ~485KB total) from Unsplash, free to use.
3 each for Household Electronics, Beauty, Toys, and Logistics.

## Local preview
```
python3 -m http.server 8787
```

## Deploying
A Vercel project named `tovexa-one-corp` already exists under the Nelly Marketing team, but has no
deployment yet. To deploy, either drag this folder onto https://vercel.com/new, or:

```
brew install node
npm i -g vercel
vercel --prod
```
