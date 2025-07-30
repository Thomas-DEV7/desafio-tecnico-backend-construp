# 🏗️ Backend – Desafio Técnico CRUD de Produtos | Construp

![Logo da Construp](https://www.construp.com.br/img/new-logo.bdeb3a22.png)

Este repositório contém a implementação do **backend** da aplicação desenvolvida para o **desafio técnico** da empresa **Construp**, utilizando o framework **Laravel 11**, com banco de dados **Supabase (PostgreSQL)**. A API fornece endpoints RESTful seguros e eficientes para manipulação de produtos, com suporte a autenticação via **Laravel Sanctum**.

---

## 📌 Descrição do Desafio

O desafio teve como objetivo construir uma API moderna para gerenciamento de produtos, com as seguintes funcionalidades:

- Cadastro de produtos (nome, descrição, preço, imagem)
- Listagem com paginação
- Edição de informações
- Exclusão de produtos
- Upload de imagens com Supabase Storage
- Autenticação para proteção de rotas

---

## 🧰 Tecnologias Utilizadas

- Laravel 11 (PHP 8.3)
- Supabase (PostgreSQL + Storage)
- Laravel Sanctum (autenticação)
- Laravel Eloquent ORM
- PHPUnit (testes)
- Docker e Docker Compose

---

## 📁 Estrutura do Projeto

```bash
backend/
├── app/
│   ├── Http/
│   ├── Models/
│   └── Services/
├── routes/
│   └── api.php
├── database/
│   └── migrations/
├── tests/
├── .env.example
└── docker-compose.yml
