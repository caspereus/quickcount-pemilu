# QuickCount Pemilu

QuickCount Pemilu is a simple polling and election vote counting application built with [Laravel](https://laravel.com?utm_source=chatgpt.com).
This project allows users to participate in polls, monitor voting results, and display quick election statistics through a clean and responsive interface.

## Features

* Public voting system
* Real-time result calculation
* Candidate polling dashboard
* Vote percentage statistics
* Responsive interface
* Simple Laravel backend architecture
* Admin-ready structure

## Tech Stack

* PHP
* Laravel
* Blade Template
* MySQL
* JavaScript
* HTML/CSS
* Vite

## Installation

Clone the repository:

```bash
git clone https://github.com/caspereus/quickcount-pemilu.git
```

Move into the project directory:

```bash
cd quickcount-pemilu
```

Install dependencies:

```bash
composer install
npm install
```

Copy environment file:

```bash
cp .env.example .env
```

Generate application key:

```bash
php artisan key:generate
```

Configure your database inside `.env`

Run migration:

```bash
php artisan migrate
```

Run development server:

```bash
php artisan serve
npm run dev
```

## Project Structure

```bash
app/            # Application core
routes/         # Application routes
resources/      # Blade templates and frontend assets
public/         # Public assets
database/       # Database migration and seeder files
config/         # Application configuration
```

## Goals

This project was built to provide:

* Simple online polling experience
* Fast vote aggregation
* Easy deployment
* Lightweight election monitoring system

## Future Improvements

* Authentication & admin management
* Multi-poll support
* Better analytics dashboard
* Export polling results
* Improved mobile experience
* Public API support

## License

This project is open-sourced under the MIT License.
