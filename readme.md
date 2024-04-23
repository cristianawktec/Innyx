<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Instruções sobre a construção do sistema

Primeiros passos:

-Criando o projeto usando composer:
composer create-project laravel/laravel loja --prefer-dist

-Migrando o BD
php artisan make:migration create_product_table
nessa hora temos que editar o arquivo .env com os dados do servior do DB
continuamos com o comando: php artisan migrate

-Criando os Models
php artisan make:model Product

-Criando a autenticação
php artisan make:auth
onde vai gerar automaticamente a tela de registro/login

-Logando no sistema (servidor hostgator)
http://localhost/innyx
usuario: teste@gmail.com
senha: 123456
