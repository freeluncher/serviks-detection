<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Serviks Detection (Laravel + Flask)

[![Laravel](https://img.shields.io/badge/Laravel-Framework-red)](https://laravel.com/)
[![Python Flask](https://img.shields.io/badge/Flask-Python-blue)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/github/license/yourusername/serviks-detection)](LICENSE)
[![Issues](https://img.shields.io/github/issues/yourusername/serviks-detection)](https://github.com/yourusername/serviks-detection/issues)

## Deskripsi
Serviks Detection adalah aplikasi web untuk pemeriksaan dan diagnosa serviks berbasis Laravel (backend & frontend) dan Flask (API Machine Learning). Aplikasi ini mendukung:
- Manajemen data pasien
- Upload dan validasi gambar serviks
- Diagnosa otomatis menggunakan model machine learning
- Manajemen user multi-role (admin, dokter, user)
- Fitur edit profil, upload foto profil, dan riwayat diagnosa

## Fitur Utama
- **Pemeriksaan Serviks**: Upload gambar serviks, validasi ukuran, dan diagnosa otomatis.
- **Manajemen Pasien**: Tambah, edit, dan lihat data pasien serta riwayat diagnosa.
- **User Management**: Role-based access (admin, dokter, user), edit profil, dan upload foto profil.
- **Integrasi Flask API**: Model ML untuk prediksi kanker serviks.

## Teknologi
- Laravel 10+ (PHP)
- Python Flask (API ML)
- Bootstrap 5, OpenCV.js (frontend)
- SQLite/MySQL (database)

## Instalasi
1. Clone repo ini
2. Jalankan `composer install` dan `npm install`
3. Copy `.env.example` ke `.env` dan atur konfigurasi
4. Jalankan migrasi: `php artisan migrate --seed`
5. Jalankan server Laravel: `php artisan serve`
6. Jalankan Flask API: `cd flask_api && pip install -r requirements.txt && python app.py`

## Kontribusi
Pull request dan issue sangat terbuka untuk pengembangan lebih lanjut.

## Lisensi
MIT

---
> Aplikasi ini dikembangkan untuk membantu deteksi dini kanker serviks berbasis teknologi AI dan web modern.

<!--
## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

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
-->
