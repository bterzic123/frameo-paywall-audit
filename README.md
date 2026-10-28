# Paywall Audit — Frameo

**Live:** https://bterzic123.github.io/frameo-paywall-audit/

Prepared for the Frameo team by Adapty. Four ranked ideas for Frameo's paywall, each backed by a number from
[State of Paywalls 2026](https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=frameo),
a scorecard of the paywall against the report, and a clickable rebuild of the paywall and the moment after close, in Frameo's own design.

## The ideas

| # | Idea | Report anchor | Potential outcome |
| :-- | :-- | :-- | :-- |
| 01 | Explain the 14 days before they start | Photo & Video: 54.6% of trials cancelled within 24h (table E); trial explainer (5.3) | ARPU +12–36%, observed in winning A/B tests |
| 02 | Give a second chance when they close | Only 4% of apps show a paywall after close; converts at 0.88× the main one (4.5) | ARPU +10–15%, based on Adapty data |
| 03 | Put your 4.9 stars on the paywall | Only 27% of top paywalls show social proof (3.1); social proof (5.3) | CR +10–30%, observed in winning A/B tests |
| 04 | Speak to the person who tapped Upgrade | Only 2% of top paywalls use what the app knows about the user (3.5) | No lift range in the report |

**Benchmark slice:** Photo & Video, all regions. App Store data, Oct 2025–Sep 2026.

## Grounding

Prices (16,99 € / 1,99 € for Frameo+, 59,99 € / 6,99 € for Premium), the 14-day trial and every feature line come from
Frameo's live paywall. 4.9 from 449K ratings and 30 million downloads come from Frameo's App Store listing. 1,42 € a month
is 16,99 € ÷ 12. No discount or new price is invented.

Impact ranges are observed lifts from winning A/B tests in State of Paywalls 2026 and Adapty's own data, not measured results for Frameo.

## Run locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000. Add `?open=proto` to land on the prototype.
