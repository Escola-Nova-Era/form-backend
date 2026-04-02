# 🚀 Desafio 03 — API com NestJS

Neste desafio você irá construir uma API com NestJS para praticar arquitetura modular, injeção de dependência e validação robusta.

## 🎯 Objetivo do Desafio

Criar um módulo de `users` com operações principais de cadastro e consulta, seguindo boas práticas do framework.

## 🧠 Tecnologias que você irá praticar

- NestJS
- TypeScript
- Controllers, Services e Modules
- DTOs
- Pipes de validação
- HTTP status codes

## 📦 Escopo funcional (MVP)

Endpoints mínimos:

- `POST /users`
- `GET /users`
- `GET /users/:id`
- `PATCH /users/:id`

Campos sugeridos para usuário:

- `id`
- `name`
- `email`
- `role` (`admin` ou `member`)

## 🛠 Requisitos técnicos

- Separar responsabilidades em módulo, controller e service.
- Criar DTOs para criação e atualização.
- Validar email e campos obrigatórios.
- Retornar erros coerentes para dados inválidos e usuário não encontrado.

## ✅ Critérios de aceite

- Projeto NestJS inicializado e executável.
- Endpoints funcionando com validação.
- Código organizado e de fácil manutenção.

## ⭐ Parte opcional

- Versionamento de rotas (`/v1/users`).
- Filtro por `role`.

## 🏁 Resultado esperado

Ao concluir este desafio, você terá base sólida para APIs profissionais usando NestJS.

## 🚀 Próximo desafio

No próximo desafio você irá containerizar uma API com Docker.
