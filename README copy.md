## Requisitos

* PHP 8.2 ou superior
* MySQL 8 ou superior
* Composer

## Como rodar o projeto baixado


## Sequencia para criar o projeto
Criar o projeto com Laravel
```
composer create-project laravel/laravel .
```

Alterar no arquivo .env as credenciais do banco de dados<br>

Criar o arquivo de rotas para API
```
php artisan install:api
```

Iniciar o projeto criado com Laravel
```
php artisan serve
```

Para acessar a API, é recomendado utilizar o Insomnia para simular requisições à API.
```
http://127.0.0.1:8000/api/user
```
