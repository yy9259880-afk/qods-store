# QODS STORE

Responsive multilingual storefront for QODS STORE, Casablanca, with Arabic, French, and English. Includes product management, individually replaceable product images, cart, WhatsApp checkout, GSAP scroll animation, a procedural Three.js hero scene, and a 3D mannequin preview for apparel.

## Start

You can open `index.html` directly in a browser. The page uses classic browser scripts so its products and layout also work from a `file://` address. GSAP, Three.js, and Google Fonts load from public CDNs, so the 3D scene and animated effects need an internet connection. For development, install Node.js, run `npm install` and `npm run dev`, then open the local address printed by Vite.

## Product editor

Select the small pencil icon in the header. Each product has its own image field; replacement uploads affect only that product. The editor stores products and cart contents in the current browser's local storage. Uploaded images are resized and compressed before saving. This is a front-end demo: products are saved per browser/device, not to a shared server.

## Checkout

The checkout button opens a WhatsApp message to QODS STORE at +212 604 55 40 28. The message includes cart items and total, with a prompt to enter the delivery city.
