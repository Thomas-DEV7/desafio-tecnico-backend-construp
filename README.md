# 🏗️ Desafio Técnico – CRUD de Produtos | Construp

![Logo da Construp](https://www.construp.com.br/img/new-logo.bdeb3a22.png)

Este repositório apresenta a solução desenvolvida para o desafio técnico da **Construp**, cujo objetivo foi a construção de uma aplicação completa para gerenciamento de produtos utilizando **Laravel (Backend)** com integração à plataforma **Supabase** e **Vue.js (Frontend)**.

---

## 📌 Descrição do Desafio

O desafio consistia na implementação de uma aplicação full-stack com as seguintes funcionalidades principais:

- Criação de produto (nome, descrição, preço, imagem)
- Listagem de produtos com paginação
- Edição de dados de um produto
- Exclusão de produtos
- Interface responsiva e intuitiva

Requisitos adicionais:

- Integração com banco de dados Supabase
- API RESTful com autenticação (JWT ou outra)
- Separação clara entre frontend e backend

---

## ⚙️ Tecnologias Utilizadas

### Backend (API)
- Laravel 11 (PHP 8.3)
- Supabase (PostgreSQL)
- Laravel Sanctum (autenticação)
- Laravel Eloquent ORM
- Laravel Resource API
- PHPUnit (testes)

### Frontend
- Vue.js 3 (Composition API)
- Vue Router
- Axios
- Pinia (gerenciamento de estado)
- Tailwind CSS (estilização)

---

## 📁 Estrutura do Projeto

```plaintext
desafio-crud-construp/
├── backend-laravel/
│   ├── app/
│   ├── routes/
│   ├── tests/
│   └── ...
├── frontend-vue/
│   ├── src/
│   ├── public/
│   └── ...
├── docker-compose.yml
└── README.md
