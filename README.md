# Page to JSON — policy site

Public policy pages for the **Page to JSON** browser extension: the hosted Privacy Policy
and Terms of Use required for the Chrome Web Store listing.

## Pages
- `index.html` — landing, links to both docs
- `privacy/index.html` — Privacy Policy (`/privacy/`)
- `terms/index.html` — Terms of Use (`/terms/`)

Static HTML, no build step, no dependencies.

## Hosting
Serve this folder as the site root.

- **GitHub Pages:** push to a repo, enable Pages on the branch (root). URL: `https://<user>.github.io/<repo>/`.
- **Cloudflare Pages:** connect the repo, build command *none*, output directory `/` (or this folder).

After deploying, use the resulting URLs in the extension popup (`LINKS.privacy`, `LINKS.report`,
`LINKS.feedback`) and in the Chrome Web Store dashboard's privacy-policy field.

## License
© 2026 Gustavo Máximo Filho. All rights reserved.
Created by [Gustavo Máximo Filho](https://github.com/GoldenMaximo).
