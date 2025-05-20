# 🚀 FastAPI Todo List API  

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)  ![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)  

> ⚠️ Este repositório faz parte dos meus estudos em desenvolvimento backend com **Python**, **FastAPI**, **SQLAlchemy** e **SQLite**.

Este é um projeto simples de uma API para gerenciar tarefas (To-Do List), criado com o objetivo de praticar a construção de APIs RESTful utilizando FastAPI, modelagem com SQLAlchemy e persistência com SQLite.


## ✨ Funcionalidades  
- CRUD completo de tarefas  
- Validação de dados com Pydantic  
- Documentação automática (Swagger UI e Redoc)  
- Paginação na listagem de tarefas  


---

## 🔗 Endpoints principais

| Método | Endpoint         | Descrição                 |
|--------|------------------|---------------------------|
| GET    | `/todos/`        | Lista todas as tarefas    |
| POST   | `/todos/`        | Cria nova tarefa          |
| GET    | `/todos/{id}`    | Obtém uma tarefa por ID   |
| PUT    | `/todos/{id}`    | Atualiza uma tarefa       |
| DELETE | `/todos/{id}`    | Remove uma tarefa         |

---

## 🧩 Modelo de dados

### Tarefa (ToDo)

```json
{
  "id": 1,
  "title": "Fazer compras",
  "description": "Comprar itens essenciais",
  "completed": false
}

