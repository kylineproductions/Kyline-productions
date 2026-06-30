# Kyline Productions — Site

Static site built with Astro. Zero server, zero database, free hosting.

## Run locally
npm install
npm run dev

## Build for production
npm run build      # outputs to /dist

## Deploy (recommended: Cloudflare Pages or Netlify, both free)
1. Push this folder to a GitHub repo
2. Connect the repo in Cloudflare Pages (or Netlify)
3. Build command: npm run build
4. Output directory: dist
5. Point kylineproductions.com at the generated site (instructions provided by host)

## Before going live, replace these placeholders:
- src/pages/services.astro  -> Formspree form action URL (REPLACE_WITH_YOUR_FORM_ID)
- src/pages/contact.astro   -> same Formspree form action URL
- src/pages/music.astro     -> Spotify embed src (REPLACE_WITH_SPOTIFY_ID)
- src/pages/portfolio.astro -> real project history/photos
- src/pages/reviews.astro    -> set the `youtube` field on any entry to a video ID to embed it
- src/pages/reviews.astro -> add more entries (each can be Gear, Venue, Band, or Vlog, with optional YouTube embed) to the arrays at top of file as you write reviews

Formspree (free tier, no backend needed): https://formspree.io
