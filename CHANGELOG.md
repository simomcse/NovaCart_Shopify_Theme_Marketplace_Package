# Changelog

## 1.6.7
- Always-visible currency switcher with USD as default display currency (client-side conversion when Shopify Markets multi-currency is not enabled).
- Currency rates configurable in Theme settings; MAD no longer forced in theme strings.
- Color schemes confirmed in Theme settings (Classic, Dark, Emerald, Rose, Royal) with stronger surface overrides.

- Added complete Spanish storefront locale (`es.json`) with full theme string coverage.

- Added customer registration and login pages with email signup, Google/Apple/Microsoft buttons UI, phone field, and verification notices (email/SMS).
- Added register shortcut in the header and shopify-account component support.

- Upgraded collection product filtering: sidebar filters, price range, active filter chips, mobile filter drawer, and auto-apply on desktop.

- Added predictive product search overlay in the header with live suggestions, prices, and category badges.
- Improved the search results page to focus on products with product cards and type filters.

- Added a Categories section (Food, Clothes, Technologies, Home, Gaming…) with customizable cards linking to collections.
- Display product type/category badge on product cards and product pages.

- Added 5 elegant color schemes in Theme settings: Classic Blue, Dark Mode, Emerald Luxury, Rose Luxe, and Royal Purple (with soft glow accents).
- Improved language switcher with country flags and refined currency selector styling.
- Removed hard-coded Moroccan Dirham references; storefront money display follows the store currency (recommended: USD).
- Added language switcher and currency selector in the header (and mobile menu) using Shopify localization forms.
- Updated free-shipping threshold default and announcement copy to USD-oriented examples ($50).
- Updated locale strings (ar / en / fr) for language & currency labels.


- Updated theme version metadata to 1.6.7 and refreshed theme settings schema labels to English for wider marketplace compatibility while preserving full Arabic, English, and French storefront locales.
- Refined header section structure, navigation, and mobile menu handling for improved RTL/LTR behavior.
- Simplified and optimized the main theme layout (theme.liquid) for cleaner asset loading and direction support.
- Updated multiple sections (featured collection, flexible content, promo countdown, marquee, main-page) and templates with layout and editor improvements.
- Synchronized locale files (ar, en, fr) with the latest translation keys and strings.

## 1.6.0
- Expanded Online Store 2.0 customization with flexible rich-text and image-with-text sections and app block support in header/footer groups.
- Improved mobile layouts for flexible content, promotion, and cart page sections.
- Added Shopify responsive image variants, sizing hints, and lazy loading for non-critical content images; kept the main product image eager/high priority and deferred theme JavaScript.
- Added an English customer guide and marketplace support policy with a two-business-day acknowledgement target.
- Preserved the existing promotion, cart, wishlist/compare, quick-view, product variant, and COD flows.

## 1.5.0
- Added an editable offer section with discount-code link/copy support and an optional localized countdown.
- Added an optional global promotional popup with timed or exit-intent display and configurable dismissal frequency.
- Added asynchronous cart drawer quantity and removal controls, live cart count/subtotal, and updated free-shipping progress.
- Added cart-page quantity editing, order notes, and free-shipping progress.

## 1.4.1
- Fixed product variant option selection and localized quick-view controls.

## 1.4.0
- Added quick view, sticky purchase bar, and product-image viewer.

## 1.3.0
- Added nested navigation, wishlist and comparison controls, collection filters, sorting, and responsive product cards.
