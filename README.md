# 🧑‍💻 Projeto Vagas e Candidaturas

Aplicação fullstack para gerenciamento de vagas e candidaturas, composta por:

* **Backend:** Java + Spring Boot
* **Frontend:** React
* **Banco de dados:** PostgreSQL
* **Orquestração:** Docker + Docker Compose

---

## 🚀 Como rodar o projeto

### 📦 Pré-requisitos

* Docker instalado
* Docker Compose instalado

---

### ▶️ Subindo a aplicação

Na raiz do projeto (onde está o `docker-compose.yaml`), execute:

```bash
docker compose up --build
```

---

### ⏹️ Parar a aplicação

```bash
docker compose down
```

---

## 🌐 Acessos

Após subir os containers, você poderá acessar:

* 🖥️ **Frontend:**
  http://localhost:3000

* ⚙️ **Backend (API):**
  http://localhost:8080

* 📚 **Swagger (documentação da API):**
  http://localhost:8080/swagger-ui/index.html

---

## 🧱 Estrutura do projeto

```
.
├── docker-compose.yaml
├── api-vagas-e-candidaturas/   # Backend (Spring Boot)
└── front-vagas-e-candidaturas/ # Frontend (React)
```

---

## ⚙️ Observações

* O backend está configurado para conectar no PostgreSQL via Docker.
* O frontend consome a API via `http://localhost:8080`.
* As portas utilizadas são:

  * `3000` → Frontend
  * `8080` → Backend
  * `5433` → PostgreSQL

---

## 🛠️ Tecnologias utilizadas

* Java 21
* Spring Boot
* React
* PostgreSQL
* Docker

---

## 📌 Autor

Projeto desenvolvido por Lucas Ferreira.

