# NRL Breakeven Lab

Standalone source project for the NRL Fantasy and NRL SuperCoach breakeven research tool.

The app uses public, unauthenticated official data feeds only. Official paid Coach and SuperCoach Plus breakeven fields are not requested or redistributed. Values shown in the UI are labelled as estimated BE until an exact licensed source is available.

## Files

- `index.html`, `app.js`, `styles.css` - browser app
- `netlify/functions/breakevens-data.mjs` - public-data fetch/cache endpoint
- `netlify.toml` - Netlify publish/functions config

## Main Site Mirror

The `brent-clark` site serves the same app at:

`public/tools/breakevens/`

For now, this repo is the standalone source and the `brent-clark` repo contains a mirrored deploy copy.
