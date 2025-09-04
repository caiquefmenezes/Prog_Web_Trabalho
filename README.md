# Projeto Programação Web

Este projeto é uma aplicação web Full Stack organizada em um único repositório, com **backend, frontend e banco de dados**, todos integrados via **Docker Compose**. 

---

## Tecnologias utilizadas

- **Frontend:** HTML, JavaScript  
- **Backend:** Node.js (Express)  
- **Banco de Dados:** SQL (via script `init.sql`)  
- **Infraestrutura:** Docker & Docker Compose  

---

## Estrutura do projeto

backend/
├─ Dockerfile        # Configuração do container do backend
├─ package.json      # Dependências Node.js
└─ server.js         # Código principal do servidor

frontend/
├─ Dockerfile        # Configuração do container do frontend
├─ app.js            # Lógica do frontend
└─ index.html        # Página inicial

db/
└─ init.sql          # Script para criar tabelas/dados iniciais

docker-compose.yml     # Arquivo de orquestração dos containers

---

## Como rodar o projeto

1. Clone este repositório:
bash
    git clone https://github.com/caiquefmenezes/Prog_Web_Trabalho
    cd Prog_Web_Trabalho

2.	Certifique-se de ter Docker e Docker Compose instalados.

3.	Inicie os serviços com:
    docker-compose up --build

4.	Acesse a aplicação:

	•	Frontend: http://localhost:8080
	•	Backend API: http://localhost:3000
	•	Banco de Dados: http://localhost:5432

Observações
	•	O backend e frontend estão prontos para uso local, sem necessidade de configuração extra.
	•	O banco de dados é inicializado automaticamente pelo script db/init.sql.

---

Caíque Menezes
Contato: caiqueluis03@gmail.com