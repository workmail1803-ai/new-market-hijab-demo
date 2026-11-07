# SAYA — The New Market Edit

A mobile-first client presentation for a hijab boutique in Dhaka New Market. SAYA is editable sample branding. Prices, stock, descriptions, customer records and policies are illustrative. The nine unique client-supplied photos are embedded in `index.html`; one duplicate upload was omitted.

## One-file demo

Open `index.html` in a modern browser or use the GitHub Pages deployment. No build, dependencies, CDN, external fonts or image server are required. Images, CSS, JavaScript and seed data are all included in the file (about 4.4 MB).

## Client walkthrough

1. Browse, search or filter the collection, save favourites, and choose a size and quantity.
2. Add items to the bag and continue to checkout. Use **Fill sample details** and the discount code **SAYA10**. Choose Dhaka/outside Dhaka delivery, express delivery in Dhaka, or free shop collection. Cash on delivery, bKash and Nagad are demo preferences; no money is collected.
3. Use **Owner demo** to manage products, add a photo, edit prices and stock, archive/restore listings, or update shop details and delivery rates.
4. Open the new order in **Orders**. Confirm, pack, assign a sample courier and tracking reference, then mark it shipped or delivered. Customer tracking reflects the updates. Cancelling an unfinished order restores its stock.
5. Send a customer message, reply in **Owner demo → Inbox**, and return to the storefront to view the reply.
6. Export orders to CSV, download a receipt or data snapshot, or restore the original presentation in **Settings → Reset to the original demo**.

Sample tracking: **SAYA-1042**, phone **01700000042** (fictional demo record).

## Limits

All mutable data is saved in localStorage in the current browser. It is not shared with another device or visitor. The owner panel is intentionally open for presentation; it is not authentication. No real orders, payment transactions, external messages or courier bookings are submitted. Do not use the demo for live commerce or real customer data.

A production shop requires a secured backend, owner authentication, shared database, verified business information and policies, and payment, messaging and courier integrations.

## Validation

The mobile walkthrough was checked in the browser: checkout and discount calculation, stock decrement, owner fulfilment updates, customer tracking, two-way demo messages, product creation/editing/archive/restore and refresh persistence. Additional logic checks cover shipping thresholds, express charges, cancellation/restock, overselling and invalid-size prevention, HTML escaping and CSV formula handling.

Client-supplied product photographs are included for the requested demonstration. No general reuse licence is granted for these images.
