# Aastha Fresh — EdgeOne Static Website (Updated)

## Publish
- Publish the contents of this folder as a static site with `index.html` at the site root.
- `admin.html` is a shortcut to the hidden admin entry flow.
- The admin entry is triggered by clicking the header logo seven times within about 2.5 seconds.

## Features
- Grocery homepage inspired by the supplied reference, responsive navigation, category/product browsing, search/filter/sort, product details, cart, checkout demo and Cash on Delivery order flow.
- Admin registration once per browser, then login. Admin can add/edit/delete products, upload product photos, and upload the hero banner, two promotional banners, logo and favicon from mobile gallery/computer file picker.
- SVG line icons; no emoji icons.

## Important limitations
This is a static frontend demo. Login credentials, products, banner images, and orders are stored in browser localStorage, so they are not secure and are not shared between devices or visitors. Anyone who can inspect browser storage/devtools may bypass this demo protection. For a real public store, use server-side authentication with password hashing, role-based authorization, a database, and shared image storage (for example object storage). Do not use this localStorage login for real sensitive admin access.
