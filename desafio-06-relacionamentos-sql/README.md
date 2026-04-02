# 🚀 Desafio 06 — Relacionamentos SQL

Neste desafio você irá modelar um domínio com múltiplas tabelas e relacionamentos para sair do CRUD simples.

## 🎯 Objetivo do Desafio

Criar uma API de pedidos com as entidades `customers`, `orders` e `order_items`.

## 🧠 Tecnologias que você irá praticar

- MySQL
- Relacionamentos `1:N` e `N:N`
- `FOREIGN KEY`
- `JOIN`
- API REST com regras de integridade

## 📦 Escopo funcional (MVP)

Funcionalidades mínimas:

- cadastrar cliente;
- criar pedido com múltiplos itens;
- listar pedidos com dados agregados (cliente + itens);
- cancelar pedido respeitando regras de negócio.

## 🛠 Requisitos técnicos

- Definir schema SQL com chaves primárias e estrangeiras.
- Aplicar `ON DELETE` e `ON UPDATE` conforme necessidade.
- Consultar dados com `JOIN`.
- Validar existência de cliente e produtos antes de criar pedido.

## ✅ Critérios de aceite

- Modelo relacional consistente.
- API cria e consulta dados relacionais corretamente.
- Integridade referencial preservada.

## ⭐ Parte opcional

- Total do pedido calculado por query.
- Paginação na listagem de pedidos.

## 🏁 Resultado esperado

Ao concluir este desafio, você terá domínio de modelagem relacional para cenários reais de negócio.

## 🚀 Próximo desafio

No próximo desafio você irá modelar uma rede social usando MongoDB.
