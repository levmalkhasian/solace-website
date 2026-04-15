# Solace Website

Marketing site for **Solace** — an iOS focus app that blocks distractions behind an NFC tag. Tap to start a session, tap to end it.

Live at **[get-solace.app](https://get-solace.app)**.

## Stack

Plain static site — HTML, CSS, and image assets. No build step, no dependencies. Hosted on GitHub Pages.

## Structure

```
.
├── index.html      # landing page
├── support.html    # support / contact
├── privacy.html    # privacy policy
├── styles.css      # shared styles
├── assets/         # icons and images
└── CNAME           # custom domain for GitHub Pages
```

## Local development

Open `index.html` in a browser, or serve the folder with any static server:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Pushes to `main` are published automatically by GitHub Pages. The custom domain is configured via the `CNAME` file and DNS records pointing to GitHub's Pages IPs.
