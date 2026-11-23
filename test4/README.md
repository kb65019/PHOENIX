# Phoenix storefront

This folder is a lightweight, static storefront adapted from the supplied Phoenix prototype. It runs without a build step and can be deployed to any static host.

## Run locally

Serve this directory with any static HTTP server (for example `python3 -m http.server 8000`) and open `http://localhost:8000`. The cart is stored in browser local storage. Product/category seed data is embedded in `index.html` in the `CATALOG` and generated `PRODUCTS` arrays.

## Deployment checklist

1. Deploy this directory to Vercel (or another static host).
2. Connect the store domain and enable HTTPS.
3. Replace the placeholder contact and policy details with verified Phoenix information.
4. Set the canonical host in `index.html` and update `sitemap.xml` before launch.
5. Submit `/sitemap.xml` in Google Search Console and Bing Webmaster Tools.
6. Replace the demo checkout with a server-side order and payment integration before accepting real orders.

## Current scope

The prototype includes the supplied logo, responsive catalog, subcategory and price filtering, sorting, product details, variants, cart, and WhatsApp checkout handoff. `robots.txt`, `llms.txt`, a web manifest, and a basic offline cache are included. Added product names, prices, and sale markdowns are demo content; replace them with the actual Phoenix inventory and approved promotion schedule before publishing. Store contact and policy data also need verification. There is no CMS, secure checkout, customer account system, order tracking backend, admin dashboard, real review system, or production product feed yet; those require store credentials, operational data, and a backend service.
