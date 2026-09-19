# NewsWoo

![NewsWoo Logo](assets/logo.svg)

**WooCommerce, rebuilt for newsrooms.** A lean, purpose-built fork of WooCommerce tailored for publishers using [Newspack](https://newspack.com/) — stripped of retail bloat and optimized for digital subscriptions, paywall access, and reader donations.

## Why NewsWoo?

Standard WooCommerce ships with 800,000+ lines of code built for physical retail — shipping zones, inventory management, warehouse logistics, complex product variations. Newsrooms don't need any of that.

NewsWoo keeps what publishers need and removes what they don't:

| Feature | Standard WooCommerce | NewsWoo |
|---------|---------------------|---------|
| Primary Product | Physical or Digital Goods | Subscriptions, Paywall Access, Donations |
| Checkout Flow | Cart → Shipping → Billing → Payment | Direct Paywall → Minimal Billing/Payment |
| Database Weight | Heavy tables for stock, logs, shipping | Lightweight tables focused on user meta & access |
| Tax Engine | Shipping address destination | Billing address / Country residency only |

## What Gets Removed

- **Shipping & Fulfillment** — Shipping zones, classes, methods, calculators, address fields
- **Physical Inventory** — Stock management, backorders, low-stock alerts, product dimensions
- **Retail Checkout** — Cart page, "Add to Cart" fragments, complex coupon logic
- **Retail Product Types** — Grouped products, external/affiliate products, complex attribute variations
- **Tax Overhead** — Shipping-based tax calculations, geo-location for freight estimation

## What Gets Kept (and Enhanced)

- **Customer Accounts / My Account** — Reader dashboard for credit card updates, invoices, subscription management
- **Payment Gateways** — Stripe, PayPal, Apple Pay / Google Pay
- **Webhooks & REST API** — Mailchimp, ActiveCampaign, CRM integrations
- **Subscriptions** — Recurring access, tiered paywalls, trial periods
- **Memberships** — Content restriction, member-only areas
- **Name Your Price** — Flexible donation and "pay what you want" support

## Included Plugins (Analyzed)

| Plugin | Version | LOC | Purpose |
|--------|---------|-----|---------|
| WooCommerce | 11.1.1 | 800,537 | Core platform (to be trimmed) |
| WooCommerce Subscriptions | 9.2.0 | 155,157 | Recurring billing and access |
| WooCommerce Memberships | 1.30.0 | 146,424 | Content restriction and member areas |
| Name Your Price | 3.8.2 | 10,325 | Flexible/donation pricing |
| Subscriptions Gifting | 2.9.1 | 7,092 | Gift subscription support |

## Brand Assets

- [Logo (light)](assets/logo.svg)
- [Logo (dark)](assets/logo-dark.svg)
- [Icon](assets/icon.svg)
- [WooCommerce Icon Font](assets/fonts/WooCommerce.woff2)
- [Inter Font (WooCommerce's typeface)](assets/fonts/Inter-VariableFont_slnt,wght.woff2)

## Project Status

📋 See [ROADMAP.md](ROADMAP.md) for the full development plan.

## Development

See [dev/readme.md](dev/readme.md) for the development environment setup.

## License

GPL-2.0-or-later (same as WooCommerce)

## Links

- [Repository](https://github.com/Postdated/NewsWoo)
- [Newspack](https://newspack.com/)
- [WooCommerce](https://woocommerce.com/)

