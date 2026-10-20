# Reica Gray — Stories Behind the Curtain

A responsive static author website for Reica Gray, themed around Victorian London's theatrical history. It uses warm ivory, charcoal blue, muted burgundy, sepia and antique gold, with an atmospheric London-at-dusk presentation.

## Files

- `index.html` — page structure and placeholder copy
- `styles.css` — colours, typography, responsive layout and styling
- `script.js` — mobile navigation and automatic copyright year
- `assets/` — folder reserved for local images or book cover artwork

## Preview locally

Open `index.html` in a browser. An internet connection is needed only for the optional Google Fonts; the London skyline and music-hall artwork are rendered in CSS, with no external photographs.

## Publish with GitHub Pages

1. Sign in to GitHub and create a **public** repository, for example `reica-gray-website`.
2. Upload `index.html`, `styles.css`, `script.js`, and the `assets` folder to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then save.
6. Wait for GitHub Pages to publish the site. The URL is usually `https://YOUR-USERNAME.github.io/reica-gray-website/`.

To use the root address `https://YOUR-USERNAME.github.io/`, name the repository exactly `YOUR-USERNAME.github.io`.

## Before publishing

- Replace the placeholder book title and book description when details are available.
- Replace the placeholder author biography.
- Change `hello@example.com` in `index.html` to the author's preferred email address.
- The newsletter/contact section is currently a simple email link, not a subscription form.
- Add properly licensed local artwork to `assets/` if photographs are needed later.
- The page includes Dan Leno as a genuine historical figure; check historical claims before publication.

## Customising the look

Edit the CSS variables at the top of `styles.css` to change the palette. The site uses charcoal blue, muted burgundy, warm ivory and antique gold. Google Fonts are loaded from an external service; fallback serif and sans-serif fonts are included.
