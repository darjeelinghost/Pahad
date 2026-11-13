# PAHAD supporting website files (excluding index.html)

This package contains the supporting pages and shared assets for the existing PAHAD homepage. **It intentionally does not include `index.html`**. Keep your approved homepage in the repository root.

## Pages included

- `live-events.html` — Live Events
- `about.html` — About PAHAD
- `governance.html` — Governance and six-directorate framework
- `our-work.html` — Five areas of work
- `programmes.html` — Programme overview
- `knowledge.html` — Knowledge and Research
- `news.html` — News and Media
- `membership.html` — Membership information and official application link
- `contact.html` — Contact and official channels
- `dashboard.html` — Member dashboard landing page (no pretend login/backend)
- `get-involved.html` — Participation, volunteering and collaboration
- `vision-mission.html` — Vision, mission and principles
- `transparency.html` — Transparency and accountability
- `constitution.html` — Constitution and institutional documents
- `privacy-policy.html` — Website privacy notice placeholder requiring review against actual data practices
- `explore.html` — Explore PAHAD overview

## Shared files

- `assets/site.css` — Responsive design system, mobile navigation, cards and motion
- `assets/site.js` — Mobile navigation, reading progress, back-to-top, PWA install prompt and service-worker registration
- `assets/favicon.svg` — Browser icon
- `pahad-app-icon.svg` — Install icon
- `manifest.webmanifest` — PWA metadata
- `sw.js` — Service worker for same-origin static assets/pages

## Install into your existing repository

1. Download and extract this ZIP.
2. Upload all extracted files and folders into the same repository root where your existing lowercase `index.html` is located. Do not replace your homepage.
3. Keep the `assets` folder structure intact.
4. Ensure `index.html` references `manifest.webmanifest`, `pahad-app-icon.svg`, and `sw.js` (or your chosen service-worker filename).
5. Your homepage should link to `live-events.html`, `dashboard.html`, and the other page names above.
6. Deploy the repository through your existing Vercel or GitHub Pages setup. PWA installation requires HTTPS and a browser-supported install flow; users must approve installation.

## Important publishing checks

- The footer deliberately contains no website URL.
- Do not publish draft constitutions, unapproved policies, unverified event dates, or placeholder reports as final official documents.
- The dashboard is an informational landing page, not an authenticated member account system. Do not collect passwords or sensitive data on it.
- The privacy notice is a starting point; have it reviewed to match actual collection, use, retention and third-party services before collecting personal data.
- Verify all external form, social and WhatsApp links before launch.
- Google Fonts is loaded from Google Fonts when online; system fonts remain available as fallback.
