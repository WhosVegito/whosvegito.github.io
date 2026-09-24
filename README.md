# whosvegito.github.io

Personal portfolio for **Aaranya Sharma** — Computer Science student (SRM, 2027), cybersecurity research, data systems and IoT.

Live at: https://whosvegito.github.io

## Stack

Single self-contained `index.html`. No build step, no dependencies.

- Fonts loaded from Google Fonts (Bricolage Grotesque, IBM Plex Sans, JetBrains Mono)
- All CSS and JS inline
- Light/dark theme support via `prefers-color-scheme`
- Generative canvas art on each project tile (no images/libraries)

## Structure

- Hero — name, pitch, live HalluciSTIX claim-check demo (illustrative scores, clearly labeled)
- Stats strip — headline numbers from the resume
- Selected work — 5 projects (HalluciSTIX, Secure LoRa IoT Link, Health Risk Clustering, IoT Pet Treat Dispenser, Inventory Reporting Pipeline)
- Experience — DRDO, FindYourKicks
- Toolkit — skills grouped by category
- Education & certifications
- Contact — copyable email, LinkedIn, GitHub

All content is sourced directly from the resume; nothing was added or embellished beyond what's listed there.

## Editing

Open `index.html` in any editor — everything (markup, styles, script) lives in that one file. No `npm install`, no build.

To preview locally, just open the file in a browser, or run:

```bash
python3 -m http.server 8000
```

and visit `http://localhost:8000`.

## Deploying

This repo is a GitHub Pages **user site**, so whatever is on `main` is served automatically at `https://whosvegito.github.io`. To publish a change:

```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

GitHub rebuilds and redeploys automatically (usually within a minute or two — check the **Actions** tab for build status).

## Contact

- Email: axrxnxa@gmail.com
- LinkedIn: https://www.linkedin.com/in/aaranya-sharma-65a343290
- GitHub: https://github.com/whosvegito
