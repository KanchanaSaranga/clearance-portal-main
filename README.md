<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>
# 🎓 Clearance Management System

A Laravel-based web application to streamline and automate the student clearance process at universities. This system enables students to request department-wise clearance and allows departments to manage, approve, or decline requests—all in one centralized platform.

![Laravel](https://img.shields.io/badge/Laravel-10.x-red?style=flat&logo=laravel)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue?style=flat&logo=mysql)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen.svg)

---

## 📌 Key Features

- ✅ Student registration & clearance request submission  
- 🏢 Department dashboards to approve/decline requests  
- 🔐 Role-based access (Admin, Department, Student)  
- 📊 Real-time status tracking  
- 📥 Excel student data import (via Laravel-Excel)  
- ✉️ Notification messages after actions  
- 🔒 Secure authentication with Laravel Breeze/Auth  

---

## 🧱 Tech Stack

- **Backend**: Laravel 10+
- **Frontend**: Blade, Bootstrap 5, CSS (#6699FF theme)
- **Database**: MySQL
- **Authentication**: Laravel Breeze / Laravel UI
- **Excel Import**: Maatwebsite Laravel-Excel

---

## 🚀 Installation

```bash
# Step 1: Clone the repo
git clone https://github.com/your-username/clearance-management.git
cd clearance-management

# Step 2: Install dependencies
composer install
npm install
npm run dev

# Step 3: Setup environment
cp .env.example .env
php artisan key:generate

# Step 4: Configure your .env file (DB credentials)

# Step 5: Run migrations and seeders
php artisan migrate --seed

# Step 6: Serve the application
php artisan serve

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[WebReinvent](https://webreinvent.com/)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Jump24](https://jump24.co.uk)**
- **[Redberry](https://redberry.international/laravel/)**
- **[Active Logic](https://activelogic.com)**
- **[byte5](https://byte5.de)**
- **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
