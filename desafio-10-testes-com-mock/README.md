# 🚀 Desafio 10 — Testes com Mock

Neste desafio você irá isolar dependências externas para testar comportamento de negócio com mais precisão.

## 🎯 Objetivo do Desafio

Escrever testes unitários para services que dependem de banco, API externa ou fila, usando mocks/spies.

## 🧠 Tecnologias que você irá praticar

- Jest
- Mocks
- Spies
- Testes assíncronos
- Isolamento de dependências

## 📦 Escopo funcional (MVP)

Cobrir cenários como:

- service que cria usuário com repositório mockado;
- service que chama gateway externo em sucesso e erro;
- validação de chamadas (`toHaveBeenCalledWith`).

## 🛠 Requisitos técnicos

- Abstrair dependências por interfaces/contratos.
- Mockar retorno de sucesso e falha.
- Validar efeitos colaterais esperados.
- Manter testes rápidos e determinísticos.

## ✅ Critérios de aceite

- Testes independem de banco real.
- Cenários críticos de negócio cobertos.
- Mocks usados de forma clara e sem acoplamento excessivo.

## ⭐ Parte opcional

- Factory de dados fake reutilizável.
- Testes de contrato para dependências externas.

## 🏁 Resultado esperado

Ao concluir este desafio, você terá maturidade para testar regras complexas sem depender de infraestrutura real.

## 🚀 Próximo desafio

No nível avançado, você iniciará uma API inspirada em plataforma de streaming.
