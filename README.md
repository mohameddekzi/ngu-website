# New Generation University — Website

Official website for New Generation University (NGU), Hargeisa, Somaliland.
**Learn Today. Lead Tomorrow.**

## Structure
- `index.html` — the full site. Each header menu item is its own page (hash routes: `#about`, `#admission`, `#academic`, `#partnerships`, `#facilities`, `#centres`, `#research`, `#apply`, `#contact`); sub-links jump to sections (e.g. `#about-history`).
- `assets/photos/` — photos (campus and staff from the NGU Facebook page; student photos from Unsplash).
- `assets/ngu-seal.png`, `assets/ngu-logo.jpg` — brand assets.

## Brand
- Colors from the NGU logo: maroon `#600911`, red `#D93C2B`, blue `#2B3B8F`, cream `#F2D6B1`.
- Font: Lexend (Google Fonts).

## To update before launch
- Contact details (phone, email, address, office hours).
- Leadership profiles, admission requirements, fees, academic calendar, publications.
- Replace Unsplash photos with NGU's own photos in `assets/photos/` (keep the same file names).
- Connect the application and contact forms to a backend (they are UI-only).

## Deploy
Static site, no build step. Deployed on Vercel.
