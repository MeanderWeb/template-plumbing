# Meander Web — Plumbing Template

Local business website template for plumbing businesses.
Built with vanilla HTML, CSS, and JavaScript.

## Usage
Replace all [BRACKET] tokens with client-specific content.
Deploy to Cloudflare Workers.

## Tokens to Replace
- [BUSINESS_NAME]
- [PHONE]
- [EMAIL]
- [ADDRESS], [CITY], [STATE], [ZIP]
- [TAGLINE]
- [YEAR_FOUNDED]
- [LICENSE_NUMBER]
- [PRICE_START]
- [BRAND_1], [BRAND_2]
- [BOOKING_URL] (remove button if N/A)
- [SERVICE_1_NAME] through [SERVICE_6_NAME]
- [SERVICE_1_DESC] through [SERVICE_6_DESC]
- [SERVICE_1_ICON] through [SERVICE_6_ICON]

## Google Maps
Update the iframe src to the client's address:
https://maps.google.com/maps?q=[ADDRESS]+[CITY]+[STATE]&output=embed

## Deployment
- Host: Cloudflare Workers
- Build command: (none)
- Output directory: /

## Built By
[Meander Web](https://meanderweb.com)
