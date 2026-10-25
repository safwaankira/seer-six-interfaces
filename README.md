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

All six share one shell and header, run in dark and light mode, and use real Seer data. The Seer app, Risk Pricing and Futarchy pages fetch Seer's public APIs live on page load, falling back to a 23 Oct 2026 07:56 UTC snapshot; Deep and Opportunity use that snapshot (their APIs don't allow browser access). Each page's badge says whether it is live or a snapshot. Trade buttons open a demo ticket; nothing is sent onchain.
