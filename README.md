# Your Cafe Name — Example Website Template

A static, single-page example website for a cafe, inspired by the layout and
warm colour palette of a British neighbourhood coffee shop. Every business
detail (name, address, phone number, product/bean names) has been replaced
with generic placeholders so this can be used as a starting template for any
cafe.

## What's included

- `index.html` — page markup (hero, story, visit/order, menu highlights,
  values, testimonials, newsletter, footer)
- `styles.css` — design system (colour tokens, type scale, layout, responsive
  breakpoints)
- `script.js` — mobile nav toggle, scroll-reveal animation, back-to-top
  button, demo newsletter form handler
- `vercel.json` / `package.json` — deployment config

No build step, no framework, no dependencies — just HTML/CSS/JS.

## Customize it

1. Replace "Your Cafe Name" throughout `index.html` with your real name.
2. Swap the placeholder address, phone, hours and email in the footer.
3. Replace the illustrated SVG hero/menu graphics with real photography if
   you have it (swap the `<svg>` blocks or `.menu-card-media` backgrounds
   for `<img>` tags / `background-image`).
4. Update the menu items, prices and testimonials with your own.
5. Wire the newsletter form and "Order Ahead" buttons up to your real
   ordering/email provider.

## Run it locally

Just open `index.html` in a browser, or serve it:

```bash
npx serve .
```

## Deploy to Vercel

**Option A — Vercel CLI**

```bash
npm i -g vercel
vercel
```

Follow the prompts (choose "Other" as the framework preset — this is a
static site, no build command needed).

**Option B — Git + Vercel dashboard**

1. Push this folder to a GitHub/GitLab/Bitbucket repo.
2. Go to [vercel.com/new](https://vercel.com/new) and import the repo.
3. Framework preset: **Other**. Build command: none. Output directory: `.`
4. Click **Deploy**.
