**This is a full-stack E-Commerce web application built using React.js for the frontend and Spring Boot for the backend. The application allows users to browse products, filter by categories, add items to cart, authenticate securely, and complete orders with payment integration. An admin dashboard is also available for managing products and orders.**



![Homepage](https://github.com/Arindam130701/E-Commerce-Website/blob/67fc9a64c28f6dd5f94454c61ff2577aa2551553/Home.png)

**Frontend (React.js)**

The frontend is developed using React.js with a structured and scalable project architecture.
It includes a Home page with multiple sections and a responsive Footer.
Products are displayed using mock API data initially and later integrated with the backend API.
Users can navigate between pages including Categories, Product Details, Cart, and Checkout.
Filtering functionality is implemented in the Categories page.
A detailed Product page shows product information and pricing.
Shopping cart functionality allows users to add, remove, and update product quantities.
User authentication is implemented with Sign-up, Login, and Logout functionality.
A complete Checkout process is available for order placement.


**Backend (Spring Boot)**

The backend is developed using Spring Boot following RESTful API principles.
Product APIs are implemented for fetching and managing product data.
User authentication and authorization are implemented using JWT (JSON Web Token).
Secure APIs are protected using Spring Security.
Order processing and management system is implemented.
Payment gateway integration is added for secure transactions.
Admin dashboard APIs are available for managing products and orders.

**Authentication & Security**

JWT-based authentication system is implemented.
Password encryption is handled securely.
Role-based access control is implemented for Admin and Users.
Protected routes are secured on both frontend and backend.
