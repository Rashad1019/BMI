# The Brian Mickie Index — Investment Chart

An interactive, single-file HTML dashboard that lays out the full SpaceX IPO investment playbook: the existing core portfolio, the new space-economy picks being added, and the wider watchlist of possible plays — all in one place with prices, sentiment, and risk ratings.

## What's inside

**`index.html`** — the entire app, no build step required. Open it in any browser.

### Features

- **Strategy overview** — three cards summarizing the existing 40/40/20 core (SCHD / SPLG / BAI), the three new space picks being added (NASA / MARS / RDW), and the broader watchlist.
- **Interactive investment table** — all 12+ plays with ticker, type (ETF or stock), group, price, sentiment, and a color-coded risk badge (Safer / Moderate / Aggressive). Filter by group or risk level, sort by price or ticker, and click any row to expand the full thesis in plain language.
- **Allocation calculator** — enter any dollar amount, drag the space-sleeve slider (0–40%), and see real-time per-ticker dollar allocations with a visual bar breakdown. Defaults to a $150 initial investment with a 20% space sleeve.

## The Playbook

### Existing Core (40 / 40 / 20)

| Ticker | What it is | Allocation |
|--------|-----------|-----------|
| SCHD | Schwab US Dividend Equity ETF — steady income anchor | 40% |
| SPLG | SPDR Portfolio S&P 500 ETF — broad market growth | 40% |
| BAI | AI Innovation ETF — higher-risk tech kicker | 20% |

### New Space Picks (added ahead of SpaceX IPO)

| Ticker | What it is | Risk |
|--------|-----------|------|
| NASA | Tema Space Innovators ETF — diversified space basket with pre-IPO SpaceX exposure | Safer |
| MARS | Roundhill Space & Technology ETF — space-economy focused basket | Moderate |
| RDW | Redwire Corp — space infrastructure "sleeper" stock | Aggressive |

### Watchlist

RKLB · LUNR · PL · FLY · ASTS · UFO · ARKX · ROKT

## The thesis in one paragraph

The SpaceX IPO is expected to price at ~$1.5–1.7T on $18B in 2025 revenue — a rich multiple. Early investors face a short lockup and are likely to sell once they get liquidity. Rather than chasing the IPO directly, the strategy is to **buy the ecosystem, not the headline**: two diversified space ETFs (NASA, MARS) for broad exposure, one sleeper infrastructure stock (RDW) for upside, and a watchlist of sympathy names to monitor as the hype cycle plays out.

## Usage

Download or clone, then open `index.html` in any browser. No server, no dependencies, no build tools.

```bash
git clone https://github.com/Rashad1019/BMI.git
cd BMI
open index.html   # mac
start index.html  # windows
```

## Disclaimer

Prices are a snapshot from June 2026 research. This is for discussion and educational purposes only — not financial advice. Always verify current quotes and do your own due diligence before investing.
