# 🚀 Desafio 13 — Docker avançado

Neste desafio você irá elevar a maturidade de containerização com foco em performance, segurança e reprodutibilidade.

## 🎯 Objetivo do Desafio

Otimizar build e runtime da sua API em Docker para cenário próximo de produção.

## 🧠 Tecnologias que você irá praticar

- Docker multi-stage build
- Imagens enxutas
- Usuário não-root
- Estratégia de cache
- Ambientes dev/prod

## 📦 Escopo funcional (MVP)

- Criar `Dockerfile` com multi-stage.
- Separar estágio de build e execução.
- Reduzir tamanho final da imagem.
- Rodar aplicação com usuário sem privilégios.

## 🛠 Requisitos técnicos

- Evitar dependências de desenvolvimento na imagem final.
- Configurar `NODE_ENV=production`.
- Definir estratégia de logs para container.
- Documentar comandos de build e run.

## ✅ Critérios de aceite

- Imagem final menor que a versão inicial.
- Aplicação executa corretamente no estágio final.
- Configuração segue práticas básicas de segurança.

## ⭐ Parte opcional

- Scan de vulnerabilidade de imagem.
- Publicação automática em registry.

## 🏁 Resultado esperado

Ao concluir este desafio, você terá domínio de Docker em nível profissional para backend.

## 🚀 Próximo desafio

No próximo desafio você irá dividir o sistema em múltiplos serviços.
