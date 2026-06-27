# LocalFlow AI landing page

A static GitHub Pages-ready landing page for a productized AI automation service aimed at small businesses.

## What this sells

LocalFlow AI is positioned as an AI receptionist and follow-up engine for local service businesses. The offer is designed for a solo developer to sell, install, and support:

- Website chat and SMS intake
- Lead qualification and routing
- Quote and appointment follow-up
- Booking/CRM handoff
- Monthly performance reporting

## Local preview

Open `index.html` directly in a browser, or run a small local server:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deploy

This repository includes `.github/workflows/pages.yml`, which deploys the static site to GitHub Pages from the root of the repository whenever `main` is pushed.

After pushing, enable Pages for the repository if needed:

1. Open the GitHub repository.
2. Go to Settings → Pages.
3. Set Source to GitHub Actions.
4. Re-run the workflow if the first run started before Pages was enabled.

## Customize before outreach

- Replace `hello@localflow.ai` in `index.html` with your email or calendar link.
- Add your own domain and logo if you have them.
- Replace pricing with your actual offer.
- Add testimonials once you have beta users.
