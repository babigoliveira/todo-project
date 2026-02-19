# 📝 ToDo Project - Full Stack App

Aplicação Full Stack de gerenciamento de tarefas (To-Do List), com autenticação JWT, interface moderna com React + Tailwind, back-end em Node (Bun), testes automatizados e conteinerização com Docker.

> Desenvolvido por [Bárbara Oliveira](https://github.com/babigoliveira)


## 🚀 Funcionalidades

- ✅ Autenticação via JWT
- ✅ CRUD de tarefas (criar, listar, editar e excluir)
- ✅ Estilizado com Tailwind CSS
- ✅ Testes automatizados no front-end e back-end
- ✅ Containerização com Docker e orquestração via docker-compose
- ✅ Projeto dividido por submódulos (`frontend`, `backend`)

---

## 🧱 Tecnologias utilizadas

### Front-End (Next.js)

- React + Next.js + TypeScript
- Tailwind CSS
- Context API
- Jest + React Testing Library

### Back-End (Bun/Node)

- Bun + TypeScript
- Express 
- JWT para autenticação
- Testes com Bun Test

### Outros

- Docker + Docker Compose
- Git + GitHub + Submódulos

---

## 🧪 Como rodar o projeto localmente

### Pré-requisitos

- Git
- Docker e Docker Compose

### Passos

1. **Clone o repositório principal com submódulos**:

```bash
git clone --recurse-submodules https://github.com/babigoliveira/todo-project.git
cd todo-project
```
2. **Instale as dependências dos submódulos:**

- No backend:
```bash
cd todo-backend
bun install
```
- No frontend:

```bash
cd todo-frontend
npm install
```
3. **Executar localmente sem Docker (opcional):**

- Rodar backend:

```bash
cd backend
bun run server.ts
```
- Rodar frontend:
```bash
cd frontend
npm run dev
```

4. **Executar com Docker e Docker Compose (recomendado):**

- Na raiz do projeto, rode:

```bash
docker-compose up --build
```

*Isso irá construir e iniciar os containers do backend e frontend.*

5. **Acessar a aplicação:**

Frontend estará disponível em:
http://localhost:3000

Backend estará disponível em:
http://localhost:33333 

