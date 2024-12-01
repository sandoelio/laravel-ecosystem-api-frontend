# laravel-ecosystem-api-frontend - Backend API e Frontend Completo

## 📋 Sobre o Projeto

Este é um **ecossistema Laravel** que explora as melhores práticas de desenvolvimento web modernas, utilizando o Laravel 10. O projeto é dividido em dois grandes módulos: **Backend** (API) e **Frontend**, ambos estruturados para aproveitar ferramentas e padrões avançados.  

**Principais Tecnologias e Recursos:**
- **Backend**:
  - Laravel 10
  - API Restful
  - Testes Unitários com PHPUnit
  - Autenticação JWT
  - DTO (Data Transfer Object)
  - Design Patterns
  - Docker para ambiente padronizado

- **Frontend**:
  - Blade para renderização no servidor
  - TailwindCSS para estilização moderna e responsiva
  - Integração com a API Backend

---

## ✨ Funcionalidades

### Backend (API)
- CRUD completo para gerenciamento de recursos.
- Autenticação e autorização via **JWT (JSON Web Token)**.
- Testes unitários e de integração utilizando **PHPUnit**.
- Design Patterns para organização e escalabilidade do código.
- Uso de **DTO** para transferências seguras e organizadas de dados.

### Frontend
- Renderização de páginas com **Blade**.
- Estilos modernos e responsivos com **TailwindCSS**.
- Comunicação com a API backend via **AJAX ou Axios**.

---

## 🛠️ Tecnologias Utilizadas

### Backend
- **Laravel 10**
- **PHPUnit** para testes
- **JWT Auth** para autenticação
- **Docker** para ambiente de desenvolvimento
- **Design Patterns (Repository Pattern)** e DTO
- **Redis** para Cache, Gerenciamento de sessões...

### Frontend
- **Blade** para renderização
- **TailwindCSS** para estilização
- **JavaScript** para interatividade
- **Axios** para consumo da API

---

## 🚀 Como Executar o Projeto

1. Clone o repositório:
    ```
    git clone https://github.com/sandoelio/laravel-ecosystem-api-frontend.git
    ```
2. Crie o Arquivo .env
    ```
    cp .env.example .env
    ```
3. Atualize essas variáveis de ambiente no arquivo .env
    ```
    APP_NAME="laravel-ecosystem-api-frontend"
    APP_URL=http://localhost:8989

    DB_CONNECTION=mysql
    DB_HOST=mysql
    DB_PORT=3306
    DB_DATABASE=nome_que_desejar_db
    DB_USERNAME=nome_usuario
    DB_PASSWORD=senha_aqui

    CACHE_DRIVER=redis
    QUEUE_CONNECTION=redis
    SESSION_DRIVER=redis

    REDIS_HOST=redis
    REDIS_PASSWORD=null
    REDIS_PORT=6379
    ```

4. Suba os containers do projeto
    ```
    docker-compose up -d
    ```
5. Acesse o container
    ```
    docker-compose exec app bash
    ```
6. Instale as dependências do projeto
    ```
    composer install
    ```
7. Gere a key do projeto Laravel
    ```
    php artisan key:generate
    ```
8. Acesse o projeto
[http://localhost:8989](http://localhost:8989)

# 📧 Contato
* Autor: Sandoelio Silva
* Email: sandoelio@hotmail.com
* LinkedIn: [Sandoelio Silva](https://www.linkedin.com/in/sandoelio-silva/)
