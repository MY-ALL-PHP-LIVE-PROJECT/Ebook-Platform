# Ebook

## Project Overview
An e-book reading and selling platform.

## Technologies Used
PHP, MySQL, Bootstrap

## Features
- Ebook Library
- Purchase & Download
- Reading Interface
- Admin Panel

## Local Installation

### Prerequisites
- PHP 7.4+ / 8.x
- MySQL / MariaDB
- Web Server (Apache/Nginx) or XAMPP/WAMP

### Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/MY-ALL-PHP-LIVE-PROJECT/Ebook-Platform.git
   cd Ebook-Platform
   ```

2. **Database Setup**
   - Create a database in MySQL
   - Import the `.sql` file if provided
   - Update database credentials in the config file

3. **Configuration**
   - Update DB credentials in config

4. **Start the server**
   - For Laravel: `php artisan serve`
   - For CodeIgniter/Core PHP: Place in `htdocs` or `www` folder and start Apache

## Deployment
1. Upload all files to server (excluding `vendor/`, `node_modules/`)
2. Set proper file permissions for writable folders
3. Configure environment variables / config files with production values
4. Point web server document root to the `public/` directory (for Laravel)

## Organization
This project is part of the [MY-ALL-PHP-LIVE-PROJECT](https://github.com/MY-ALL-PHP-LIVE-PROJECT) collection.
