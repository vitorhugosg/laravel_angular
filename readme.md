<div align="center">
  <h1>📦 Laravel Estoque API</h1>
  <p><strong>Estudo de uma API REST para controle de estoque.</strong></p>
  <p>Backend legado em Laravel 5.2 com autenticação de usuários.</p>
</div>

---

## ✨ Sobre o projeto

Este repositório contém o backend Laravel para uma aplicação de estoque. O nome também menciona Angular, mas o cliente Angular não está incluído na estrutura atual deste repositório.

## 🧰 Tecnologias

`PHP 5.5.9+` · `Laravel 5.2` · `API REST`

## 🚀 Como executar

> Laravel 5.2 é uma versão antiga. Use um ambiente PHP compatível com o `composer.json` deste projeto.

```bash
composer install
cp .env.example .env
php artisan key:generate
```

Configure o banco no `.env` e execute as migrations:

```bash
php artisan migrate
php artisan serve
```

Consulte `routes/` e `app/Http/Controllers/` para conhecer os endpoints disponíveis.
