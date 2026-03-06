# BiblioWeb

## Installation Instructions

1. Clone the repository:
   ```
   git clone https://github.com/charifaa106-dot/Biblioweb.git
   cd Biblioweb
   ```

2. Install dependencies:
   ```
   composer install
   ```

3. Copy the environment file:
   ```
   cp .env.example .env
   ```

4. Generate application key:
   ```
   php artisan key:generate
   ```

5. Set up the database in your .env file.

6. Run migrations:
   ```
   php artisan migrate
   ```

7. Serve the application:
   ```
   php artisan serve
   ```
