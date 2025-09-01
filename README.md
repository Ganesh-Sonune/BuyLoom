#🛒 E-commerce Platform
This is a full-stack e-commerce application designed for modern online shopping experiences, utilizing cutting-edge technologies. The platform supports seamless user interaction, product management, secure payments, and analytics.

#🚀 Tech Stack
⚛️ Frontend: React.js
🌐 Backend: Node.js (Express)
🍃 Database: MongoDB
☁️ Image Storage: Cloudinary
💳 Payment Gateway: Stripe
🏎️ In-memory Cache: Redis
📊 Data Visualization: Recharts
#✨ Key Features
🔑 User Authentication: Sign up, login, password management
🛍️ Product Management: Add, edit, remove products
💰 Payment Processing: Integrated with Stripe for secure transactions
📸 Image Handling: Upload and store product images via Cloudinary
⚡ Performance: Caching with Redis to enhance performance
📈 Analytics: Real-time data visualization with Recharts
📦 Order Management: Track and manage orders efficiently
🛠️ Installation Guide
Prerequisites
Make sure you have the following installed:

Node.js 🟢
MongoDB 🍃
Redis 🏎️
Steps to Set Up
Clone the repository :

git clone https://github.com/Hariom-Ingle/e-commerce-store
cd ecommerce-project
Install server dependencies :

cd server
npm install
Install client dependencies :

Copy code
cd ../client
npm install
Environment Variables :

Create a .env file in the root of the server folder and add:

MONGODB_URI=<your-mongodb-uri>
CLOUDINARY_CLOUD_NAME=<your-cloudinary-cloud-name>
CLOUDINARY_API_KEY=<your-cloudinary-api-key>
CLOUDINARY_API_SECRET=<your-cloudinary-api-secret>
STRIPE_SECRET_KEY=<your-stripe-secret-key>
REDIS_URL=<your-redis-url>
5.Start the application:

Backend:

cd server
npm run dev
Frontend:

cd ../client
npm start
🎉 Access the App: Open your browser and visit http://localhost:3000.

📄 License This project is licensed under the MIT License.
