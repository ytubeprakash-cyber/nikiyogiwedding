# Yogesh & Nikita — Wedding Website & Invitation Studio

One file (`index.html`), no build step. 7 website designs + 7 invitation cards.

## Deploy to Vercel
- `npx vercel` inside this folder, or push to GitHub and import in Vercel (Framework preset: Other).

## Links to send guests (studio controls hidden)
Use the **Share** button inside any design, or build the link yourself:

- Website: `https://YOUR-SITE.vercel.app/?guest=1#/site/editorial`
- Invitation: `https://YOUR-SITE.vercel.app/?guest=1#/card/lotus_diya`

Website ids: editorial, rajwada, pinkcity, sheeshmahal, thar, thread, boarding
Card ids: lotus_diya, velvet_haveli, gold_foil, story_reel, emerald_gatefold, mehendi, diya

## Editing details
Open `index.html` and search for `CONFIG` (names, parents, date, RSVP date) and `EVENTS` (times, venues, dress codes).
Set `rsvpWhatsApp` to a number like `919829012345` so RSVPs arrive on that WhatsApp.

## Background music
The invitations and the Shubh Vivah site play an original instrumental generated live in the browser (free, nothing to download).
To use a recording instead, put a royalty-free MP3 named `music.mp3` in this folder next to index.html and redeploy — it's picked up automatically.
