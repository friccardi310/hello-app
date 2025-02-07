# Laravel Hello App

This is a simple Laravel application that displays "Hello, [Your Name!]" when accessed.

## Requirements
- PHP 8.1 or higher
- Composer
- MySQL (if database is needed)
- Laravel 10 (installed via Composer)

## Installation

1. **Clone the repository (if applicable)**
   ```sh
   git clone https://github.com/friccardi310/hello-app.git
   cd hello-app
   ```

2. **Install Dependencies**
   ```sh
   composer install
   ```

3. **Create Environment File**
   ```sh
   cp .env.example .env
   ```

4. **Generate Application Key**
   ```sh
   php artisan key:generate
   ```

5. **Start the Development Server**
   ```sh
   php artisan serve
   ```

6. **Access the Application**
   Open your browser and go to:
   ```
   http://127.0.0.1:8000/
   ```
   You should see:
   ```
   Hello, [Your Name!]
   ```

## Additional Commands

- **Clear Cache:**
  ```sh
  php artisan cache:clear
  ```

- **Migrate Database (if applicable):**
  ```sh
  php artisan migrate
  ```

- **Run Tests:**
  ```sh
  php artisan test