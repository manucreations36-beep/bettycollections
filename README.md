# Betty Collections Ecommerce MVP

A responsive, front-end-only ecommerce storefront inspired by the supplied sneaker-store reference.

## Run locally
Open `index.html` in a browser, or serve this folder with any static web server.

## Included
- Responsive desktop and mobile layouts
- Product search and category filtering
- Product cards including leather official shoes, sale banners and brand strip
- Five-slide hero carousel (official, casual and training shoes; arrows, dots, auto-rotation); phone hero mirrors the desktop layout
- Product view page (`index.html#/product/13`): image gallery with detail views, size picker, quantity, Add to cart, Order on WhatsApp, related products
- Cart lines are size-aware and the WhatsApp order message includes the chosen EU size
- Cart with quantity changes and estimated totals
- WhatsApp checkout that sends the cart summary to Betty Collections
- Mobile navigation and floating WhatsApp contact

## Important setup notes
- WhatsApp order number is configured in `index.html` as `254781287268` (Kenyan international format for 0781287268).
- Product names, sample prices, images and categories are demo content. Replace them with Betty Collections' actual catalog before publishing.
- Official-shoe photos live in `assets/` (keep this folder next to `index.html`). Sneaker photos are still loaded from Unsplash and need an internet connection.
- To add a product, add an entry to the `products` array in `index.html` (`img`, `pos` focal point, optional `gallery` detail views).
- This MVP has no backend, payment gateway, stock database, or admin panel. WhatsApp is used to confirm orders.
