# orviak-site

Source for [orviak.com](https://orviak.com), the website of Orviak, an AI and software studio building mobile apps, web platforms and AI systems.

## What's here

| File | Purpose |
| --- | --- |
| `index.html` | The whole site: one self-contained page (HTML, CSS and a little JavaScript) |
| `404.html` | Page shown for unknown URLs |
| `CNAME` | Tells GitHub Pages to serve the site at `orviak.com` |
| `robots.txt`, `sitemap.xml` | Search engine hints |
| `.nojekyll` | Serves the files as they are, with no Jekyll build |

There is no build step and no dependencies. Fonts load from Google Fonts.

## Preview locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
```

Then visit <http://localhost:8080>.

## Deploy

The site is hosted on GitHub Pages from the `main` branch root. Every push to `main` goes live within a minute or two.

DNS for `orviak.com` (managed at Namecheap):

| Type | Host | Value |
| --- | --- | --- |
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `aftabkh4n.github.io` |

Mail records (MX, SPF) belong to the mailbox provider and must stay as they are.

## Contact

hello@orviak.com

## License

Copyright (c) 2026 Orviak. All rights reserved. See [LICENSE](LICENSE).
