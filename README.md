# Light Up Thadingyut — Campaign Prototype

Mobile-first festival mini-game plus a visual campaign editor.

## URLs after GitHub Pages is enabled
- Player game: /Thadinkyuktest/
- Campaign editor: /Thadinkyuktest/admin/

## Current prototype
- Touch/mouse detection
- Username + six quick stages
- Local score/leaderboard
- Reward tiers
- Campaign editor with live phone preview
- Editable branding, colors, timers, target count and reward thresholds
- JSON export
- Asset slots prepared for the production storage layer

## Important
This version uses browser localStorage. It is **not** the production database and is not suitable for a telecom-scale public launch or real prize fulfilment.

Production architecture should use CDN hosting, a protected server-side API, scalable database/object storage, rate limiting, server-side score validation, fraud controls, private PII tables, monitoring and load testing. The admin route must also be protected by authentication before production.
