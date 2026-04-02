# 🚀 Desafio 01 — CRUD com MySQL

Bem-vindo ao primeiro desafio da Formação Backend JS.

Neste desafio você irá construir uma API CRUD completa usando Node.js e MySQL, praticando os fundamentos essenciais de backend: rotas, persistência, validação e organização de projeto.

O foco não é apenas "salvar e listar dados", mas entender o ciclo completo de uma entidade dentro de uma API real.

## 🎯 Objetivo do Desafio

Criar uma API para gerenciamento de produtos que:

- cadastra registros no MySQL;
- lista, busca, atualiza e remove registros;
- valida dados de entrada;
- retorna respostas HTTP padronizadas.

## 🧠 Tecnologias que você irá praticar

- Node.js
- JavaScript ou TypeScript
- MySQL
- SQL (`CREATE`, `INSERT`, `SELECT`, `UPDATE`, `DELETE`)
- API REST
- Validação com Zod

## 📦 Escopo funcional (MVP)

A API deve expor endpoints para a entidade `products`:

- `POST /products`
- `GET /products`
- `GET /products/:id`
- `PUT /products/:id`
- `DELETE /products/:id`

Campos sugeridos:

- `id` (auto incremento)
- `name` (obrigatório)
- `price` (obrigatório, maior que zero)
- `stock` (obrigatório, inteiro >= 0)
- `created_at` (timestamp)

## 🛠 Requisitos técnicos

- Organizar em camadas (rota/controller, service, repository).
- Criar script SQL inicial para tabela.
- Tratar erros de validação e erros de banco.
- Usar códigos HTTP corretos (`200`, `201`, `400`, `404`, `500`).
- Configurar variáveis de ambiente (`DB_HOST`, `DB_PORT`, `DB_USER`, `DB_PASSWORD`, `DB_NAME`).

## ✅ Critérios de aceite

- CRUD completo funcionando no Postman/Insomnia.
- Dados persistidos de forma consistente no MySQL.
- Mensagens de erro claras e padronizadas.
- Projeto com README de execução (`npm install`, `npm run dev`).

## ⭐ Parte opcional

- Paginação no `GET /products`.
- Filtro por nome.
- Ordenação por preço.

## 🏁 Resultado esperado

Ao concluir este desafio, você será capaz de estruturar uma API backend real com persistência SQL e operações CRUD completas.

## 🚀 Próximo desafio

No próximo desafio você irá trabalhar com MongoDB e modelagem básica NoSQL.
