# FashionablyLate Contact-form

## Dockerビルド
- git clone git@github.com:yo003002/contact-form.git
- docker-compose up -d --build

## Laravel環境構築
- docker-compose exec php bash
- composer install
- cp .env.example .env  環境変数を変更
- php artisan key:generate
- php artisan migrate
- php artisan db:seed

## 開発環境

## 使用技術（実行環境）
- PHP 8.1.33
- Laravel 8.83.8
- MYSQL 11.8.3
- nginx 1.21.1

## ER図