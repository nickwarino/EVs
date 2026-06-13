# How China Won the Electric Car — A Data Investigation

An interactive, single-file HTML feature making the data-backed case that China and BYD lead the global EV market and supply chain as of mid-2026 — built in the style of a long-form interactive newspaper feature.

**[→ View `china-ev-dominance.html`](china-ev-dominance.html)** (open in any browser — no build step, no dependencies)

## What's inside

Seven chapters, each driven by scroll-triggered data visualizations:

1. **The Crown Changes Hands** — BYD overtakes Tesla in global BEV sales (2.26M vs 1.64M in 2025)
2. **The Factory of the World, Electrified** — China builds ~75% of the world's EVs; exports doubled
3. **Owning Everything Beneath the Car** — China's grip on batteries, cathode/anode material, and rare earths
4. **The Money** — BYD vs Tesla FY2025 financials and the ~30% battery cost moat
5. **More Car per Dollar** — God's Eye ADAS on a $9,555 Seagull
6. **The Machine That Builds the Machine** — vertical integration from minerals to ships
7. **What Could Still Go Wrong** — the price war, Q1 2026 reversal, inventory, and tariffs

## How it was made

Researched via an automated deep-research pipeline: the question was decomposed into five angles, searched in parallel, and the load-bearing claims were submitted to adversarial verification (three fact-check agents per claim, two refutations required to kill a claim). **26 sources fetched, 127 claims extracted, 25 verified, 22 confirmed, 3 refuted and corrected.** Claims are badged in the report by confidence level, and a full methodology and source list appears in the footer.

Primary sources include the IEA *Global EV Outlook 2026* and *Critical Minerals Outlook 2025*, Tesla's SEC 8-K, BYD's FY2025 annual report, CPCA registration data, CSIS, and BloombergNEF.

## Interactive features

- **Animated bar-chart race** — global BEV sales by manufacturer, 2021→2025, with play/scrub controls (watch BYD seize #1)
- **Value-per-dollar comparator** — pick a segment and compare a BYD model against its Western rival on price, range, 0–62 and £-per-mile
- **The Tariff Map** — a clickable world map of how open each market is to Chinese EVs
- **Dark mode** — toggle in the top-right, remembers your choice
- Scroll-triggered charts, an animated financial ledger, and counters throughout

## Tech

Two files, zero dependencies: `china-ev-dominance.html` (the feature) and `index.html` (a redirect landing with social-preview tags). Vanilla JavaScript, CSS animations, `IntersectionObserver` scroll reveals, hand-built SVG/CSS charts, Open Graph/Twitter cards, and an inline SVG favicon. No frameworks, no build step, no external data — only Google Fonts and the four attributed Wikimedia photos are fetched.

---

*Compiled June 2026. Figures reflect full-year 2025, the latest complete data cycle, with verified Q1 2026 developments noted. This is an editorial data feature, not investment advice.*
