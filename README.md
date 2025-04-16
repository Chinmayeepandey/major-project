# 🛒 Pandey's Store

Welcome to **Pandey's Store**, a fully functional full-stack platform offering a wide range of branded **Watches**, **Clothes**, **Electronic Devices**, and more. Built with the powerful **MERN Stack**, it delivers a seamless shopping experience, email notifications after purchase,and daily updates on sale offers on your email with integrated location mapping.


## 🚀 Features

- 🛍️ Browse branded products across multiple categories
- 🔐 Secure Authentication using `Passport.js` and `JWT`
- 🧾 Email confirmation after checkout using **AWS SES**
- 📍 Map-based delivery location using **Mapbox**
- 🖼️ Image uploads with **Cloudinary**
- 📦 Add to cart, checkout, and order tracking
- 📊 Admin dashboard for product and order management
- 📱 Responsive design for all devices

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
- AWS SES (Email Service)
- Cloudinary (Image Hosting)
- Mapbox (Geolocation & Maps)


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
# MAPBOX_TOKEN=your_mapbox_token
# JWT_SECRET=your_jwt_secret

# Run the app
npm run dev   # Runs both frontend and backend (use concurrently)

