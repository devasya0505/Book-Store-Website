# Online Bookstore

An online bookstore built with **HTML, CSS, JavaScript, and PHP**, featuring interactive browsing, a PHP backend for dynamic content, and a MySQL database. Users can browse books, view details, manage a shopping cart, and securely log in to their accounts. The project also includes an admin panel for managing books, orders, and users.


## Features

- Browse books by category or search for specific titles  
- View detailed information for each book, including price and description  
- Add and remove books from the shopping cart  
- Secure user login and registration (`login.php` and `register.php`)  
- Checkout system to place orders  
- Admin panel to manage books, orders, and users (optional if implemented)  
- JavaScript-powered interactivity for a better user experience  


## Project Exploration

The `login.php` page allows users to securely access their accounts. Combined with `register.php`, it ensures that only authenticated users can manage their cart and place orders. The project demonstrates a **full-stack web application workflow**:

1. **Front-end:** HTML, CSS, and JavaScript create the interface for browsing books, viewing details, and managing the cart.  
2. **Back-end:** PHP handles user authentication, order processing, and data retrieval from the MySQL database.  
3. **Database:** MySQL stores book information, user accounts, and order details.  
4. **Admin Panel:** Optional but included in the project to showcase content management capabilities.  

Overall, this project provides a **hands-on demonstration of integrating front-end interactivity with a PHP backend** to create a functional online bookstore.  


## Technologies Used

- **Front-end:** HTML, CSS, JavaScript  
- **Back-end:** PHP  
- **Database:** MySQL  


## Setup Instructions

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/your-repo.git

2. Move into the project folder:
    ```bash
    cd your-repo

3. Install a local server (XAMPP, WAMP, or MAMP).

4. Import `shop_db.sql` into MySQL.

5. Update `config.php` with your database credentials.

6. Open the project in your browser:
    ```bash
    http://localhost/your-repo/

## Folder Structure

```bash
/css        - Stylesheets
/js         - JavaScript files
/admin      - Admin panel pages
*.php       - Main website pages
shop_db.sql - Database backup file