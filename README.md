# Suraksha Sathi website

Static site for the Suraksha Sathi pilot. No build step, no trackers.

- `index.html` – page for mothers and families (Hindi by default, English toggle)
- `doctors/index.html` – page for doctors and hospitals (pilot places, compliance, revenue uplift, request form)
- `robots.txt` – blocks all crawlers while the pilot is under review (pages also carry `noindex, nofollow`)

## Before going public
- Fill the square-bracket placeholders: hospital phone number, privacy notice details, contact details, pilot place count.
- Connect the doctors' request form to Firebase (currently it shows a copy-and-send fallback).
- Self-host the Google Fonts for faster loading on weak connections.

## Deploy
Import this repo into Vercel (framework preset: Other, no build command, output directory: `.`).
