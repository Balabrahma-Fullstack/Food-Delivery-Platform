# 🍅 TOMATO — Food Ordering Website

A modern, full-stack **food ordering platform** built using the **MERN Stack**. TOMATO provides a seamless online food ordering experience with dedicated interfaces for customers and administrators.

The platform supports authentication, food discovery, cart management, secure payments, order placement, and complete admin-side product and order management.

---

## 🌐 Live Demo

### 👤 User Panel

**Live Application:**
`https://your-food-delivery-frontend-url.onrender.com/`

### 🧑‍💼 Admin Panel

**Admin Dashboard:**
`https://your-food-delivery-admin-url.onrender.com/`

> Replace the above URLs with your deployed application links.

---

## ✨ Features

### 👤 User Panel

* User registration and login
* JWT-based authentication
* Secure password hashing with Bcrypt
* Browse food products
* Filter food items
* Add products to cart
* Update cart quantities
* Place orders
* Stripe payment integration
* View order status
* Logout functionality
* Responsive and user-friendly interface
* Beautiful alerts and notifications

### 🧑‍💼 Admin Panel

* Secure admin authentication
* Dashboard for managing the application
* Add food products
* Update food products
* Delete food products
* Manage food categories
* View customer orders
* Update order status
* Product management
* Order management

### 🔐 Backend & API

* RESTful API architecture
* JWT authentication
* Role-based identification
* Authenticated APIs
* MongoDB database integration
* Secure password hashing
* Stripe payment processing
* Image/file upload support

---

## 🎨 User Interface

The application provides a clean and responsive interface designed for a smooth food-ordering experience.

### 🏠 Hero Section

A visually engaging landing section that introduces the food ordering platform and guides users toward exploring available food items.

### 🍔 Food Products

Users can browse and filter food products based on available categories.

### 🛒 Cart

Users can review selected items, update quantities, and proceed with their orders.

### 🔐 Authentication

A simple and secure login/signup experience allows users to access personalized features.

### 📦 Order Management

Customers can place orders and track their order status, while administrators can manage orders from the admin dashboard.

---

## 📸 Screenshots

### 🏠 Hero Section

*Add your hero-section screenshot here.*

### 🍔 Products Section

*Add your products-section screenshot here.*

### 🛒 Cart Page

*Add your cart-page screenshot here.*

### 🔐 Login Popup

*Add your login/signup screenshot here.*

---

## 📁 Project Structure

```text
TOMATO/
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── ...
│
├── admin/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── ...
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
└── README.md
```

---

## ⚙️ Run Locally

### 1. Clone the Project

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the Project

```bash
cd TOMATO
```

---

### 3. Install Frontend Dependencies

```bash
cd frontend
npm install
```

---

### 4. Install Admin Dependencies

```bash
cd ../admin
npm install
```

---

### 5. Install Backend Dependencies

```bash
cd ../backend
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file inside the backend directory:

```env
JWT_SECRET=YOUR_SECRET_TEXT
SALT=YOUR_SALT_VALUE
MONGO_URL=YOUR_DATABASE_URL
STRIPE_SECRET_KEY=YOUR_STRIPE_SECRET_KEY
```

> Never commit your `.env` file or expose API keys, database credentials, or secret keys in a public repository.

---

## 🔗 Configure Application URLs

Update the backend URL in the admin application:

```javascript
// admin/src/App.jsx

const url = "YOUR_BACKEND_URL";
```

Update the backend URL in the frontend application:

```javascript
// frontend/src/context/StoreContext.js

const url = "YOUR_BACKEND_URL";
```

Configure the frontend URL in the backend order controller:

```javascript
// backend/controllers/orderController.js

const frontend_url = "YOUR_FRONTEND_URL";
```

---

## ▶️ Start the Application

### Start Backend

```bash
cd backend
npm run dev
```

If your project uses Nodemon directly:

```bash
nodemon server.js
```

### Start Frontend

Open a new terminal:

```bash
cd frontend
npm start
```

### Start Admin Panel

Open another terminal:

```bash
cd admin
npm start
```

---

## 🛠️ Tech Stack

### Frontend

* **React.js** — User interface
* **CSS** — Responsive styling
* **Axios** — API communication

### Backend

* **Node.js** — Server-side runtime
* **Express.js** — REST API framework
* **MongoDB** — Database
* **Mongoose** — MongoDB object modeling
* **JWT** — Authentication
* **Bcrypt** — Password hashing
* **Multer** — File and image uploads

### Payment

* **Stripe** — Secure online payment processing

---

## 🚀 Deployment

The application can be deployed using platforms such as **Render**, with separate deployments for:

* Frontend
* Admin Panel
* Backend API
* MongoDB database

Make sure all production environment variables and API URLs are correctly configured before deployment.

---

## 🔒 Security

The application follows common security practices including:

* JWT-based authentication
* Password hashing
* Protected API routes
* Role-based access control
* Environment-based secret management
* Authenticated user operations
* Secure payment processing through Stripe

---

## 📌 Future Enhancements

* 🔎 Advanced food search
* ⭐ Food ratings and reviews
* ❤️ Wishlist functionality
* 📧 Email order notifications
* 🔔 Real-time order tracking
* 📊 Advanced admin analytics
* 👤 User profile management
* 🎟️ Coupon and discount system
* 🤖 AI-powered food recommendations

---

## 👨‍💻 Author

### Bala Brahma Chari

**Full Stack Developer | AI Developer**

Passionate about building scalable web applications, solving real-world problems, and exploring modern technologies across full-stack development and Artificial Intelligence.

### Areas of Interest

* Full Stack Development
* React.js
* Node.js & Express.js
* MongoDB
* REST API Development
* Authentication & Authorization
* Generative AI
* AI-Powered Applications
* Data Structures & Algorithms

---

## 🤝 Contributing

Contributions and suggestions are welcome.

If you would like to contribute:

1. Fork the repository
2. Create a new feature branch
3. Implement your changes
4. Commit your changes
5. Push the branch
6. Create a Pull Request

---

## 📄 License

This project is available for educational and portfolio purposes.

---

## 📬 Contact

**Bala Brahma Chari**

For professional opportunities, collaboration, or project-related discussions, connect through your preferred professional platform.
