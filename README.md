# 🛒 E-Commerce API with Authentication

A secure and scalable **E-Commerce REST API** built with **Node.js, Express.js, MongoDB, and JWT Authentication**.

This backend project provides APIs for user authentication, product management, and shopping cart operations. It follows a modular project structure with separate controllers, routes, models, and middleware for better maintainability.

---

## 🚀 Features

- 🔐 User Authentication using JWT
- 👤 User Registration and Login
- 🔒 Protected API Routes
- 🛍️ Product Management
- 🛒 Shopping Cart Management
- 🗄️ MongoDB Database Integration
- ⚡ RESTful API Architecture
- 🧩 Modular Backend Structure
- 🔑 Environment Variables for Sensitive Configuration
- 🛡️ Authentication Middleware
- 📦 Express.js Server

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Node.js | Backend Runtime |
| Express.js | Web Framework |
| MongoDB | Database |
| Mongoose | MongoDB ODM |
| JWT | Authentication |
| JavaScript | Programming Language |
| Nodemon | Development Server |

---

## 📂 Project Structure

```text
ecommerce-api-authentication/
│
├── Controllers/
│   ├── cart.js
│   ├── product.js
│   └── user.js
│
├── Middlewares/
│   └── Auth.js
│
├── Models/
│   ├── Cart.js
│   ├── Product.js
│   └── User.js
│
├── Routes/
│   ├── cart.js
│   ├── product.js
│   └── user.js
│
├── .gitignore
├── package.json
├── package-lock.json
└── server.js


🔐 Authentication

The application uses JSON Web Tokens (JWT) to authenticate users.

Authentication Flow
User Registration
       ↓
User Login
       ↓
Credentials Verification
       ↓
JWT Token Generated
       ↓
Token Sent to Client
       ↓
Protected API Request
       ↓
Authentication Middleware
       ↓
Access Granted

Protected routes require a valid JWT token.

Example:

Authorization: Bearer <your-jwt-token>
📌 API Modules
👤 User APIs

User APIs handle:

User registration
User login
Authentication
User-related operations
🛍️ Product APIs

Product APIs handle:

Creating products
Fetching products
Updating products
Deleting products
🛒 Cart APIs

Cart APIs handle:

Adding products to cart
Viewing cart
Updating cart items
Removing products from cart
⚙️ Installation
1. Clone the Repository
git clone https://github.com/abhi9504/ecommerce-api-authentication.git
2. Navigate to the Project
cd ecommerce-api-authentication
3. Install Dependencies
npm install
🔑 Environment Variables

Create a .env file in the root directory:

PORT=3000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

⚠️ Never upload your .env file or database credentials to GitHub.

The .env file is already included in .gitignore.

▶️ Run the Project
Development Mode
npx nodemon server.js

or:

npm run dev
Start Server
node server.js

The server will run on:

http://localhost:3000
🧪 API Testing

You can test the APIs using tools such as:

Postman
Thunder Client
Insomnia

Example request:

POST http://localhost:3000/...

For protected endpoints, include:

Authorization: Bearer <your-jwt-token>
🗄️ Database

This project uses MongoDB for storing application data.

Main database models include:

User
Product
Cart

MongoDB provides persistent storage for users, products, and cart information.

🔒 Security

The project follows basic backend security practices:

JWT-based authentication
Protected routes
Environment variables for secrets
.env excluded from Git
Middleware-based authentication
Password protection through the authentication system
📦 Dependencies

The project uses Node.js packages defined in:

package.json

Install all dependencies with:

npm install
📸 Project Preview
Backend API

This project is primarily a backend REST API and can be tested using Postman or Thunder Client.

You can add screenshots here later:

![API Testing](./screenshots/api-testing.png)

Recommended project structure:

ecommerce-api-authentication/
│
├── screenshots/
│   ├── api-testing.png
│   └── authentication.png
│
├── Controllers/
├── Middlewares/
├── Models/
├── Routes/
└── server.js
🎯 Learning Outcomes

Through this project, I practiced and implemented:

REST API development
Node.js backend development
Express.js routing
MongoDB database integration
Mongoose models
JWT authentication
Authentication middleware
CRUD operations
API testing
Environment variable management
Git and GitHub version control
🔮 Future Improvements

Possible future enhancements include:

Role-based authorization
Admin dashboard
Product search and filtering
Product categories
Order management
Payment gateway integration
Image upload for products
API documentation using Swagger
Deployment using cloud platforms
Rate limiting and additional security
👨‍💻 Author

Abhishek Kumar

B.Tech Computer Science Engineering

GitHub:
https://github.com/abhi9504

⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub.

📄 License

This project is created for learning and educational purposes.
