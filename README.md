<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Template for multi auth with roles and permissions

In this 'template' there are two routes one for user and other for admin both with different dashboards. Herein i have user breeze package for authentication for both normal user and admin users. I have created guard for normal user and used default guard for admin users. Also made middleware for normal users and default middleware for admin users. Admin user is able to manage roles and permission with the help of stapie roles and permissions package. 

## For testing 
1. clone the project https://github.com/PS213073/laravel-multi-auth.git
2. Composer Update
3. Create new .env file 
4. php artisan migrate:fresh --seed
5. Npm run dev
6. php artisan serve
