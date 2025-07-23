# MovelControl

![Status do Projeto](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)

## 📝 Sumário
- [Sobre o Projeto](#-sobre-o-projeto)
- [✨ Funcionalidades](#-funcionalidades)
- [🏛️ Arquitetura](#️-arquitetura)
- [🚀 Começando](#-começando)
- [🤝 Como Contribuir](#-como-contribuir)
- [📫 Contato](#-contato)

## 📖 Sobre o Projeto

**MovelControl** é um sistema de gestão integrada (ERP) projetado para otimizar os processos de uma marcenaria de móveis planejados. O objetivo é substituir o controlo manual por uma solução digital, centralizando informações e automatizando fluxos de trabalho críticos.

O sistema atuará como uma API REST, oferecendo flexibilidade para a implementação de diversas interfaces de cliente (front-end). O foco principal é a organização interna, a gestão de orçamentos, o controlo da produção e, crucialmente, a gestão de estoque.

Este projeto foi desenvolvido como parte do curso de Sistemas de Informação do Instituto Federal Goiano - Campus Urutaí.

---

## ✨ Funcionalidades

-   ✅ **Gestão de Orçamentos:** Crie e emita orçamentos personalizados.
-   📦 **Controlo de Estoque:** Faça a gestão completa de materiais, incluindo entradas, saídas, edições e exclusões.
-   👥 **Gestão de Clientes:** Mantenha um registo organizado dos clientes para agilizar o processo comercial.
-   📋 **Registo de Pedidos:** Registe e acompanhe o estado de todos os pedidos de clientes.
-   🚚 **Pedidos a Fornecedores:** Crie e gira pedidos de compra de materiais para os seus fornecedores.
-   🧾 **Emissão de Fatura:** Gere e envie faturas eletrónicas (NF-e) para os clientes, com integração a sistemas externos.
-   📧 **Envio de Documentos:** Envie orçamentos e faturas diretamente para o e-mail do cliente.

---

## 🏛️ Arquitetura

O sistema foi projetado com base numa variação do padrão arquitetural **Model-View-Controller (MVC)**, com a adição de uma camada de **Repositório** para abstrair o acesso aos dados.

-   **`Model`**: Representa as entidades de negócio (ex: `Utilizador`, `Pedido`, `Item`).
-   **`View`**: Camada de apresentação (Interface do Utilizador).
-   **`Controller`**: Intermediário que processa as regras de negócio.
-   **`Repositorio`**: Camada de acesso a dados, responsável pela comunicação com a base de dados.

A infraestrutura é baseada numa arquitetura cliente-servidor para operar em rede local, garantindo segurança e rapidez no acesso aos dados.

---

## 🤝 Como Contribuir

Contribuições são o que tornam a comunidade de código aberto um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que fizer será **muito apreciada**.

1.  Faça um *Fork* do Projeto
2.  Crie a sua *Feature Branch* (`git checkout -b feature/AmazingFeature`)
3.  Faça o *Commit* das suas alterações (`git commit -m 'Add some AmazingFeature'`)
4.  Faça o *Push* para a *Branch* (`git push origin feature/AmazingFeature`)
5.  Abra um *Pull Request*

---

## 📫 Contato

Jorge Afonso Rabelo de Araujo - [jorgeafonsoaraujo@gmail.com](mailto:jorgeafonsoaraujo@gmail.com)
