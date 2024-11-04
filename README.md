E-Commerce Website
This is an e-commerce website built with Django and integrated with PayPal for payments. The website includes product browsing, user authentication, shopping cart functionality, and order processing.


User Authentication: Register, log in, log out, and reset passwords.
Product Browsing: View product categories, product details, and filter products by categories.
Shopping Cart: Add items to the cart and adjust quantities.
Order Processing: Place orders, view order history, and track orders.
Payment Integration: PayPal API integration for secure online payments.
Responsive Design: Fully responsive layout for various devices.
Tech Stack
Frontend: HTML, CSS, JavaScript, Bootstrap
Backend: Django
Database: SQLite (for development)
Payment Gateway: PayPal API

Installation
Prerequisites
Python 3.10
Git
Virtual environment tool (optional, but recommended)


Steps
git clone https://github.com/bassy1992/e-commerce_alx_final.git
cd e-commerce_alx_final

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver


Usage
Home Page: Browse products and explore categories.
Account Management: Register or log in to your account, reset your password if needed.
Cart: Add products to the cart, adjust quantities, and view the cart summary.
Checkout: Proceed to checkout, review order details, and make payments using PayPal.

