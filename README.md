# Frontend for E-Commerce Project

This document provides all the necessary information to set up and run the frontend for the e-commerce project. The frontend is built using React.js, leveraging modern tools and technologies to deliver a seamless user experience.


## Technologies Used

- React.js
- CSS Modules
- JavaScript (ES6+)
- React Context API
- Axios
- React Router
- Fetch API
- Vite
- ESLint
- Responsive Design:

## Features

- **User Authentication:** Login, registration, and integration with the backend for authentication.
- **Product Management:** View products by categories, search, and view detailed information.
- **Cart Management:** Add, remove, and update items in the cart with real-time cost calculation.
- **Backend Integration:** Fetch data for products, users, and orders via RESTful API.
- **Newsletter Subscription:** Frontend form integration for subscribing users.
- **Responsive Design:** Optimized for all screen sizes, from mobile to desktop.


## Project Structure

```plaintext
frontend/
├── public/                 # Public files (favicon, index.html)
├── src/
│   ├── Components/         # Reusable UI components (Navbar, Footer, ProductDisplay, etc.)
│   ├── Pages/              # Application pages (Shop, LoginSignup, Cart, etc.)
│   ├── Context/            # State management (ShopContext.jsx)
│   ├── Assets/             # Images, icons, and mock data
│   ├── App.js              # Main application component
│   ├── index.js            # Entry point for the React app
│   └── index.css           # Global styles
├── .gitignore              # Git ignored files
├── package.json            # Node.js dependencies and scripts
└── README.md               # Documentation
```

## How to Run

1. Clone the repository or download the project files:

    ```bash
    git clone <repository-url>
    cd ecommerce-frontend-main
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up environment variables by creating a `.env.local` file in the root directory. 


4. To build the application for production:

    ```bash
    npm start
    ```

## Screenshots

### Login
![Login](https://github.com/Redline1e/ecommerce-frontend/blob/main/public/screenshots/login.png)

### Item
![Item](https://github.com/Redline1e/ecommerce-frontend/blob/main/public/screenshots/item.png)

### Cart
![Transactions](https://github.com/Redline1e/ecommerce-frontend/blob/main/public/screenshots/cart.png)


## Notes

Ensure the backend server is running before starting the frontend.
The environment variable REACT_APP_API_URL must point to the correct backend API base URL.
Use the same versions of Node.js and npm/yarn for consistent behavior.

