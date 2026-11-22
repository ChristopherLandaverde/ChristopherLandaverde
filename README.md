<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/brand/header-dark.png">
  <img alt="" src=".github/brand/header-light.png" width="100%">
</picture>

### Christopher Landaverde

Marketing Operations & MarTech engineer. I make marketing, CRM, and analytics systems produce data teams can trust: tracking, customer data, CRM, automation, measurement, traced end to end.

Founder of [Focosys](https://focosys.io/), an independent practice.

`Tools / ordered along the signal path`

**□ Tracking and consent: where the signal is captured**

- [adlinter](https://github.com/ChristopherLandaverde/adlinter): 82 checks against a GTM container export and Google Ads conversions. Privacy-first, runs entirely in the browser
- [ConsentFlow-Debugger](https://github.com/ChristopherLandaverde/ConsentFlow-Debugger): Chrome extension for debugging GTM Consent Mode in real time
- [trimtale](https://github.com/ChristopherLandaverde/trimtale): agentic GA4 setup. An in-page assistant sets up events through GTM, proves each one fires with real browser requests, and publishes only after your approval

**↓ CRM handoff: where attribution is overwritten**

- [leadtrace](https://github.com/ChristopherLandaverde/leadtrace): sends one synthetic lead through the landing page and form, then checks 6 attribution fields in HubSpot. Catches redirects that drop `gclid` and hidden inputs that never fill

**✓ Measurement: where the number is reported**

- [pipetrace](https://github.com/ChristopherLandaverde/pipetrace): dbt package on BigQuery that traces pipeline revenue to the GA4 session behind it. 14 models, 54 of 54 dbt nodes pass in CI on synthetic data, credit sums to 1 per deal
- [open-source-revenue-attribution](https://github.com/ChristopherLandaverde/open-source-revenue-attribution): the same job as a self-hosted app
- [rabbit](https://github.com/ChristopherLandaverde/rabbit): FastAPI service for marketing attribution modeling (parked)

Field notes on how these failures happen ↗ [focosys.io](https://focosys.io/)

[focosys.io](https://focosys.io/) · christopher@focosys.io
