# 🚀 Desafio 14 — Arquitetura com múltiplos serviços

Neste desafio você irá decompor uma aplicação em serviços independentes para ganhar escalabilidade e desacoplamento.

## 🎯 Objetivo do Desafio

Implementar uma arquitetura com, no mínimo, dois serviços backend que se comunicam entre si.

## 🧠 Tecnologias que você irá praticar

- Arquitetura de microserviços (base)
- Comunicação HTTP entre serviços
- Separação de responsabilidades
- Observabilidade básica
- Docker Compose para orquestração

## 📦 Escopo funcional (MVP)

Serviços sugeridos:

- `user-service`
- `catalog-service`
- `gateway-api` (opcional)

Fluxos mínimos:

- consulta de usuário + dados de catálogo;
- composição de resposta em endpoint agregado.

## 🛠 Requisitos técnicos

- Cada serviço com repositório lógico e domínio próprio.
- Comunicação entre serviços com timeout e tratamento de falha.
- Configuração via variáveis de ambiente por serviço.
- Logs com identificação de serviço.

## ✅ Critérios de aceite

- Serviços sobem e se comunicam corretamente.
- Falha de um serviço não derruba todo o sistema sem tratamento.
- Arquitetura documentada com diagrama simples.

## ⭐ Parte opcional

- Mensageria para comunicação assíncrona.
- Circuit breaker simples.

## 🏁 Resultado esperado

Ao concluir este desafio, você terá noção prática de decomposição de sistemas backend em serviços.

## 🚀 Próximo desafio

No próximo desafio você irá consolidar toda a formação em um projeto final completo.
