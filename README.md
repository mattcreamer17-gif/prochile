# ProChile × Eduba · Booth Landing Page

Bespoke, single-page sales landing built for the ProChile booth conversation at eMerge Americas 2026 (booth 439, International Pavilion). Audience is Claudia Serrer (Trade Commissioner, Miami) and her trade-manager team. Visual language pulls from the live ProChile brand system: teal primary (#0091B1), white surfaces, light-blue feature blocks (#EBF4F9), thin rules, no gradients, no sheen. Copy is Spanish-primary with an English parity toggle (ES/EN in the top-right of the utility bar). The pitch body is the fit-analysis.md section 7 read of the 70-office network, delivered in the prospect's institutional voice. CTA is a thirty-minute call with Matt Creamer via Calendly (direct URL). No pricing, no revenue terms. Eduba is absent from the top of the page and appears only in the footer, per disclosure rules.

Intended URL path: `/for/prochile`

## Files

- `index.html`: single-page layout, ES/EN toggle via lightweight inline script.
- `styles.css`: ProChile-native tokens (teal #0091B1, Work Sans / Source Sans 3 stack that stands in for the "Chilena" heading font used on prochile.gob.cl).
- `logo.svg` / `logo.png`: official ProChile wordmark (SVG primary, PNG fallback).

## Notes

- Mobile tested at 375px. Hero stat band collapses to single column. CTA button is full-width on small screens.
- All external links (GitHub repo for ICM, arXiv for Ethics Engine, Calendly, eduba.io) open in a new tab with `rel="noopener"`.
- Ethics Engine one-sentence bio included per disclosure rules. NLP Logix credibility line ("in machine learning since 2011 and runs over 150 data scientists") included per disclosure rules. No KPMG reference on this page (not the strongest match for a government-agency audience; Correlation One / Pacific Life / Colgate-Palmolive carries the credibility).
- Voice scrubbed for em dashes, antithesis patterns, performed questions, and hype words.
