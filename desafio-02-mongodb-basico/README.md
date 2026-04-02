# 🚀 Desafio 02 — MongoDB básico

Neste desafio você irá migrar a lógica de CRUD para um banco NoSQL, entendendo como documentos e coleções funcionam na prática.

## 🎯 Objetivo do Desafio

Criar uma API para gerenciamento de tarefas usando MongoDB que:

- cria documentos;
- lista e filtra tarefas;
- atualiza status;
- remove tarefas.

## 🧠 Tecnologias que você irá praticar

- Node.js
- MongoDB
- Coleções e documentos
- Operadores de consulta (`$eq`, `$in`, `$regex`)
- API REST
- Validação de payload

## 📦 Escopo funcional (MVP)

Entidade `tasks` com campos:

- `_id`
- `title` (obrigatório)
- `description` (opcional)
- `status` (`pending`, `in_progress`, `done`)
- `tags` (array)
- `createdAt`

Endpoints esperados:

- `POST /tasks`
- `GET /tasks`
- `PATCH /tasks/:id/status`
- `DELETE /tasks/:id`

## 🛠 Requisitos técnicos

- Conectar ao MongoDB via variável de ambiente.
- Validar entrada e status permitido.
- Padronizar respostas de erro.
- Implementar filtro por `status` e `tag`.

## ✅ Critérios de aceite

- Operações CRUD funcionando com persistência em documentos.
- Filtros retornando resultados corretos.
- Estrutura de código organizada e legível.

## ⭐ Parte opcional

- Busca textual por título.
- Soft delete com campo `deletedAt`.

## 🏁 Resultado esperado

Ao concluir este desafio, você terá domínio inicial de modelagem e consultas em MongoDB para APIs backend.

## 🚀 Próximo desafio

No próximo desafio você irá construir uma API com NestJS e arquitetura modular.
