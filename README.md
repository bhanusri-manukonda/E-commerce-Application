<div align="center">

# 🛍️ ShopEZ — Full-Stack MERN E-Commerce Platform

### Shop Smarter. Experience Better.

A modern full-stack e-commerce platform featuring an interactive customer storefront, secure authentication, shopping cart, order management, and a comprehensive admin dashboard.

<p>
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Vite-Build_Tool-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Node.js-Runtime-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
</p>

<p>
  <img src="https://img.shields.io/badge/Express.js-Backend-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js">
  <img src="https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Git-GitHub-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
</p>

<br>

**🛒 Online Shopping &nbsp; • &nbsp; 🔐 Authentication &nbsp; • &nbsp; 📦 Order Management**

**📊 Admin Analytics &nbsp; • &nbsp; ❤️ Wishlist &nbsp; • &nbsp; 🏷️ Coupons**

</div>

---

## 📑 Table of Contents

- [🛍️ About ShopEZ](#-about-shopez)
- [🎯 Project Highlights](#-project-highlights)
- [✨ Features](#-features)
- [🛒 Customer Storefront](#-customer-storefront)
- [⚙️ Admin Dashboard](#️-admin-dashboard)
- [🛠️ Technologies Used](#️-technologies-used)
- [🧠 Technical Skills Demonstrated](#-technical-skills-demonstrated)
- [🏗️ Project Architecture](#️-project-architecture)
- [🚀 Installation and Setup](#-installation-and-setup)
- [🔑 Demo Accounts](#-demo-accounts)
- [🔌 API Endpoints](#-api-endpoints)
- [🎟️ Preloaded Coupons](#️-preloaded-coupons)
- [🎨 Design System](#-design-system)
- [🔒 Security Considerations](#-security-considerations)
- [🧪 Testing and Validation](#-testing-and-validation)
- [🚧 Future Enhancements](#-future-enhancements)
- [👩‍💻 Developer](#-developer)

---

# 🛍️ About ShopEZ

**ShopEZ** is a full-stack e-commerce web application built using the **MERN stack — MongoDB, Express.js, React, and Node.js**.

The platform is designed to deliver a convenient online shopping experience while providing administrators with tools to manage products, categories, orders, customers, coupons, and store analytics.

The application separates the customer shopping experience from administrative operations and connects the frontend to backend REST APIs.

### 🎯 Project Objectives

- Develop a complete full-stack e-commerce application.
- Create an interactive and responsive customer storefront.
- Implement authentication and role-based access control.
- Build REST APIs for products, carts, wishlists, and orders.
- Manage application data using MongoDB and Mongoose.
- Provide administrative tools for managing store operations.
- Apply practical software engineering concepts in a real-world application.

---

# 🎯 Project Highlights

| Feature | Description |
|---|---|
| 🛒 Online Store | Browse products and explore available categories. |
| 🔐 Authentication | Registration, login, and JWT-based authentication. |
| 🔎 Product Discovery | Search, filter, sort, and explore products. |
| ❤️ Wishlist | Save products for future purchases. |
| 🏷️ Coupon System | Apply eligible discount codes during shopping. |
| 🧾 Checkout | Follow a multi-step checkout workflow. |
| 📦 Order Management | View orders, track status, and access order details. |
| ⭐ Review Management | Support product reviews and administrative moderation. |
| 🖼️ Image Uploads | Support local image storage or optional Cloudinary integration. |
| 📊 Admin Dashboard | View key performance indicators, charts, and product data. |
| 📈 Analytics | Review revenue, orders, and business trends. |
| 🎨 Modern UI | Use a consistent design system with animations and notifications. |

---

# ✨ Features

## 🛒 1. Customer Shopping Experience

The customer storefront provides the main shopping interface.

- Browse products and categories.
- Search and filter product listings.
- Sort products using supported criteria.
- View individual product details.
- Access product reviews and price history.
- Add and remove items from the shopping cart.
- Apply eligible coupons.
- Maintain a wishlist.
- Complete the checkout workflow.
- View order history and order details.
- Manage profile information and addresses.

## 🔐 2. Authentication and Account Management

- User registration and login.
- JWT-based authentication.
- Current-user information retrieval.
- Password hashing using bcryptjs.
- Profile and password management.
- Administrative access controls.

> Authentication and authorization must be enforced by the backend. Frontend route protection alone is not sufficient.

## 🏷️ 3. Coupon and Discount System

ShopEZ includes predefined discount coupons.

- Percentage-based discounts.
- Fixed-value discounts.
- Minimum order requirements.
- Maximum discount limits for supported coupons.
- Coupon application through the cart workflow.

## 📦 4. Order Management

The order workflow includes:

- Order creation.
- Customer order history.
- Order detail pages.
- Order status management.
- Order cancellation options.
- Administrative order management.

The exact order lifecycle depends on the backend implementation.

## 🖼️ 5. Image Management

ShopEZ supports image uploads through its backend.

- Multer-based file upload handling.
- Local image storage without Cloudinary.
- Optional Cloudinary integration.
- Product image management through the admin interface.

## 📊 6. Administrative Analytics

The admin dashboard is designed to provide an overview of store activity.

- Key performance indicators.
- Revenue and order charts.
- Top product information.
- Order management.
- User management.
- Product and category management.
- Coupon and review administration.
- Store settings.

---

# 🛒 Customer Storefront

The storefront is organized into dedicated pages for browsing, shopping, and account management.

| Page | Route | Description |
|---|---|---|
| Home | `/` | Hero banners, flash deals, and trending products |
| Products | `/products` | Product listings, search, filters, and sorting |
| Product Details | `/products/:slug` | Product information, reviews, and price history |
| Shopping Cart | `/cart` | Manage cart items and apply coupons |
| Wishlist | `/wishlist` | Manage saved products |
| Checkout | `/checkout` | Multi-step checkout workflow |
| My Orders | `/orders` | View order history and tracking |
| Order Details | `/orders/:id` | View order information and cancellation options |
| Profile | `/profile` | Manage profile, addresses, and password |
| Authentication | `/login` and related routes | Login, registration, and password recovery |

---

# ⚙️ Admin Dashboard

The administrative interface provides centralized store management.

| Module | Route | Description |
|---|---|---|
| Dashboard | `/admin` | KPIs, charts, and top products |
| Products | `/admin/products` | Product CRUD and image uploads |
| Categories | `/admin/categories` | Manage product categories |
| Banners | `/admin/banners` | Manage hero banners |
| Orders | `/admin/orders` | Manage orders and update statuses |
| Users | `/admin/users` | Manage users and blocking controls |
| Coupons | `/admin/coupons` | Create and manage discount coupons |
| Reviews | `/admin/reviews` | Moderate product reviews |
| Analytics | `/admin/analytics` | Review revenue, orders, and trends |
| Settings | `/admin/settings` | Manage profile, password, and site settings |

*The routes above reflect the supplied project specification. Confirm that each page and operation is implemented before presenting it as a verified feature.*

---

# 🛠️ Technologies Used

## 🎨 Frontend

<p>
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white" alt="Framer Motion">
</p>

| Technology | Purpose |
|---|---|
| React 18 | Component-based user interface |
| Vite | Development server and build tooling |
| Tailwind CSS v4 | Utility-first styling |
| Framer Motion | UI animations |
| React Router v6 | Client-side navigation |
| React Hook Form | Form management |
| Chart.js | Charts and data visualization |
| Lucide React | Icons |
| React Hot Toast | Notifications |

## ⚙️ Backend

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/JWT-Authentication-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT">
</p>

| Technology | Purpose |
|---|---|
| Node.js | JavaScript runtime |
| Express.js | Backend API framework |
| MongoDB | Database |
| Mongoose | Database modeling |
| JWT | Token-based authentication |
| bcryptjs | Password hashing |
| Multer | File uploads |
| Cloudinary | Optional cloud image storage |
| Helmet | HTTP security headers |
| Morgan | HTTP request logging |

## 🔧 Development Tools

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code">
</p>

---

# 🧠 Technical Skills Demonstrated

## 1. Full-Stack Development

- React component development.
- Frontend and backend integration.
- REST API communication.
- Client-server architecture.
- Environment-based configuration.

## 2. Database Management

- MongoDB data storage.
- Mongoose data modeling.
- Managing products, users, and orders.
- Handling relationships between application entities.

## 3. Backend Development

- Express.js route handling.
- REST API design.
- Request and response processing.
- Authentication and authorization.
- File upload handling.

## 4. Frontend Development

- Component-based architecture.
- Client-side routing.
- Form handling.
- Product filtering and sorting.
- Responsive interface development.
- UI feedback and animations.

## 5. E-Commerce Business Logic

- Shopping cart operations.
- Coupon validation.
- Wishlist management.
- Checkout workflows.
- Order status management.
- Administrative operations.

## 6. Software Engineering

- Modular application structure.
- Environment configuration.
- Error handling and debugging.
- Dependency management.
- Version control with Git and GitHub.

---

# 🏗️ Project Architecture

ShopEZ follows a client-server architecture in which the React frontend communicates with an Express backend, which accesses MongoDB through Mongoose.

```text
                    👤 CUSTOMER / ADMIN
                            |
                            v
                 ┌─────────────────────┐
                 │   React Frontend    │
                 │                     │
                 │ Storefront          │
                 │ Cart & Wishlist     │
                 │ Checkout & Orders   │
                 │ Admin Dashboard     │
                 └──────────┬──────────┘
                            |
                            | HTTP / REST API
                            v
                 ┌─────────────────────┐
                 │   Express Backend   │
                 │                     │
                 │ Authentication      │
                 │ Product Management  │
                 │ Cart & Wishlist     │
                 │ Order Processing    │
                 │ Admin Operations    │
                 └──────────┬──────────┘
                            |
                            | Mongoose
                            v
                 ┌─────────────────────┐
                 │      MongoDB        │
                 │                     │
                 │ Users               │
                 │ Products            │
                 │ Categories          │
                 │ Orders              │
                 │ Coupons & Reviews   │
                 └─────────────────────┘

                 Optional Image Storage
                            |
                            v
                        Cloudinary
```

### Architecture Overview

| Layer | Responsibility |
|---|---|
| Frontend | User interface, navigation, and user interactions |
| Backend | Business logic, API endpoints, and authorization |
| Database | Persistent application data |
| Image Storage | Local file storage or optional Cloudinary integration |

---

# 🚀 Installation and Setup

Follow these steps to run ShopEZ locally.

## 1️⃣ Prerequisites

Install the following:

- [Node.js](https://nodejs.org/)
- npm
- [MongoDB Community Server](https://www.mongodb.com/try/download/community) or a MongoDB connection string
- [Git](https://git-scm.com/)

## 2️⃣ Clone the Repository

Replace the placeholder with your actual repository URL.

```bash
git clone <YOUR_SHOPEZ_REPOSITORY_URL>
cd <YOUR_PROJECT_FOLDER>
```

## 3️⃣ Install Dependencies

### Backend

```bash
cd server
npm install
```

### Frontend

Open a second terminal from the project root:

```bash
cd client
npm install
```

## 4️⃣ Configure Environment Variables

Create your local environment files from the provided examples.

### Windows PowerShell

Run these commands from the project root if both example files exist:

```powershell
Copy-Item server/.env.example server/.env
Copy-Item client/.env.example client/.env
```

If the example files are missing, create the `.env` files manually.

### Backend — `server/.env`

```env
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/shopez
JWT_SECRET=replace_with_a_long_random_secret
CLIENT_URL=http://localhost:5173
```

### Frontend — `client/.env`

```env
VITE_API_URL=http://localhost:5000/api
```

Ensure MongoDB is running and the connection string matches your database setup.

## 5️⃣ Seed Demo Data

From the project root:

```bash
cd server
npm run seed
```

The supplied seed configuration is expected to create:

- 16 products
- 7 categories
- 3 coupons
- 3 hero banners
- One administrator demo account
- One customer demo account

Check the seed script before running it against a database containing existing data.

## 6️⃣ Start the Backend

In the first terminal:

```bash
cd server
npm run dev
```

Expected backend address:

```text
http://localhost:5000
```

## 7️⃣ Start the Frontend

In a second terminal:

```bash
cd client
npm run dev
```

Expected frontend address:

```text
http://localhost:5173
```

## 8️⃣ Open ShopEZ

Visit the frontend in your browser:

**http://localhost:5173**

Both the backend and frontend must be running.

---

# 🔑 Demo Accounts

Use the following credentials for local development if they are created by the seed script.

| Role | Email | Password |
|---|---|---|
| Administrator | `admin@shopez.com` | `admin123` |
| Customer | `customer@shopez.com` | `customer123` |

> ⚠️ **Security Warning:** These are development credentials. Never use default demo credentials for a production deployment.

---

# 🔌 API Endpoints

The backend provides REST API endpoints for authentication, products, categories, carts, wishlists, orders, administration, and image uploads.

## 🔐 Authentication

| Method | Endpoint | Description |
|---|---|---|
| POST | `/api/auth/register` | Register a user |
| POST | `/api/auth/login` | Authenticate a user |
| GET | `/api/auth/me` | Retrieve the current user |

## 🛍️ Products and Categories

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/products` | Retrieve products with supported filters |
| GET | `/api/products/:id` | Retrieve a product |
| POST | `/api/products` | Create a product — admin |
| GET | `/api/categories` | Retrieve categories |

Example product query:

```text
/api/products?keyword=phone&category=electronics&sort=price&page=1
```

## 🛒 Cart

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/cart` | Retrieve the user's cart |
| POST | `/api/cart` | Add or update a cart item |
| DELETE | `/api/cart/:itemId` | Remove a cart item |
| POST | `/api/cart/apply-coupon` | Apply a coupon |

## ❤️ Wishlist

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/wishlist` | Retrieve the wishlist |
| POST | `/api/wishlist` | Add or update wishlist items |

## 📦 Orders

| Method | Endpoint | Description |
|---|---|---|
| POST | `/api/orders` | Create an order |
| GET | `/api/orders/my` | Retrieve the user's orders |

## 📊 Administration

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/admin/dashboard` | Retrieve dashboard data |
| GET | `/api/admin/orders` | Retrieve administrative order data |
| GET | `/api/admin/users` | Retrieve user data |
| GET | `/api/admin/analytics` | Retrieve analytics data |
| POST | `/api/upload` | Upload an image — admin |

**Note:** This table summarizes the endpoints provided in the project specification. Verify the exact route handlers, HTTP methods, permissions, request formats, and response structures against the source code.

---

# 🎟️ Preloaded Coupons

The supplied seed configuration includes the following coupon codes.

| Coupon Code | Discount | Minimum Order |
|---|---|---:|
| `WELCOME10` | 10% off, maximum ₹200 | ₹500 |
| `FLAT200` | ₹200 off | ₹2,000 |
| `ELEC15` | 15% off, maximum ₹1,500 | ₹5,000 |

Coupon availability and final discounts depend on the backend's validation rules.

---

# 🎨 Design System

ShopEZ uses a consistent visual design system to maintain a unified interface.

| Design Token | Value |
|---|---|
| Primary Blue | `#2563EB` |
| Secondary Indigo | `#4F46E5` |
| Accent Orange | `#F97316` |
| Success Green | `#22C55E` |
| Danger Red | `#EF4444` |
| Background | `#F8FAFC` |
| Heading Font | Poppins |
| Body Font | Inter |
| Card Border Radius | `16px` |

### Design Principles

- Consistent color usage.
- Clear visual hierarchy.
- Reusable interface components.
- Responsive layouts.
- Meaningful interaction feedback.
- Consistent styling across customer and admin pages.

---

# 🔒 Security Considerations

The application uses several security-related technologies and configuration options.

- JWT-based authentication.
- Password hashing with bcryptjs.
- Helmet for HTTP security headers.
- Environment variables for sensitive configuration.
- Administrative access restrictions.
- Configurable frontend origin.

Before deploying the application:

- Use a strong, randomly generated JWT secret.
- Never commit `.env` files or credentials.
- Enforce authorization on protected backend endpoints.
- Validate user input and uploaded files.
- Configure production CORS settings.
- Use HTTPS.
- Replace default demo passwords.
- Review token expiration and storage practices.
- Configure appropriate file upload limits and permissions.

These technologies support security, but their presence alone does not guarantee that the application is secure.

---

# 🧪 Testing and Validation

The application should be tested across its customer and administrative workflows.

| Area | Recommended Verification |
|---|---|
| Authentication | Registration, login, and protected routes |
| Products | Search, filtering, sorting, and product details |
| Cart | Add, update, and remove items |
| Coupons | Valid, invalid, and ineligible coupon cases |
| Wishlist | Add and remove saved products |
| Orders | Order creation, history, and status updates |
| Administration | Product, category, and user management |
| Image Uploads | File validation and storage behavior |
| Analytics | Dashboard data and chart rendering |
| UI | Responsive layout and browser-console errors |

*Do not describe tests as passing until they have actually been executed.*

---

# 🚧 Future Enhancements

Potential improvements for future versions include:

- [ ] Add automated frontend and backend tests.
- [ ] Document API requests and responses with OpenAPI.
- [ ] Integrate a payment gateway.
- [ ] Add email notifications for order updates.
- [ ] Improve accessibility and keyboard navigation.
- [ ] Add product recommendation functionality.
- [ ] Introduce Docker-based development.
- [ ] Configure a CI/CD pipeline.
- [ ] Deploy the application to a production environment.
- [ ] Add live application screenshots and a demo link.

These are proposed improvements, not claims about current functionality.

---

# 👩‍💻 Developer

<div align="center">

### Bhanusri Manukonda

Computer Science and Engineering  
Aspiring Software Developer

<br>

<a href="https://github.com/bhanusri-manukonda">
  <img src="https://img.shields.io/badge/GitHub-bhanusri--manukonda-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile">
</a>

</div>

---

# 📌 Project Purpose

ShopEZ demonstrates the practical application of full-stack web development through an e-commerce use case.

The project brings together frontend development, REST API integration, database management, authentication, business logic, and administrative workflows in one application.

It is intended as a portfolio project showcasing MERN stack development and practical software engineering skills.

---

<div align="center">

### ⭐ Like the project? Consider starring the repository!

**ShopEZ — Browse Products. Shop with Ease. Manage with Confidence.**

</div>
