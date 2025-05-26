# Bookstore Application

This is a Laravel-based web application for managing a bookstore. It provides features for managing books, users, and other related entities. The application is built with modern web development practices and includes a robust backend, a clean frontend, and a database for persistent storage.

---

## 📺 Demo Video

<div align="center">
  
[![Book Store Laravel Demo](https://github.com/noobdevsam/book-store-laravel-project/blob/master/resources/Screenshot2025-05-22.png)](https://youtu.be/N_dYUSjGeeg)

</div>

> _Click the image above to watch the demo on YouTube!_


---

## Features
- Manage books (CRUD operations)
- User authentication and management
- Database seeding and migrations
- Unit and feature testing with Pest
- Asset bundling with Vite

## Project Structure
- **app/**: Contains the core application logic, including models, controllers, and service providers.
- **bootstrap/**: Initializes the framework and loads configuration files.
- **config/**: Configuration files for various services and features.
- **database/**: Database migrations, seeders, and factories.
- **public/**: Publicly accessible files, including the entry point (`index.php`).
- **resources/**: Frontend assets like CSS, JavaScript, and Blade templates.
- **routes/**: Application routes defined in `web.php` and `console.php`.
- **storage/**: Storage for logs, cached views, and other generated files.
- **tests/**: Unit and feature tests.
- **vendor/**: Composer dependencies.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd bookstore
   ```
3. Install dependencies:
   ```bash
   composer install
   npm install
   ```
4. Set up the environment file:
   ```bash
   cp .env.example .env
   ```
   Update the `.env` file with your database and other configuration details.

5. Run database migrations and seeders:
   ```bash
   php artisan migrate --seed
   ```
6. Start the development server:
   ```bash
   php artisan serve
   ```

## Testing
Run the test suite using Pest:
```bash
./vendor/bin/pest
```

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is open-source and available under the [MIT License](LICENSE).