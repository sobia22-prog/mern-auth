**MERN Authentication System with Email Verification & Password Reset**

A complete authentication system that includes Email Verification and Password Reset using a secure 6-digit OTP sent directly to the user's email. This project ensures a robust authentication mechanism using MERN Stack (MongoDB, Express, React, Node.js) and JWT (JsonWebToken) for secure access management.


🚀 **Tech Stack**

**Frontend:** React, Tailwind CSS

**Backend:** Node.js, Express.js

**Database:** MongoDB

**Authentication:** JWT (JsonWebToken)

**Email Service:** Nodemailer


**📌 Features**

✅ User Registration & Login

✅ Email Verification with OTP

✅ Secure Password Reset with OTP

✅ JWT-based Authentication

✅ Fully Functional MERN Stack App



**🛠️ Installation & Setup**

**1️⃣ Clone the repository**

git clone https://github.com/sobia22-prog/mern-auth.git

cd mern-auth

**2️⃣ Backend Setup**

cd server

npm install

npm start

**3️⃣ Frontend Setup**

cd client

npm install

npm run dev


**4️⃣ Environment Variables**

Update .env file in the server/ folder:

MONGODB_URI = your_mongodb_url;

JWT_SECRET='your_secret_key'

NODE_ENV='development'

SMTP_USER="smtp username"

SMTP_PASS="your smtp paswword"

SENDER_EMAIL="your_email"
