# Hardan & Vale — landing page (static site)

A static site, no build step. Upload the contents of this folder as they are.

## Files
- `index.html` — the landing page (styles and scripts inline)
- `*.jpg` — photos (kept next to index.html, no subfolders)
- `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `site.webmanifest` — icons
- `404.html` — "page not found" page

## Deploy (pick one)
- **Netlify Drop:** open app.netlify.com/drop and drag this folder onto the page.
- **Vercel:** `npx vercel` inside this folder (framework: Other, no build command, output directory `.`).
- **GitHub Pages:** push the folder to a repo → Settings → Pages → Deploy from branch → `/ (root)`.
- **Any hosting / cPanel:** upload everything into `public_html` (or the site root).

## Before going live for real
- The page has `<meta name="robots" content="noindex, nofollow">` so the concept is not indexed by Google. Remove that line when the site goes public.
- Replace sample content with real data: client logos, testimonials, founder name and photo, the email address, and the stock photos.
- Booking and contact forms are UI demos and do not send data anywhere. Connect a real tool (e.g. Cal.com / Calendly for the calendar, a form service or CRM for the contact form).
- Fonts load from Google Fonts.
