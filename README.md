# Laravel with Firestore: A Comprehensive Guide

This repository contains the source code for how to build a fully functional CRUD (Create, Read, Update, Delete) application using Laravel, a powerful PHP framework, and Firebase Firestore, Google's flexible, scalable database service.

## Getting Started

To get started with the project, follow these steps:

1. Navigate to the project directory:

```bash
cd laravel-with-firebase
```

2. Install Composer dependencies:

```bash
composer install
```

3. Set up Firebase credentials:

    - Download the Firebase Admin SDK JSON file from your Firebase project settings.
    - Update the `.env` file with your Firebase project details.



4. Running with XAMPP or WAMP

   If you encounter any issues related to gRPC when running the project using the local terminal, you can alternatively run it using XAMPP or WAMP. Follow these steps:

 - Start your XAMPP or WAMP server.
 - Open the shell or command prompt provided by XAMPP or WAMP.
 - Navigate to the directory where you have installed XAMPP or WAMP.
 - Paste the path to your project directory in the shell or command prompt.

5. Run the Laravel development server:

```bash
php artisan serve
```