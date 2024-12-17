# Vamos encher o carrinho! 🛒

## Sobre o Projeto

Este projeto analisa dados da Instacart, uma plataforma de entrega de supermercado que funciona de forma similar ao Uber Eats e iFood. O conjunto de dados utilizado é uma versão modificada do original, otimizada para performance computacional, incluindo valores ausentes e duplicados controlados que mantêm as distribuições dos dados originais.

## Estrutura do Conjunto de Dados 📊

O conjunto de dados está dividido em cinco tabelas principais:

### 1. Pedidos (instacart_orders.csv)
- **order_id**: Identificador único do pedido
- **user_id**: Identificador único do cliente
- **order_number**: Número sequencial de pedidos do cliente
- **order_dow**: Dia da semana do pedido (0 = domingo)
- **order_hour_of_day**: Hora do dia do pedido
- **days_since_prior_order**: Dias desde o último pedido

### 2. Produtos (products.csv)
- **product_id**: Identificador único do produto
- **product_name**: Nome do produto
- **aisle_id**: Identificador do corredor
- **department_id**: Identificador do departamento

### 3. Produtos por Pedido (order_products.csv)
- **order_id**: Identificador único do pedido
- **product_id**: Identificador único do produto
- **add_to_cart_order**: Ordem de adição ao carrinho
- **reordered**: Indicador de recompra (0 = primeira compra, 1 = recompra)

### 4. Corredores (aisles.csv)
- **aisle_id**: Identificador único do corredor
- **aisle**: Nome do corredor

### 5. Departamentos (departments.csv)
- **department_id**: Identificador único do departamento
- **department**: Nome do departamento

## Etapas do Projeto 📝

O projeto está estruturado em três etapas principais. Cada etapa inclui:
- Introdução com metodologia proposta
- Desenvolvimento com justificativas das decisões tomadas
- Conclusão com resumo das descobertas e escolhas
