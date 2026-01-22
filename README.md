# 🚚 Food Ordering Web App (MERN Stack)

## ✨ Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [Contact](#contact)

## 📊 Introduction
This is a full-stack food ordering web application built using the MERN stack (MongoDB, Express, React, Node.js). The application consists of a customer-facing app for ordering food and an admin app for managing orders, menu items, and more.

## 🚀 Features
- User authentication and authorization
- Browse food items
- Add items to the cart and place orders
- Stripe Payment Integration: Secure and reliable payment processing using Stripe.
- Order tracking
- Admin panel to manage menu items, orders

## 🛠️ Technologies Used
- **Frontend:** React.js, React Context API, React Router
- **Backend:** Node.js, Express.js
- **Payment Gateway:** Stripe
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Styling:** CSS

## Installation
### Prerequisites
- Node.js
- MongoDB

## 🚀 Run Locally — Step-by-step

Make sure you have Node.js (v20+ recommended) and npm installed.

### Clone the Repository
```sh
git clone https://github.com/DulanjaliSenarathna/mern-food-delivery-app.git
cd mern-food-delivery-app
```

## Backend Setup
Navigate to the backend directory:

```sh
cd backend

```
Install dependencies:

```sh
npm install
```

Create a .env file in the backend directory and add the following:

```sh
JWT_SECRET = "random#secret"
STRIPE_SECRET_KEY = "your_stripe_secret_key_here" 
⚠️ Note: Do not commit your .env file. Create your own keys from Stripe Dashboard and use them locally.

```
 
Start the backend server:

```sh
npm run server
```
## Frontend Setup
Navigate to the frontend directory:

```sh

cd frontend
```

Install dependencies:
```sh

npm install
```

Start the frontend server:
```sh

npm run dev
```

## Admin App Setup

Navigate to the admin directory:
```sh

cd admin
```

Install dependencies:

```sh
npm install
```

Start the admin app :
```sh
npm run dev
```

## Usage
Access the customer-facing app at http://localhost:5173.
Access the admin app at http://localhost:5174.
Register as a new user or log in with existing credentials.
Browse the menu, add items to the cart, and place an order.
Pay using dummy visa card
Use the admin panel to manage orders, menu items.

## 📸 Screenshots
# 🏠 Home :
<img width="1627" height="858" alt="Screenshot 2026-01-22 100757" src="https://github.com/user-attachments/assets/e1a564a2-6db3-4efd-a950-2bf4b0c66335" />
# 🔐 Login : 
<img width="1602" height="851" alt="Screenshot 2026-01-22 100821" src="https://github.com/user-attachments/assets/3fe70528-92ba-494f-9b18-7c5fb159c3a3" />
# 🔐 Signup : 
<img width="1674" height="845" alt="Screenshot 2026-01-22 100856" src="https://github.com/user-attachments/assets/65a39a4a-a262-451c-8b46-171ff4000e50" />
# 🍔 Menu :
![Capture2](https://github.com/DulanjaliSenarathna/mern-food-delivery-app/assets/59603716/22fc6a58-b713-4ab7-babb-cff5844e7c55)
# 🍱 Menu Food :
<img width="1260" height="567" alt="Screenshot 2026-01-22 101343" src="https://github.com/user-attachments/assets/bdbe0a46-89e4-4a00-a027-190aff9c9ef1" />
# ℹ️ App Download : 
<img width="1246" height="754" alt="Screenshot 2026-01-22 100955" src="https://github.com/user-attachments/assets/99766768-d902-4dee-a01a-3a06d9e8f15f" />
# 🍱 Menu Food :
<img width="1260" height="567" alt="Screenshot 2026-01-22 101343" src="https://github.com/user-attachments/assets/1b25b3ac-114c-4c78-aed2-eed1e9e0bcb9" />
# 🛒 Cart : 
<img width="1665" height="890" alt="Screenshot 2026-01-22 101112" src="https://github.com/user-attachments/assets/a2730115-92b6-4e21-9b79-be3a63ab670f" />
# 📞 Contact :
<img width="1260" height="567" alt="Screenshot 2026-01-22 101343" src="https://github.com/user-attachments/assets/f3c606d0-66dc-4a3a-bbdd-19361cc63683" />
![Capture7](https://github.com/DulanjaliSenarathna/mern-food-delivery-app/assets/59603716/1a94b8aa-aa4e-4991-9d45-f6548f793b47)
# ❤️ Payment :
![Capture8](https://github.com/DulanjaliSenarathna/mern-food-delivery-app/assets/59603716/c85e4c11-7ebf-4e45-8678-4000abde835d)

## 📜 API Documentation
The API endpoints for the backend can be documented using tools like Postman or Swagger. Include endpoints for user authentication, menu items, orders, and more.

## 🤝 Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Make sure to follow the code style and include relevant tests.



## 👥 Contributors

**Gulam Mohiyuddin** — Project Owner & Full-Stack Developer


## 📫 Contact
For any questions or suggestions, feel free to contact me.

Happy coding!

Feel free to customize this template according to your specific project details and requirements.




