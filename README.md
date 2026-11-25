# Premium Store

A responsive storefront concept for browsing a curated collection of premium
everyday products. The site is built with semantic HTML and Tailwind CSS loaded
from its CDN.

## Store pages

- **Home** (`index.html`) — promotional hero, featured categories, and product
  highlights.
- **Products** (`pages/product.html`) — product catalog layout.
- **Categories** (`pages/categories.html`) — category browsing layout.

The repository also contains two separate static site concepts:

- `corparate site/` — Nova Forge corporate/agency pages.
- `hotel/` — Maison Élan hotel and booking pages.

## Run locally

No build step or package installation is required. From the project root, start
a local web server:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000). A local server keeps
page navigation and asset paths working as expected. An internet connection is
needed to load Tailwind CSS from its CDN.

## Project structure

```text
.
├── index.html                 # Premium Store home page
├── pages/
│   ├── product.html           # Product catalog
│   ├── categories.html        # Product categories
│   └── images/                # Store imagery
├── corparate site/            # Nova Forge site concept
└── hotel/                     # Maison Élan site concept and imagery
```

## Current scope

This is a front-end/static-site project. The search, cart, and account links are
visual placeholders; there is no product database, checkout, payment
processing, or user authentication backend.

## Publish with GitHub Pages

For a basic static preview, open the repository's **Settings → Pages**, choose
**Deploy from a branch**, select the `main` branch and `/ (root)` folder, then
save. The store home page is at the repository root.
