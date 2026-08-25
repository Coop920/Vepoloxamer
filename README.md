# LifeRaft Biosciences / Vepoloxamer — Astro v22

This build applies the LifeRaft Biosciences Website Storyboard v22 content and seven-page architecture to the established Astro implementation.

## Public routes

- `/` — Home
- `/science/` — Science
- `/pipeline/` — Pipeline + Lead Program
- `/foundation/` — Clinical/Scientific Foundation + IP & Protection
- `/publications/` — Publications library with indication/material filters
- `/team/` — Team, Scientific Advisory Board, Board of Directors
- `/contact/` — Contact channels + Netlify form
- `/privacy/` — Privacy Policy
- `/thanks/` — Form confirmation

## v22 implementation notes

- Retains the established LifeRaft logo/header, mobile hamburger, footer, homepage molecule treatment, responsive styles, and GitHub Pages base path.
- Removes storyboard-only blue page header bars from the live pages.
- Removes `SECTION 0# —` prefixes from page eyebrow headings while preserving the descriptive eyebrow text.
- Preserves COPY NOTE and DESIGN NOTE annotations for development review.
- Places card icons and headings on the same row.
- Adds inline jump navigation to Science, Pipeline, Foundation, and Team.
- Preserves functional filtering on the Publications table.
- Contact form is Netlify-ready and includes Name, Company/Affiliation, Email, Phone Number, Role, Type of Inquiry, and Message.

## Development

```bash
npm install
npm run dev
```

The project is configured with `base: '/Vepoloxamer/'` for the current GitHub Pages deployment.
