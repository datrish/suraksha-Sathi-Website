# Suraksha Sathi website

Static site, no build step, no trackers. Deployed on Vercel (framework preset: Other, output directory `.`).

- `index.html` – homepage for doctors and hospitals (English). Demo requests open a pre-filled email to info@surakshacall.com.
- `mothers/index.html` – page for mothers and families (Hindi by default, English toggle). Link to it directly from the consent slip, clinic card and first WhatsApp message.
- `/hospital-pilot-2090/` – old doctors' link, now redirects to `/` (set in `vercel.json`).
- `robots.txt` and the `X-Robots-Tag` header keep the whole site out of search engines during the pilot.

## Content rules
- Only describe features as live once they work. Anything else is marked "coming next".
- No invented results, statistics, certifications or pilot place counts.
- Never call it a reminder service: it is the clinic's care companion.

## Before sharing widely
- Set up the info@surakshacall.com mailbox (the site and form depend on it).
- Confirm the mothers' opt-out methods match what the app supports.
