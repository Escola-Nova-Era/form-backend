# 🚀 Desafio 09 — Docker Compose

Neste desafio você irá subir sua aplicação com banco e dependências usando uma única orquestração.

## 🎯 Objetivo do Desafio

Configurar ambiente completo com Docker Compose para API + banco de dados + ferramenta auxiliar (opcional).

## 🧠 Tecnologias que você irá praticar

- Docker Compose
- Networks e volumes
- Variáveis de ambiente
- Dependência entre serviços

## 📦 Escopo funcional (MVP)

Serviços mínimos:

- `api`
- `db` (MySQL ou MongoDB)

Fluxo esperado:

- subir tudo com `docker compose up`;
- API conectar automaticamente ao banco;
- persistência de dados em volume.

## 🛠 Requisitos técnicos

- Definir `docker-compose.yml` com portas e variáveis.
- Configurar healthcheck simples no banco (quando aplicável).
- Evitar credenciais hardcoded no código.
- Criar instruções de setup no README do projeto.

## ✅ Critérios de aceite

- Ambiente sobe com um único comando.
- API responde corretamente após startup.
- Dados permanecem entre reinícios de container.

## ⭐ Parte opcional

- Serviço de admin DB (Adminer ou Mongo Express).
- Perfis de compose para dev e test.

## 🏁 Resultado esperado

Ao concluir este desafio, você terá domínio de ambiente multi-serviço para desenvolvimento backend.

## 🚀 Próximo desafio

No próximo desafio você irá praticar testes com mocks e isolamento de dependências.
