# Seller Profit Calculator (TH)

Free Thai-language fee & profit calculator for Shopee, Lazada and TikTok Shop, plus the pre-order section for the Thai Seller Profit Kit (Google Sheets).

- Static site, no backend, no cookies. Hosted on GitHub Pages from `main` root.
- Rates live in the `PLATFORMS` array in `index.html` (source: FlowAccount, Aug 2026). Update them when platforms change fees.
- `CHECKOUT_URL` in `index.html`: put the public product link of the checkout platform. The buy button stays disabled while it is empty. Never put secret keys in this repo.
- `_headers` is only used if the site is moved to Cloudflare Pages.
