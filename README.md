# Holz-Heeger

Website for **Holz-Heeger**, a family firewood supplier (Brennholz / Kaminholz) in Rod an der Weil, 61276 Weilrod, Hochtaunus (Germany).

Single self-contained static page. All CSS, JS, and images are inlined in `index.html` (the hero and product photos are embedded as base64 data URIs), so it deploys as a pure static site with no build step.

## Deploy

No build required. Vercel serves `index.html` at the root automatically.

## To do before going live

- Replace placeholder **phone** and **e-mail** (search `PLATZHALTER` in `index.html`).
- Fill in the legally required **Impressum** (§ 5 DDG) in the footer.
- Wire the order form to a backend (Formspree / Resend) or convert it to a `mailto:` link.
