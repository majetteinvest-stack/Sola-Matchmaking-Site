# Sola Matchmaking — site files

Two prototype matchmaking sites. Each folder is a complete, self-contained website:
`index.html` holds the landing page, the six-step application, the member portal and the
matchmaker desk. No build step, no dependencies.

| Folder | Site | Audience |
|---|---|---|
| `missing-link/` | The Missing Link | Matured singles, 40+ |
| `curious-space/` | Curious Space | Young adults, 21–39 |

## Deployed with Netlify

Two Netlify sites point at this one repo:

- Build command: *(empty)*
- Publish directory: `missing-link` for one site, `curious-space` for the other

Pushing to `main` redeploys both automatically.

## Status: prototype

There is no backend. Everything a visitor types is stored in their own browser and never
reaches anyone. Applications submitted here go nowhere, the matchmaker passcode is visible
in the page source, and every member profile in the demo data is fictional.

Right for gathering feedback. Not right for real applicants until the form posts somewhere
real and the matchmaker desk sits behind an actual login.
