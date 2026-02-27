# Akrama GameStore Demo (WooCommerce)

A demo WooCommerce store built in WordPress to showcase a clean storefront experience: homepage hero + CTA, featured products, category navigation, product pages, cart, and checkout.

## Live Demo
Local demo (LocalWP): `gamestore-demo.local`  
(Deployed demo can be provided on request.)

## Key Features
- WordPress pages built with the block editor (Homepage + Contact)
- WooCommerce shop with products, categories, and add-to-cart flow
- Featured products section (“Featured Games”)
- Basic on-page SEO (permalinks, titles/meta via Rank Math, image alt text)
- GA4 analytics tagging (Measurement ID installed and verified in page source)
- Backup + maintenance basics (UpdraftPlus)

## Proof
✅ GA4 tag installed (gtag present in page source)

✅ WooCommerce flow: Shop → Product → Cart → Checkout

✅ Backup created with UpdraftPlus


## Tech Stack
- WordPress + WooCommerce
- Astra theme
- Rank Math SEO
- Google Analytics 4 (GA4)
- UpdraftPlus (backups)

## Screenshots
See: `docs/screenshots/`
- Home, Shop, Product page, Cart, Checkout
- GA4 tag proof (gtag + Measurement ID)

## How to Run Locally (high level)
1. Create a local WordPress site (LocalWP)
2. Install: WooCommerce, Astra, Rank Math, UpdraftPlus
3. Import content (optional): `docs/wp-export.xml`
4. Configure products + categories
5. Add GA4 Measurement ID and verify via View Page Source

## Notes
This is a portfolio demo site. Orders are not fulfilled.
