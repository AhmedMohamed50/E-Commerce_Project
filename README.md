# E-Commerce Website
this is a HTML, CSS and JS e-commerce project in ITI Internship

# Project Overview
This is a simple e-commerce web application that allows users to view products, add them to their cart, and proceed to checkout. The project also includes a sign-up and login system, with data stored in the browser's localStorage. Basic form validation ensures that users enter valid information, including phone numbers and emails, for registration and checkout.

# Features
1. Product Listing: Users can browse through a list of products displayed on the homepage.
2. Cart Functionality: Users can add products to their cart, update the quantity, and remove items.
3. Sign-Up & Login: Users can sign up with their first name, email (with @iti.com validation), and password. They can log in using the stored credentials.
4. Checkout: Once the user is logged in, they can proceed to checkout.
5. LocalStorage Integration: User sign-up data and cart data are stored in localStorage to persist across page reloads.
6. Form Validation: The project includes validation for email, password, and phone number formats to ensure data integrity.

# Installation
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/yourusername/simple-ecommerce-project.git
Navigate to the project directory:
bash
Copy code
cd simple-ecommerce-project
Open the index.html file in your browser to start using the application.
Usage
Product Listing
On the homepage, you can see a list of products. Click the Add to Cart button to add products to your shopping cart.
Cart
Click the cart icon in the top-right corner to view your cart. You can update the quantity of items or remove them from your cart.
Sign-Up & Login
On the sign-up page, enter your first name, an email with the format *@iti.com, and a password to register.
Once registered, you can log in with the same email and password.
Checkout
After logging in, you can proceed to checkout from the cart page. This will display an alert confirming the checkout process.
Validation Rules
Email: Must end with @iti.com.
Password: Must be at least 8 characters long.
Phone Number: Must follow a valid phone number format.
Folder Structure
index.html: Homepage with product listings.
login.html: Login form.
signup.html: Sign-up form with validation.
cart.html: Cart page displaying added items.
style.css: Basic styling for the pages.
script.js: Main JavaScript file handling product and cart operations.
products.json: A JSON file that simulates product data.
Future Improvements
Add a backend to handle product storage, user authentication, and order management.
Enhance UI design for a better user experience.
Implement payment gateway integration for real purchases.
Contributing
Feel free to fork this project and submit pull requests. Any feedback or feature requests are welcome.
# Features
1. home page for 
