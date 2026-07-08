# Vault22 Investor Leaderboard (prototype)

A premium, AI-first design prototype. Positioned as **"learn from proven investing styles, then build your own version"** — not copy trading.

## Run locally
```
cd Vault22-Leaderboard-Prototype
python3 -m http.server 8901
# open http://localhost:8901/
```
Runs over http (the app loads `data.js` + `app.js`). Opening `index.html` directly via `file://` also works in most browsers.

## Structure
- `index.html` — shell, design system (glassmorphism, Onest, Vault22 teal/navy tokens), overlays.
- `data.js` — mock/illustrative data: 20 TradFi + 20 Crypto "Inspired By" legend styles (with source notes), 12 anonymised community investors, 14 model strategies, the user's Investor DNA, gamification badges, educational metric definitions.
- `app.js` — router, SVG charts (donut / sparkline / performance / match ring), the six sections, investor profile, compare, the 3-step Build Similar flow, Tara AI, tooltips, search.

## Sections
For You · Community Investors · Market Legends · Investment Strategies · Compare · Following.

## Notes
All figures are illustrative for design purposes only. "Inspired By" model portfolios are educational and show similar exposure to well-known styles; they are **not** official portfolios of any named investor, and nothing here is financial advice. Community profiles are anonymised. A compliance review is required before any launch (performance, testimonials, endorsements and hypothetical performance are regulated areas).
