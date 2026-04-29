# MexaBeer 🍻

A full‑stack B2C e‑commerce store for craft beer in Mexico City. The platform offers a warm, artisan brand identity, a mobile‑optimised shopping experience, and a powerful admin dashboard for managing products, orders, and customers.

## Tech Stack
- **Frontend:** React · Redux Toolkit · Tailwind CSS · i18next (Spanish/English)
- **Backend:** Node.js · Express · MongoDB + Mongoose
- **Payments:** Stripe Checkout · Webhooks · Automatic payment status updates
- **Media:** Cloudinary (optimised on‑the‑fly with WebP/AVIF)
- **Security:** Helmet · Rate Limiting · Input Validation · JWT Authentication · HTTP‑only cookie support
- **PWA:** Service Worker · Manifest · Installable on mobile/home screen
- **Legal:** Privacy Policy, Terms of Service, Security Policy (bilingual)
- **SEO :** Dynamic sitemap, Open Graph meta tags, clean URLs

## Key Features
- 🔍 Product filtering & sorting (category, brand, style, size, price)
- 🛒 Cart with stock‑aware quantity limits and coupon support
- 💳 Stripe checkout with success/cancel pages and webhook processing
- 👤 User accounts, order history, shipping addresses
- 📱 Mobile‑first responsive design with touch‑friendly filters
- 🧑‍💻 Full admin dashboard (products, categories, brands, styles, orders, coupons, customers)
- 🌍 Bilingual interface (English / Spanish) using i18next
- 📸 Optimised images served as WebP/AVIF via Cloudinary transformations
- 🛡️ Security best practices (CSP, HSTS, rate limiting, input sanitisation)
- 📄 Legal compliance (Mexican LFPDPPP, GDPR‑ready cookie consent)
- ⚡ Skeleton loading screens for a smooth user experience

## Status
Production‑ready and actively maintained. Built for a client but designed as a reusable e‑commerce foundation.
