Wardrobe Management System

This is a Wardrobe Management System developed with Vue3 for the frontend and Laravel 11 for the backend.
Features

    User login and registration
    Add, modify, and remove clothing items
    Organize items into categories (e.g., tops, bottoms, shoes)
    Search and filter items
    Responsive and user-friendly interface

Prerequisites

Before you begin, make sure you have the following installed:

    Node.js
    Composer
    PHP
    Laravel

Installation Guide
Backend Setup (Laravel)

    Navigate to the backend directory:

cd backend

Install all required dependencies with Composer:

composer install

Duplicate the example environment file and generate the application key:

cp .env.example .env
php artisan key:generate

Update your database settings in the .env file.

Run the database migrations to set up the required tables:

php artisan migrate

Launch the Laravel development server:

    php artisan serve

Frontend Setup (Vue3)

    Move to the frontend directory:

cd frontend

Install the necessary dependencies using npm:

npm install

Start the Vue development server:

    npm run serve

Accessing the Application

    Open your browser and go to http://localhost:8080 to view the frontend.
    The backend API will be available at http://localhost:8000.