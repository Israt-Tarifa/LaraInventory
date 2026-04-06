# LaraProductHub - Inventory Management System

LaraProductHub is a lightweight and efficient Inventory Management System built with the **Laravel** framework. This application allows users to manage a product catalog through a secure dashboard, featuring full CRUD (Create, Read, Update, Delete) functionality.

## 🛠 Features

-   **User Authentication:** Secure registration and login system to protect sensitive inventory data.
-   **Product Management (CRUD):** -   View a comprehensive list of products.
    -   Add new products with specific details.
    -   Edit and update existing product information.
    -   Remove products from the database.
-   **Server-Side Validation:** Ensures data integrity and prevents invalid entries.
-   **Clean UI:** Built using Laravel Blade templates with a responsive design for various screen sizes.

## 🚀 Tech Stack

-   **Backend:** Laravel 11.x
-   **Language:** PHP 8.2+
-   **Database:** MySQL
-   **Frontend:** Blade Template Engine, Bootstrap/Tailwind CSS

## 💻 Installation Guide

Follow these steps to set up the project locally:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/LaraProductHub.git](https://github.com/your-username/LaraProductHub.git)
    cd LaraProductHub
    ```

2.  **Install Dependencies:**
    ```bash
    composer install
    ```

3.  **Environment Setup:**
    Create a copy of the `.env` file and configure your database settings:
    ```bash
    cp .env.example .env
    ```
    *Open the `.env` file and update `DB_DATABASE`, `DB_USERNAME`, and `DB_PASSWORD`.*

4.  **Generate Application Key:**
    ```bash
    php artisan key:generate
    ```

5.  **Run Migrations:**
    ```bash
    php artisan migrate
    ```

6.  **Start the Application:**
    ```bash
    php artisan serve
    ```
    *Access the app at `http://127.0.0.1:8000`*

## 📂 Project Structure Highlights

-   **ProductController.php:** Handles the core business logic for product operations.
-   **HomeController.php:** Manages the authenticated user's dashboard view.
-   **Resources/Views:** -   `index.blade.php`: The main product listing page.
    -   `create.blade.php` & `edit.blade.php`: Forms for adding and modifying data.
    -   `login.blade.php` & `register.blade.php`: Authentication interfaces.


