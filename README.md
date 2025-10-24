# Victoria Suarez – Seller Lead Funnel (EXIT Realty DKC)

Custom, mobile-friendly seller lead funnel for Victoria Suarez of EXIT Realty DKC, serving Bronx, Yonkers, and Westchester.

## Setup (GitHub Pages + Formspree)
1. Create a Formspree form → copy the endpoint (looks like `https://formspree.io/f/XXXXYYYY`).
2. In `index.html`, replace the form `action` with your endpoint.
3. Push files to GitHub → Settings → Pages → Build from branch → `main` (root).
4. (Optional) In Zapier: Trigger = Formspree submission → Action = Google Sheets “Create Spreadsheet Row”. Map all fields including UTM params.

## Files
- `index.html` – Landing page (UTM capture built-in)
- `thank-you.html` – Post-submit confirmation
- `privacy.html` – Privacy policy
- `assets/logo.png` – Agent/brokerage logo (if provided)
- `google_sheets_template.csv` – Column headers for Sheets logging
