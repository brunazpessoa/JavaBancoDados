# 💰 Sistema de Gerenciamento de Contas Bancárias

Este projeto é um sistema de terminal em Java que permite consultar, adicionar, alterar e remover contas bancárias armazenadas em um banco de dados PostgreSQL. Ele utiliza JDBC para conectar-se ao banco e realizar as operações de CRUD.

---

## 📌 Funcionalidades

- 🔍 **Consultar contas** existentes no banco.
- ➕ **Adicionar nova conta** com número e saldo.
- ♻️ **Alterar saldo** de uma conta existente.
- 🗑 **Remover conta** do banco.
- 💾 **Persistência via banco de dados PostgreSQL** com uso de `PreparedStatement`.

---

## 🗂 Estrutura do Projeto

- `App.java`: conexão básica com o banco e exibição das contas.
- `Main.java`: interface via terminal com menu interativo.
- `Conta.java`: classe que representa uma conta bancária com número e saldo.
- `ObjetoDados.java`: camada de persistência que faz operações no banco (DAO).

---

## 🛠 Tecnologias Usadas

- Java 8+
- JDBC (Java Database Connectivity)
- PostgreSQL
- Supabase (como provedor de banco hospedado)

---

