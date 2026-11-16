# BU Saree Studio — website starter

## Included
- Responsive pink-and-gold boutique storefront
- Collection categories and sample product cards
- Shopping bag/cart
- WhatsApp enquiry and cart-order message flow
- Online-payment button marked as not yet activated

## Preview locally
Open `index.html` in a browser. An internet connection is needed for the Google Fonts.

## Before publishing
1. Open `index.html` in a text editor.
2. Find `WHATSAPP_NUMBER` and replace `91XXXXXXXXXX` with your WhatsApp Business number (country code + number, digits only).
3. Replace the three sample products in the `products` array with your real product names, prices and descriptions.
4. Replace the gradient product placeholders with your actual saree photos. The current cards are design placeholders, not product photographs.
5. Test all links and WhatsApp order messages.

## Publish free with GitHub Pages
1. Create a public GitHub repository, e.g. `bu-saree-studio`.
2. Upload `index.html` to the repository root.
3. Open Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish and open the URL shown there.

## Important: online payments
The Pay Online button is intentionally not active. Do not collect or store card, UPI PIN, CVV or banking credentials in this static website. To accept payments, create a merchant account with a payment provider such as Razorpay, integrate its Checkout using a server-side endpoint to create orders, and verify payment signatures on the server before marking an order paid. Never put secret keys in this HTML/JavaScript. Also publish clear shipping, returns/refund, privacy and contact policies before taking orders.
