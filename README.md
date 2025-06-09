# sistema-ordem-servico
O objetivo desse repositório é a organização do teste técnico que estou participando.

# Sistema de Ordem de Serviço

Este projeto é uma aplicação web desenvolvida como parte de um teste técnico para a vaga de Programador Pleno. O sistema simula o fluxo de abertura de ordens de serviço, incluindo funcionalidades de autenticação, CRUD de clientes e produtos, e registro de logs.

## 🧰 Tecnologias Utilizadas

- **Back-end:** PHP (Orientado a Objetos, API RESTful)
- **Front-end:** HTML, JavaScript, jQuery, Bootstrap
- **Banco de Dados:** PostgreSQL ou MySQL
- **Controle de Versão:** Git
- **Autenticação:** JWT (JSON Web Tokens)
- **Documentação da API:** Swagger (ou equivalente)

## 🚀 Como Executar o Projeto

### 1. Clone o Repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### 2. Configure o Ambiente

- Crie um banco de dados MySQL ou PostgreSQL.
- Renomeie `.env.example` para `.env` e configure as variáveis de ambiente.
- Instale as dependências necessárias via Composer:
```bash
composer install
```

### 3. Execute as Migrações (caso esteja usando algum framework)

```bash
php artisan migrate
```
> *ou crie manualmente com base no diagrama abaixo.*

### 4. Inicie o Servidor Local

```bash
php -S localhost:8000 -t public
```

### 5. Teste a Aplicação

- Acesse `http://localhost:8000` no navegador.
- Utilize ferramentas como Postman para testar as rotas protegidas com JWT.

## 📦 Funcionalidades Implementadas

- [x] CRUD de Clientes com validação de CPF
- [x] CRUD de Produtos com filtros e buscas
- [x] CRUD de Ordem de Serviço
- [x] Cadastro automático de cliente na OS
- [x] Registro de logs de alterações
- [x] Autenticação com JWT e controle de acesso por função (admin, usuário)
- [x] Proteção contra SQL Injection e XSS
- [x] Testes unitários e de integração
- [x] Documentação da API

## 🧪 Testes

Os testes estão localizados na pasta `/tests`. Para rodá-los, utilize:

```bash
phpunit
```

## 🧾 Diagrama do Banco de Dados

![Diagrama do Banco de Dados](./docs/Captura%20de%20Tela%202025-06-09%20a%CC%80s%2016.27.34.png)

## ✍️ Autor

**Rafael Ribeiro**  
Data: 9 de Junho de 2025
