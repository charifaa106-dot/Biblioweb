# BiblioWeb Installation Instructions

## Prerequisites
Make sure you have the following installed:
- PHP (>= 7.4)
- Composer
- Laravel Installer (optional, but recommended)
- A web server (Apache/Nginx)
- MySQL or MariaDB

## Step 1: Clone the Repository
Run the following command in your terminal:
```bash
git clone https://github.com/charifaa106-dot/Biblioweb.git
cd Biblioweb
```

## Step 2: Install Dependencies
Run Composer to install the project dependencies:
```bash
composer install
```

## Step 3: Configure the Environment
Copy the example environment file to create your own:
```bash
cp .env.example .env
```
Edit the `.env` file to set your database connection and other configurations:
```dotenv
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

## Step 4: Generate Application Key
Run the following command to generate the application key:
```bash
php artisan key:generate
```

## Step 5: Run Migrations
To create the necessary database tables, run:
```bash
php artisan migrate
```

## Step 6: Install NPM Packages
If you need to use front-end assets run:
```bash
npm install
```
```
## Step 7: Build Assets
Compile the assets using Laravel Mix:
```bash
npm run dev
```

## Step 8: Start the Server
Run the following command to start the Laravel development server:
```bash
php artisan serve
```

You can now access your application by visiting `http://localhost:8000` in your web browser.

## Conclusion
You have successfully installed the BiblioWeb project. For further customization and development, refer to the [Laravel Documentation](https://laravel.com/docs).
