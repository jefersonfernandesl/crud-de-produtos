# CRUD de Produtos 🚀  

Este é um sistema de gerenciamento de produtos desenvolvido com **Laravel 11**, **PostgreSQL** e **jQuery**. O projeto permite realizar operações de **criação, leitura, atualização e exclusão (CRUD)** de produtos de forma dinâmica, sem a necessidade de recarregar a página, utilizando **AJAX**.  

## 🛠 Tecnologias Utilizadas  
- **Laravel 11** – Framework PHP para construção da API  
- **PostgreSQL** – Banco de dados relacional  
- **jQuery & AJAX** – Manipulação do DOM e requisições assíncronas  
- **Bootstrap** – Estilização e responsividade  
- **Docker** – Containerização para fácil deploy e desenvolvimento  

## ✨ Funcionalidades  
- ✅ Listagem de produtos dinâmica  
- ✅ Criação e edição de produtos via modal  
- ✅ Exclusão de produtos com confirmação  
- ✅ Máscara para o campo de preço  
- ✅ Validações no frontend e backend  
- ✅ Dockerização para ambiente de desenvolvimento  

## ⚙️ Como Rodar o Projeto  

### 🐳 Usando Docker  
1. Clone o repositório:  
   ```bash
   git clone https://github.com/jefersonfernandesl/crud-de-produtos.git
   cd crud-de-produtos

2. Suba os containers:
    ```bash
    docker-compose up -d
3. Acesse o container da aplicação:
    ```bash
    docker exec -it crud-app bash
4. Execute as migrations e seeders
    ```bash
    php artisan migrate --seed

5. Inicie o servidor:
   ```bash
   php artisan serve


### 🚀 Rodando sem docker  

1. Clone o repositório:  
   ```bash
   git clone https://github.com/jefersonfernandesl/crud-de-produtos.git
   cd crud-de-produtos
2. Instale as dependências:
   ```bash
   composer install
   npm install
3. Configure o .env e gere a chave da aplicação:
    ```bash
    cp .env.example .env
    php artisan key:generate
4. Configure o banco de dados no .env e rode as migrations:
    ```
    php artisan migrate --seed
5. Inicie o servidor:
    ```bash
    php artisan serve
6. Acesse no navegador
   ```bash
   http://localhost:8000

