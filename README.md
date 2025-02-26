# SaaS Authentication Service Publico

Uma aplicação de autenticação multi-tenant (SaaS) para gerenciar logins de múltiplos clientes (empresas) e suas aplicações, construída com **.NET 8 Minimal API** e **Entity Framework**. Permite que empresas registrem suas aplicações e gerenciem usuários de forma isolada, com autenticação JWT e identificação de tenant/aplicação. <br>
**observações**: essa e a arquitetura inicial da aplicação o desenvolvimento real acontece no repositorio privado. Acompanhe as issues no final desse arquivo.

---

## 🚀 Funcionalidades

- **Multi-tenancy**: Cada empresa (tenant) tem um identificador único.
- **Gerenciamento de Aplicações**: Cada tenant pode registrar múltiplas aplicações (clientes) com `ClientId` e `ClientSecret`.
- **Multi-Usuários**: Usuários registrados são vinculados a uma aplicação específica.
- **Autenticação JWT**: Tokens incluem claims de `TenantId` e `ApplicationId` para contexto de autenticação.
- **Escalável**: Arquitetura pronta para expansão com roles, permissões e provedores externos (OAuth2, Google, etc.).

---

## 🛠️ Tecnologias Utilizadas

- **.NET 8**: Para construção da API.
- **Entity Framework Core**: ORM para gerenciamento do banco de dados.
- **JWT (JSON Web Tokens)**: Autenticação segura e stateless.
- **BCrypt**: Hash seguro para senhas.
- **SQL Server**: Banco de dados principal (pode ser substituído por PostgreSQL, MySQL, etc.).
- **Swagger (Opcional)**: Documentação da API.

---

## 📦 Instalação

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/saas-login-service-publico.git
   cd saas-login-service

## Quantidades de xícara de café consumidas nesse projeto. [issues]
<!-- PR_ENTRIES -->
