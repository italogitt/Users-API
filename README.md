# Users API

API REST simples para gerenciamento de usuários desenvolvida com Node.js.  
O projeto foi criado com o objetivo de praticar conceitos de **backend**, **CRUD** e integração com banco de dados.

A API permite criar, listar, atualizar e deletar usuários, seguindo o padrão de **APIs REST**, que utilizam métodos HTTP como GET, POST, PUT e DELETE para manipular recursos. :contentReference[oaicite:0]{index=0}

---

# 🚀 Tecnologias utilizadas

- Node.js
- Express
- Prisma ORM
- MongoDB

---

# 📦 Funcionalidades

- Criar usuários
- Listar usuários
- Filtrar usuários por nome
- Atualizar informações de um usuário
- Deletar usuários

---

# 📌 Endpoints da API

### Criar usuário

POST `/usuarios`

Exemplo de body:

```json
{
  "name": "João",
  "email": "joao@email.com",
  "age": 25
}
