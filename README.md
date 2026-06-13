# Cathova AI — Landing Page

Static waitlist landing page for [Cathova AI](https://cathova.ai).

## Deploy to Vercel

1. Push this repo to GitHub
2. [vercel.com/new](https://vercel.com/new) → Import this repository
3. Framework preset: **Other** (static HTML — no build step)
4. Add domain `cathova.ai` in Project → Settings → Domains

## Local preview

```bash
python3 -m http.server 8080
# Open http://localhost:8080
```

## Connect Tally waitlist

In `index.html`, set `TALLY_FORM_URL` at the bottom of the `<script>` block.
