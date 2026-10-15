# Biryani Flames

Static website (single `index.html` + `img/`). No build step.

## Deploy to Hostinger

**Option A — Git (recommended):** hPanel → Websites → Advanced → **Git** → add repository
`https://github.com/Mesumraza08-art/flames.git`, branch `main`, install path empty (deploys to `public_html`).
Optionally enable auto-deployment with the webhook URL in GitHub repo Settings → Webhooks.

**Option B — File Manager / FTP:** upload `index.html`, `.htaccess` and the `img/` folder into `public_html`.

`.htaccess` forces HTTPS, enables compression and caching.
