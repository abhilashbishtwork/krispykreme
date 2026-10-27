# Krispy Kreme India — website

Self-hosted static copy of the Krispy Kreme India brand site (previously hosted on LimeTray).
Every asset (CSS, JS, images, video, fonts) lives under `assets/`; no LimeTray or CDN requests.

- Pages: one folder per route (`menu/`, `store/`, `corporate/`, ...), each with `index.html`.
- `order-online/` opens the delivery-partner popup on the home page (`#order`).
- `stores/` redirects to `store/`.
- Corporate form posts to the Google Apps Script URL in each page (`scriptURL`).
