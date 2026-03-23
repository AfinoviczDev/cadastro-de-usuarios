# 👤 Cadastro de Usuários

API REST desenvolvida em **Java** para gerenciamento de usuários, permitindo operações completas de **CRUD (Create, Read, Update, Delete)**.

O projeto foi estruturado seguindo **boas práticas de desenvolvimento backend** e **arquitetura em camadas**, visando organização, escalabilidade e facilidade de manutenção.

---

## 🚀 Tecnologias utilizadas

- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- Banco de dados **H2 (em memória)**
- Maven

---

## 📌 Funcionalidades

- Cadastro de usuários
- Listagem de usuários
- Busca de usuário por ID
- Atualização de dados do usuário
- Remoção de usuários
- Persistência de dados com **JPA**
- Validações básicas de entrada

---

## 🏗️ Arquitetura

O projeto segue o padrão de **arquitetura em camadas**, dividido em:

- **Controller** → Responsável pelas requisições HTTP
- **Service** → Contém as regras de negócio
- **Repository** → Comunicação com o banco de dados
- **Entity** → Representação dos dados

---

## 🗄️ Banco de Dados

- Utiliza **H2 Database (em memória)**
- Console disponível em:  
  `http://localhost:8080/h2-console`

---

## ▶️ Como executar o projeto

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git

# Entrar na pasta do projeto
cd nome-do-projeto

# Executar a aplicação
./mvnw spring-boot:run
