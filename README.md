# Seer · six interfaces on Electric Foundation

Entry for poidh bounty 38, "Design Seer's six interfaces", by [@safwaan_uddin](https://x.com/safwaan_uddin).

| Interface | Page |
|---|---|
| Seer homepage | `index.html` |
| Seer app (explorer) | `app.html` |
| Deep | `deep.html` |
| Futarchy | `futarchy.html` |
| Opportunity Markets | `opportunity.html` |
| Risk Pricing | `risk.html` |

All six share one shell and header and run in dark and light mode. Every app fetches Seer's public APIs live on page load (markets-search, get-market, the Optimism Uniswap subgraph for Deep, risk.seer.pm, futarchy candles) and falls back to a 23 Oct 2026 07:56 UTC snapshot if they can't be reached; each page's badge says which. Trade buttons open a demo ticket; nothing is sent onchain.