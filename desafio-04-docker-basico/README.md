# 🚀 Desafio 04 — Docker básico

Neste desafio você irá empacotar sua API em um container, tornando a execução previsível em qualquer ambiente.

## 🎯 Objetivo do Desafio

Criar a imagem e o container de uma API Node.js para rodar localmente com Docker.

## 🧠 Tecnologias que você irá praticar

- Docker
- Dockerfile
- Imagens e containers
- Variáveis de ambiente
- Port mapping

## 📦 Escopo funcional (MVP)

- Criar um `Dockerfile` para sua API.
- Gerar imagem com `docker build`.
- Subir container com `docker run`.
- Expor a porta da aplicação (ex.: `3000`).

## 🛠 Requisitos técnicos

- Utilizar imagem base oficial do Node.
- Copiar dependências e instalar com cache eficiente.
- Definir `WORKDIR`, `EXPOSE` e comando de inicialização.
- Passar variáveis de ambiente para conexão de banco.

## ✅ Critérios de aceite

- A API sobe dentro do container sem erro.
- Endpoints respondem fora do container.
- Build reproduzível em outra máquina.

## ⭐ Parte opcional

- Imagem otimizada (multi-stage build).
- Usuário não-root no container.

## 🏁 Resultado esperado

Ao concluir este desafio, você saberá containerizar aplicações backend Node.js com segurança e previsibilidade.

## 🚀 Próximo desafio

No próximo desafio você irá garantir qualidade da API com testes usando Jest.
