# 🛍️ Sjain T-Shirt E-Commerce Store

A fully functional modern e-commerce web application built with **Next.js**, **Sanity.io** (headless CMS), and **Stripe** for secure payments. The store sells customized t-shirts featuring anime, cartoons, forex trading themes, church quotes, and more.

## 🚀 Live Site

👉 [Visit Store](https://sjainstore.vercel.app)

## 🧰 Tech Stack

- **Frontend:** Next.js, React, Tailwind CSS
- **CMS:** Sanity.io (Headless CMS)
- **Payments:** Stripe
- **Hosting:** Vercel (Frontend) & Sanity Studio (CMS)
- **State Management:** React Context API
- **Notifications:** react-hot-toast

## 💳 Stripe Integration

- Integrated Stripe Checkout.
- Fake card for testing:
Card Number: 4242 4242 4242 4242  
Expiry: Any future date  
CVC: Any 3-digit number  
ZIP: Any ZIP

## 🧠 Sanity CMS

- Use `sanity deploy` to publish the backend studio.
- Custom content types: `product`, `banner`.

Access Sanity Studio (once deployed):
```bash
sanity deploy
https://sjain.sanity.studio

git clone https://github.com/SjainThuli/ecommerce_T-shirts.git
cd ecommerce_T-shirts
npm install
sanity install
sanity start

Setup Environment Variables
Create .env.local:
NEXT_PUBLIC_SANITY_PROJECT_ID=your_project_id
NEXT_PUBLIC_SANITY_DATASET=production
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
NEXT_PUBLIC_SANITY_TOKEN=your_sanity_token
STRIPE_SECRET_KEY=your_stripe_secret_key

Run the Application

npm run dev

## ⚙️ Features

✅ Custom product pages (powered by Sanity CMS)  
✅ Animated add-to-cart system  
✅ Checkout flow with Stripe  
✅ Responsive design for mobile/tablet  
✅ Admins can add/edit products & banners via Sanity Studio  
✅ Toast notifications  
✅ Real-time cart updates  
