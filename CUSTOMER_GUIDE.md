# NovaCart Shopify Theme — Customer Guide

## 1. Install the theme

1. In Shopify Admin, go to **Online Store → Themes**.
2. Select **Add theme → Upload zip file**.
3. Upload `NovaCart_Shopify_Theme_Upload_v1.6.7.zip`.
4. Keep it as an unpublished theme while you configure and preview it. Publish only after checking your store's products, navigation, cart, and checkout.

## 2. Customize pages with Online Store 2.0

The included storefront templates use Shopify JSON templates. In **Online Store → Themes → Customize**, choose a page type from the page selector. Add, remove, and reorder available sections in the template. Header and footer content is managed in its section groups. App blocks can be added to the header and footer when the installed app provides compatible theme app blocks.

The **Flexible rich text**, **Flexible image with text**, **Featured collection**, **Promo countdown**, and existing feature sections can be configured in the theme editor. For product- or collection-specific sections, add them to the matching page template.

## 3. Configure the store identity

- Open **Theme settings** to change the primary, secondary, and accent colors, favicon, and free-shipping threshold.
- Select the **Header** group to set a logo, navigation menu, announcement message, and its colors.
- Select the **Footer** group to set brand text, menus, contact information, payment text, and compatible app blocks.
- Add the correct policy, shipping, contact, and returns pages to your store menus before publishing.

## 4. Configure promotions

### Offer section and countdown

Open the home page in the theme editor and select **عروض وعد تنازلي**. Set the offer title and details, optional discount code, button text/link, colors, and countdown. Enter the end time in ISO format with a timezone, for example `2026-12-31T23:59:00+01:00`. Enable **Hide offer when it expires** if the complete offer section should disappear at the deadline.

Create and configure discount codes in Shopify Admin first. If an offer code is set and the section's button link is blank, the section uses Shopify's discount link and returns the shopper to the cart. Shopify controls discount eligibility and combinations.

### Promotional popup

Open **Theme settings → النافذة الترويجية**. Enable the popup, add its content/image/code/button, and choose a delay or desktop exit-intent trigger. On touch devices, exit-intent uses the configured delay. Set how long the popup stays dismissed after a visitor closes it. Popup dismissal is stored in that browser.

## 5. Cart and cash-on-delivery flow

- Set the free-shipping threshold in **Theme settings → الشحن المجاني**. Enter the amount in the store currency's smallest unit; for a two-decimal currency, `50000` means `500.00`.
- In the cart drawer, shoppers can increase/decrease quantities or remove lines. The item count, subtotal, and free-shipping progress update with the cart.
- On the cart page, shoppers can edit quantities, update the cart, and add an order note.
- The product page's existing COD form still collects required contact and delivery fields and hands the cart to Shopify checkout. The theme does not create COD orders outside Shopify checkout.

## 6. Mobile and loading behavior

Sections use responsive layouts for smaller screens. Shopify-hosted content images use responsive image variants; non-critical gallery/card images load lazily, and the theme JavaScript is deferred. Keep uploaded photos appropriately cropped and avoid unnecessarily large media. Actual storefront speed depends on image content, installed apps, Shopify configuration, and network conditions; no fixed performance score is promised.

## 7. Troubleshooting

- **A section doesn't appear:** Confirm you are editing the intended template and that its section content is not blank or disabled.
- **A discount is rejected:** Check that the code exists, is active, and applies to the selected products/cart under its Shopify rules.
- **The countdown looks wrong:** Check the ISO timestamp and timezone, and confirm the visitor device clock is correct.
- **A cart action fails:** Refresh the storefront and retry. Confirm the product/variant is available and test in a Shopify development store.
- **An app block is missing:** Confirm the app provides a compatible theme app block and add it from the relevant header/footer group.

For theme support, see `SUPPORT.md`. For store-specific policies and product questions, contact the merchant operating that Shopify store.


## Theme Customizer only (no coding)

All sections and settings work from **Online Store → Themes → Customize**:

- Add sections from the left panel (Categories, Featured collection, Marquee, Promo countdown, Shoppable reels, Image with text, Rich text…)
- Edit colors, currency display, free shipping, popup from **Theme settings**
- Product page options (COD form, trust badges, sticky bar) from the Product template section settings
- Collection filters and products-per-page from the Collection template section settings

The theme uses **pure Liquid + Vanilla JavaScript** only (no jQuery, React, or heavy third-party libraries).

