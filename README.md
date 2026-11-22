# Laravel Web Security

A Laravel (PHP) web application built for the **Web & Security Technologies** course (2025). It provides user management, a question bank and grade management, with authentication and secure-coding practices.

## Structure
The application lives in [`Project/`](Project): controllers in `app/Http/Controllers` (`UserController`, `QuestionController`, `GradeController`) and routes in `routes/`.

## Run
```bash
cd Project
composer install
cp .env.example .env && php artisan key:generate
php artisan migrate
php artisan serve
```