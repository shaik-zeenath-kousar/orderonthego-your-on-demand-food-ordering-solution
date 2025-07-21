[# Food-Ordering-App-MERNSTACK
Demo - <a href="https://drive.google.com/file/d/1DLog3a51djjwvSNz1WrkB0uMwp-8e3c1/view?usp=drivesdk">VIEW VIDEO</a>


Documentation -<a href="https://docs.google.com/document/d/1aSGhfxFfMYMJChknR-pL47FW-idnhj2F/edit?usp=sharing&ouid=107917445781301743104&rtpof=true&sd=true">VIEW DOCUMENTATION </a>


PPT -<a href="https://www.canva.com/design/DAGr73dEvwY/SHf8qVJavnbW1fiQh3uewg/view?utm_content=DAGr73dEvwY&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h77f2db05c4">VIEW PPT</a>




# Project Files Structure
Order-On-The-Go/

├── Client/

│   ├── public/

│   │   ├── index.html

│   │   ├── manifest.json

│   │   └── robots.txt

│   ├── src/

│   │   ├── Pages/

│   │   │   ├── admin/

│   │   │   │   ├── Admin.jsx

│   │   │   │   ├── AllOrders.jsx

│   │   │   │   ├── AllProducts.jsx

│   │   │   │   └── AllRestaurants.jsx

│   │   │   │   └── AllUsers.jsx

│   │   │   ├── customer/

│   │   │   │   ├── CategoryProducts.jsx

│   │   │   │   ├── IndividualRestaurant.jsx

│   │   │   │   ├── Profile.jsx

│   │   │   │   └── cart.jsx

│   │   │   ├── restaurant/

│   │   │   │   ├── Authentication.jsx

│   │   │   │   └── Home.jsx

│   │   ├── components/

│   │   │   ├── Navbar.jsx

│   │   │   ├── PopularRestaurant.jsx

│   │   │   ├── Register.jsx

│   │   │   ├── Restaurants.jsx

│   │   │   ├── footer.jsx

│   │   │   └── login.jsx

│   │   ├── context/

│   │   │   └── GeneralContext.js

│   │   ├── App.js

│   │   ├── App.test.js

│   │   ├── index.css

│   │   ├── index.js

│   │   ├── reportWebVitals.js

│   │   └── setupTests.js

│   ├── package.json

│   └── package-lock.json

│

├── Server/

│   └── (Spring Boot backend files: src/, controllers/, models/, etc.)

│

└── README.md

](https://github.com/shaik-zeenath-kousar/orderonthego-your-on-demand-food-ordering-solution/tree/main/Client)


# 🍽️ Order-On-The-Go

**Order-On-The-Go** is a convenient and fast way to place orders for food/products on the go. This system allows users to browse products, make purchases, and track orders — all from their mobile or desktop devices.  
The platform is designed to improve the speed and efficiency of ordering for both users and vendors.

---

## ✨ Features

- 🛍️ **Browse Products/Services**: Users can view a catalog of available items.  
- 🛒 **Add to Cart**: Users can add items to their cart before checkout.  
- 🔐 **Secure Checkout**: Users can safely enter payment details and finalize orders.  
- 📦 **Order History**: Users can view and repeat previous orders easily.  
- 🧑‍💼 **Admin Dashboard**: Vendors can manage inventory, orders, and product listings.  

---

## 🛠️ Technologies Used

### 🌐 **Frontend**
- HTML, CSS, JavaScript  
- *(Or React / Vue if using frameworks)*

### 🖥️ **Backend**
- Node.js / Express  
- *(Or Python with Flask / Django)*

### 🗃️ **Database**
- MySQL / PostgreSQL  
- *(Or NoSQL: MongoDB if applicable)*

### 🔐 **Authentication**
- JWT / OAuth 2.0

### 💳 **Payment Integration**
- Stripe / PayPal / Razorpay *(depending on implementation)*

---

## 🧑‍💻 Getting Started

Follow these steps to set up the project on your local machine.

### ✅ Prerequisites

- Node.js or Python installed  
- MySQL/PostgreSQL (or MongoDB)  
- A code editor like **VS Code**

---

## 📥 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/PavithraVema/Order-On-The-Go.git
cd Order-On-The-Go

##2. Install Dependencies****
For Node.js
bash
Copy
Edit
npm install
For Python (Flask/Django)
bash
pip install -r requirements.txt
##3. Setup the Database
For MySQL/PostgreSQL
CREATE DATABASE order_on_the_go;
##4. Run the Application
For Node.js
npm start

🌐 Usage
🔐 Sign Up / Log In to the system.

🔎 Browse items from the home page or filter by category.

🛒 Add to Cart and review your order.

💳 Checkout and complete payment.

📄 Track Orders and view history in your account section.
## 📁 Project Files Structure
