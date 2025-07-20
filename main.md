# System Requirements & Cost Summary

---

## System Requirements

| Component              | Description                                | Technology / Service                    |
| ---------------------- | ------------------------------------------ | --------------------------------------- |
| **Frontend**           | Web app (PWA) and Mobile app               | Next.js (PWA), Flutter (iOS/Android)    |
| **Backend**            | Centralized backend with API and DB        | Xano Starter Plan                       |
| **Hosting**            | Web app hosting                            | Vercel Hobby Plan (free)                |
| **Authentication**     | User signup/login, JWT token-based         | Xano built-in                           |
| **Database**           | Store users, subscriptions, products, etc. | Xano’s DB                               |
| **Push Notifications** | For app notifications                      | Firebase free tier                      |
| **Payments**           | Process subscription payments              | External payment gateway (Stripe, etc.) |
| **Domain**             | Customer-provided custom domain            | Customer responsibility                 |

---

## Cost Summary (per month)

| Item                 | Cost (USD)        | Notes                                                                       |
| -------------------- | ----------------- | ----------------------------------------------------------------------------|
| Xano Starter Plan    | \$29              | API, Database & DB backend UI                                               |
| Vercel Pro Plan      | \$20              | Web hosting (PWA). All app in a single vercel plan.                         |
| Firebase Push        | Free              | Up to free tier limits                                                      |
| Payment Gateway Fees | Variable          | Per transaction fees (\~2.9% + \$0.30)                                      |
| Domain               | Customer pays     | Depends on domain registrar                                                 |
| App Store Fees       | One-time / yearly | Google Play \$25 one-time, Apple \$99/year                                  |
