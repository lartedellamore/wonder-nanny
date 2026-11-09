# Wonder Nanny

Its own house. Plain HTML and CSS, no build step.

- `index.html` — English; `nl/index.html` — Dutch
- `app/` — the Planner (plan a day, on the day, handover card, log). Everything stays in the browser; nothing is uploaded. iPhone: Safari → Share → Add to Home Screen.
- `css/wonder.css` — white ground, pastel sky and leaf, sea-green ink, one gold fine line; never black. Fonts in `assets/fonts`.
- `assets/mark.svg` — the mark: a small sun behind a cloud

## Before you publish widely
Search the pages for `class="confirm"` — each gold-dashed phrase (prices, VAT, the quarterly charity report) is for Wietske to confirm. Remove the class once confirmed.

## Online
GitHub Pages serves `main` at https://lartedellamore.github.io/wonder-nanny/ (Dutch `/nl/`, Planner `/app/`).
For the own domain later: rename `CNAME.example` to `CNAME` and add the DNS records GitHub shows.
