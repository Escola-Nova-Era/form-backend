# 🚀 Desafio 07 — Rede social (MongoDB)

Neste desafio você irá construir a base de uma mini rede social usando documentos e relações referenciadas.

## 🎯 Objetivo do Desafio

Criar uma API com usuários, posts e comentários, explorando consultas e agregações em MongoDB.

## 🧠 Tecnologias que você irá praticar

- MongoDB
- Modelagem embutida e referenciada
- Aggregation Pipeline
- Operadores de array
- API REST

## 📦 Escopo funcional (MVP)

Endpoints mínimos:

- `POST /users`
- `POST /posts`
- `POST /posts/:id/comments`
- `GET /feed`

Dados esperados:

- Usuário: nome, username
- Post: autor, conteúdo, hashtags
- Comentário: autor, texto, data

## 🛠 Requisitos técnicos

- Definir estratégia de modelagem para comentários.
- Criar feed ordenado por data.
- Permitir filtro por hashtag no feed.
- Validar campos obrigatórios.

## ✅ Critérios de aceite

- Fluxo de publicação e comentário funcionando.
- Feed retornando posts com metadados úteis.
- Consultas performáticas para volume moderado.

## ⭐ Parte opcional

- Curtidas em posts.
- Top hashtags por agregação.

## 🏁 Resultado esperado

Ao concluir este desafio, você será capaz de modelar domínio social em MongoDB com consultas ricas.

## 🚀 Próximo desafio

No próximo desafio você irá evoluir para uma API REST completa com autenticação e paginação.
