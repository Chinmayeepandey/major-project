# 🛒 Pandey's Store

Welcome to **Pandey's Store**, a fully functional full-stack offering a wide range of branded **Watches**, **Clothes**, **Electronic Devices**, and more. Built with the powerful **MERN Stack**, it delivers a seamless shopping experience with secure payments, post-purchase email confirmations and regular updates on sale offers on email, customer reviews, and integrated location mapping.


## 🚀 Features

- 🛍️ Browse and filter branded products by category
- 🛒 Add to cart, update quantity, and checkout
- 💳 **Secure payment** integration (e.g., Stripe)
- ✅ Email confirmation with order details via **AWS SES**
- 🌍 Delivery location preview using **Mapbox**
- 🧾 View order history and previous invoices
- 🔐 Secure login & register using `Passport.js` and `JWT`
- 📸 Product image hosting via **Cloudinary**
- 🗣️ **Write reviews** after purchase and **view previous customer reviews**
- 🛠️ Admin dashboard for managing products, orders & reviews
- 📱 Fully responsive design for desktop & mobile

---

## 🧱 Tech Stack

### Frontend
- React.js
- Redux Toolkit
- TailwindCSS
- Axios
- Mapbox GL JS

### Backend
- Node.js
- Express.js
- MongoDB + Mongoose

### Auth & Security
- Passport.js (Local Strategy)
- JWT-based Authentication
- bcrypt for password hashing

### Cloud & Media
- AWS SES (Email Notifications)
- Cloudinary (Image Hosting)
- Mapbox (Geolocation & Maps)
- Stripe (Payment Gateway)

---

## 💳 Payments

- Integrated **Stripe API** for secure and fast transactions
- Card details are securely handled using Stripe elements
- Order summary and payment receipt emailed after checkout

---

## 🗣️ Reviews System

- ✅ Only verified purchasers can leave reviews
- ⭐ Rating + comment support
- 📜 View all past reviews on product pages
- 🚫 Admins can moderate or remove abusive reviews

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/pandeys-store.git

# Install client & server dependencies
cd pandeys-store/client
npm install

cd ../server
npm install

# Create .env files in both /client and /server
# Example for /server/.env:
# MONGO_URI=your_mongodb_uri
# CLOUDINARY_API_KEY=your_cloudinary_key
# AWS_SES_KEY=your_ses_key
# STRIPE_SECRET_KEY=your_stripe_key
# MAPBOX_TOKEN=your_mapbox_token
# JWT_SECRET=your_jwt_secret

# Run the app
npm run dev   # Runs both frontend and backend concurrently
