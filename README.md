# 🧾 Sistema de Vendas Web Forms (CRUD + Estoque)

Sistema simples de vendas desenvolvido com **ASP.NET Web Forms** e **banco de dados relacional**, focado em demonstrar conhecimentos em CRUD, autenticação, controle de estoque e lógica de vendas.

---

## 🚀 Funcionalidades

- ✅ Login com autenticação por e-mail e senha
- ✅ Cadastro e listagem de produtos (estoque)
- ✅ Cadastro de clientes
- ✅ Registro de vendas com atualização de estoque
- ✅ Consulta de vendas realizadas
- ✅ Cancelamento de vendas
- ✅ Relatórios simples (produtos mais vendidos, estoque baixo)
- ✅ Interface protegida por sessão

---

## 🛠️ Tecnologias Utilizadas

- ASP.NET Web Forms (C#)
- ADO.NET
- SQL Server ou MySQL
- HTML/CSS
- Bootstrap (opcional para estilo)

---

## 📦 Estrutura do Banco de Dados

- **Usuarios** (Id, Nome, Email, SenhaHash)
- **Produtos** (Id, Nome, Preco, QuantidadeEstoque, Ativo)
- **Clientes** (Id, Nome, CPF, Email, Telefone)
- **Vendas** (Id, Data, ClienteId, UsuarioId, Total, Status)
- **ItensVenda** (Id, VendaId, ProdutoId, Quantidade, Subtotal)

---

## 🔐 Segurança

- Autenticação de usuários com verificação de sessão
- Proteção de páginas internas
- Senhas armazenadas com hash

---

## 🎯 Objetivo

Este projeto foi criado como parte do meu aprendizado e para compor meu portfólio na área de **desenvolvimento back-end** e **sistemas de informação**. Simula um sistema simples de controle de vendas, ideal para pequenos comércios.

---

## 🧠 Aprendizados

Durante o desenvolvimento, pratiquei:
- CRUD completo com ADO.NET
- Manipulação de sessões
- Atualização de estoque via lógica de negócio
- Criação de relacionamentos no banco de dados
- Organização de páginas em Web Forms
