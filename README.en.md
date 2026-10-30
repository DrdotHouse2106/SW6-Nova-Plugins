# Nova – open-source plugins for Shopware 6

[![Buy me a coffee](https://img.shields.io/badge/☕_Buy_me_a_coffee-PayPal-0070ba?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/DrdotHouse)

*[Deutsche Version](README.md)*

**Nova** is a series of free plugins for Shopware 6.6 and 6.7, built while running several of my own shops on a single Shopware installation. All plugins are open source, free of charge and are installed and updated straight from GitHub with the **Nova Updater**.

---

## Why Nova exists

I run several online shops myself – mostly spare parts – and have used plenty of commercial plugins over the years. The same experience again and again: subscriptions for small things, features that almost fit, data running through third-party servers, and plugins that break for months after a Shopware update with no way to fix them yourself.

So I started building what I actually need: lean, privacy-friendly, no subscription and open, so anyone can review and adapt it. Programming is not my profession – the plugins were created with the help of AI (Claude by Anthropic): I bring the requirements from day-to-day shop operations, test everything in my own shops and decide what goes in.

**I am a big fan of open source.** My shop, my server and almost every tool I work with rely on free software that other people shared. With Nova I want to give something back: what helps me should help other shop owners too – free, open, to read, improve and build upon.

> I am not a professional developer; these plugins are a hobby next to my actual business. They run in my own shops in production, but come without warranty or support. Bug reports and ideas are always welcome – ideally as an issue in the respective repository.

---

## The plugins

| Plugin | Purpose | Repository |
|---|---|---|
| **Nova Updater** | Installs and updates Shopware plugins directly from GitHub releases – no plugin store, with checks, backup and automatic rollback. The base for all other Nova plugins. | [SW6-Nova-Updater](https://github.com/DrdotHouse2106/SW6-Nova-Updater) |
| **Nova Theme** | Fast, modular storefront theme with ready-made CSS classes for shopping experiences and configurable header, footer and newsletter per sales channel. | [SW6-Nova-Theme](https://github.com/DrdotHouse2106/SW6-Nova-Theme) |
| **Nova Search** | Large search layer with images, filters and sorting that learns from searches, clicks and purchases, understands typos and word parts, manages synonyms and redirects and can improve zero-result terms with AI – no external search service. | [SW6-Nova-Suche](https://github.com/DrdotHouse2106/SW6-Nova-Suche) |
| **Nova Legal Texts** | Maintain imprint, privacy policy, terms and withdrawal once and use them in all shops – with per-channel placeholders, blocks that follow the services in use, and time-controlled sections. | [SW6-Nova-Rechtstexte](https://github.com/DrdotHouse2106/SW6-Nova-Rechtstexte) |
| **Nova 2FA** | Two-factor login via authenticator app for the administration and optionally for customer accounts. | [SW6-Nova-2FA](https://github.com/DrdotHouse2106/SW6-Nova-2FA) |
| **Nova Upload** | Protected file uploads in the contact form and on products (logos, drawings, 3D files) plus a download area in the customer account. | [SW6-Nova-Upload](https://github.com/DrdotHouse2106/SW6-Nova-Upload) |
| **Nova Decimal** | Sell by metre, square metre etc. with decimal quantities; fixed-size panels priced per m². | [SW6-Nova-Dezimal](https://github.com/DrdotHouse2106/SW6-Nova-Dezimal) |
| **Nova Category Automation** | Assigns products to the matching categories via a code – without slow dynamic product groups. | [SW6-Nova-Kategorie-Automatik](https://github.com/DrdotHouse2106/SW6-Nova-Kategorie-Automatik) |
| **Nova Events** | Manage events and fairs in the admin, show them as an event list, let visitors suggest events – plus pick-up at events as a shipping method. | [SW6-Nova-Termine](https://github.com/DrdotHouse2106/SW6-Nova-Termine) |
| **Nova Captcha** | Invisible spam protection without Google: proof-of-work in the browser instead of image puzzles, no cookies, no external requests. | [SW6-Nova-Captcha](https://github.com/DrdotHouse2106/SW6-Nova-Captcha) |
| **Nova Tag Manager** | Load Google Tag Manager only after consent, with e-commerce events and enhanced conversions. | [SW6-Nova-Tag-Manager](https://github.com/DrdotHouse2106/SW6-Nova-Tag-Manager) |
| **Nova Delivery Dates** | Fixed monthly shipping dates with order cut-off per supplier – shown from the product page to the e-mail. | [SW6-Nova-Lieferzeiten](https://github.com/DrdotHouse2106/SW6-Nova-Lieferzeiten) |
| **Nova Shipping Costs** | Calculate shipping costs from your own carrier purchase tariffs: parcel building, letter/small parcel/DPD/DHL, bulky goods, peak and abroad – with freight via Cargoboard, delivery date in the checkout and margin control on the order. | [SW6-Nova-Versandkosten](https://github.com/DrdotHouse2106/SW6-Nova-Versandkosten) |
| **Nova Vehicle Switcher** | Horizontal vehicle quick selector in the header for shops with vehicle-specific ranges. | [SW6-Nova-Fahrzeugauswahl](https://github.com/DrdotHouse2106/SW6-Nova-Fahrzeugauswahl) |

All plugins are **MIT licensed**. Every README is available in German and English.

### ERPNext

Connecting Shopware with [ERPNext](https://erpnext.com)? My fork of [ecommerce_integrations](https://github.com/DrdotHouse2106/ecommerce_integrations) adds a full Shopware 6 integration (products, orders, stock, prices) to the Frappe app.

---

## Installation

1. Install the **Nova Updater** once as a ZIP from the [latest release](https://github.com/DrdotHouse2106/SW6-Nova-Updater/releases/latest) via *Extensions → My extensions → Upload extension*.
2. All Nova plugins then appear in the updater's **plugin catalogue** and can be installed and updated with one click.
3. Alternatively upload each plugin's ZIP from its repository releases.

## Principles

- **No subscription, no licence keys, no telemetry.**
- **Privacy first:** external services only where unavoidable – switchable and documented for the privacy policy.
- **Lean and fast:** no heavy frameworks, no third-party scripts in the shop.
- **German first:** UI and docs in German, English in addition.
- **Open to everyone:** forks, pull requests and ideas are explicitly welcome.

---

## Support

If one of the plugins saves you work or a subscription, I'd be happy about a coffee – voluntary, no support entitlement, just a kind gesture:

[![Buy me a coffee](https://img.shields.io/badge/☕_Buy_me_a_coffee-PayPal-0070ba?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/DrdotHouse)

**For companies:** You use Nova in production and want to support its development? Invoices are possible – one-off or monthly. On request I'll list you here as a supporter with company name and link. Just get in touch via an issue.

Just as valuable: **a GitHub star ⭐**, a bug report or a small pull request.

Thank you! 💙
