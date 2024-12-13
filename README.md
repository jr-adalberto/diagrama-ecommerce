# E-commerce de Venda - Diagrama de Banco de Dados

Este repositório contém o diagrama de banco de dados para um sistema de e-commerce de vendas. O objetivo é modelar as entidades e seus relacionamentos necessários para atender aos requisitos de uma aplicação de comércio eletrônico.

## 📋 Descrição do Projeto

O sistema de e-commerce permite:
- Cadastro de clientes (Pessoa Física e Jurídica).
- Gerenciamento de contas, entregas e pagamentos.
- Atualização do status de entrega e rastreamento.

O diagrama representa a estrutura do banco de dados que dá suporte a essas funcionalidades.

## 🗂 Estrutura do Banco de Dados

### Entidades e Relacionamentos

1. **Cliente**
   - Pode ser **Pessoa Física (PF)** ou **Pessoa Jurídica (PJ)**.
   - Cada cliente está associado a uma única conta.

2. **Conta**
   - Relacionada a um cliente (PF ou PJ).
   - Armazena informações específicas da conta do cliente.

3. **Entrega**
   - Inclui código de rastreio e status para acompanhar os pedidos.
   - Relacionada a um pedido de compra.

4. **Pagamento**
   - Suporta múltiplas formas de pagamento por cliente.
   - Relacionado diretamente a um pedido.

### Diagrama ER
Abaixo está o diagrama de banco de dados:


## 🚀 Tecnologias Utilizadas

- **MySQL Workbench**: Para modelagem do banco de dados.
- **MySQL**: Sistema de gerenciamento do banco de dados.
- **Docker**: Para ambiente de desenvolvimento isolado.
- Outras tecnologias usadas durante a aula da DIO.

## 📦 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/ecommerce-diagram.git
