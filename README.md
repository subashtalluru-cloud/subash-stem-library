# Subash STEM Library — Cloudflare Pages

## Identity
**III — Intuitive · Interactive · Intelligent**
**Subash STEM Library**

## Current structure
- `/` — main library homepage
- `/books/statistics/test-chapter/` — test chapter
- `/interactive/` — standalone Interactive Learning Lab
- `/assets/statistics-cover.png` — supplied portrait book cover
- `/assets/statistics-landscape.png` — supplied landscape visual

## Design principle
The website separates:
1. The book/narrative structure.
2. Standalone interactive HTML learning objects.

This means an interactive can be discovered and used independently of the book.

## Adding real interactive modules
Use:
`/interactive/<module-name>/index.html`

The module can then be linked from the lab catalogue.

## Cloudflare Pages deployment
Connect this folder/repository to Cloudflare Pages.

Build command: none
Build output directory: `/`

No server or database is required.

## Next development stages
- Add the complete statistics book.
- Add a chapter index and book navigation.
- Add a searchable interactive catalogue.
- Add Mathematics and Electronics sections.
- Add optional support/donation page.
- Add privacy, attribution and licensing pages.
- Add a custom domain.
