# 🧩 Projeto: Lista de Tarefas 06 — Spring Boot + Vue.js + CORS

**Autor:** José Augusto Francisco  
**Curso:** Análise e Desenvolvimento de Sistemas — 2º ADS  
**Disciplina:** Linguagem de Programação / POO  
**Atividade:** Lista de Tarefas 06 — Spring Boot + Vue.js + CORS  
**Tipo:** Atividade individual

---

## 🎯 Objetivo do Projeto

O objetivo deste projeto é desenvolver uma aplicação **Web Full Stack** integrando **Spring Boot (backend)** e **Vue.js (frontend)**.  
A aplicação tem como finalidade gerenciar uma lista de tarefas (_to-do list_), permitindo visualizar, adicionar, editar e remover tarefas.

Durante o desenvolvimento, foi proposto um **erro proposital de CORS (Cross-Origin Resource Sharing)** no backend, que impede o carregamento dos dados iniciais (_seed data_) pelo frontend.  
A tarefa consiste em identificar, corrigir e documentar a solução.

---

## ⚙️ Tecnologias Utilizadas

### 🖥️ Backend — Spring Boot

- Java 24
- Spring Boot 3.x
- Maven
- Lombok (opcional, para reduzir código boilerplate)

### 🌐 Frontend — Vue.js

- Vue 3
- Vite
- Axios (para chamadas à API)
- Node.js + npm

---

## 🧱 Estrutura do Projeto

Lista_de_Tarefas_06/
|-- backend/ → Projeto Spring Boot (API REST)
│ |-- src/
│ |-- pom.xml
│ |-- README-backend.md
|-- frontend/ → Projeto Vue.js (Interface Web)
│ |-- src/
│ |-- package.json
│ |-- README-frontend.md
|-- README.md → Documento principal do projeto (este arquivo)

---

## 🚀 Como Importar e Executar o Projeto

### ✅ Pré-requisitos

Antes de começar, verifique se você possui instalado:

- **Java JDK 24** (ou superior)
- **Maven 3.8+** (configurado no PATH)
- **Node.js 16+** e **npm**
- **IDE compatível com Spring Boot** (como IntelliJ IDEA, Eclipse ou VS Code)
- **Plugin do Lombok** habilitado (caso use Lombok)

---

### 🔧 1. Clonar o Repositório

Abra o terminal e execute:

```
git clone <URL-do-repositório>
cd Lista_de_Tarefas_06
```

---

Abra outro terminal e entre na pasta frontend:
`cd frontend`
Instale as dependências do projeto:
`npm install`

Inicie o servidor de desenvolvimento:
`npm run dev`

O frontend estará disponível em:
`http://localhost:5173`
