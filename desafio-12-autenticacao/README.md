# 🚀 Desafio 12 — Autenticação

Neste desafio você irá proteger a API com fluxo de login, controle de sessão/token e autorização por perfil.

## 🎯 Objetivo do Desafio

Implementar autenticação de usuários e controle de acesso a rotas protegidas.

## 🧠 Tecnologias que você irá praticar

- Autenticação com credenciais
- Hash de senha
- JWT ou sessão
- Guards/Middlewares de autorização
- Boas práticas de segurança

## 📦 Escopo funcional (MVP)

Endpoints mínimos:

- `POST /auth/register`
- `POST /auth/login`
- `GET /me`
- rotas protegidas por perfil (`admin`, `member`)

## 🛠 Requisitos técnicos

- Nunca armazenar senha em texto puro.
- Implementar expiração de token/sessão.
- Validar credenciais com mensagens seguras.
- Proteger rotas sensíveis por role.

## ✅ Critérios de aceite

- Usuário registra e autentica com sucesso.
- Rotas protegidas exigem autenticação válida.
- Usuário sem permissão recebe erro apropriado (`403`).

## ⭐ Parte opcional

- Refresh token.
- 2FA básico (código temporário).

## 🏁 Resultado esperado

Ao concluir este desafio, você terá uma base sólida de segurança para APIs backend.

## 🚀 Próximo desafio

No próximo desafio você irá aprofundar Docker com otimizações e ambientes separados.
