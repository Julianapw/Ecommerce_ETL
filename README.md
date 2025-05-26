# API Ecommerce Fashion + ETL para Data Warehouse

## Descrição

Este projeto consiste em uma API RESTful desenvolvida com Flask para gerenciar operações básicas de um e-commerce de moda, incluindo criação de contas, login e faturamento de pedidos. Além disso, implementa processos ETL que extraem dados do banco relacional MySQL, transformam e carregam em um Data Warehouse baseado em MongoDB.

O objetivo é demonstrar a integração entre bancos de dados relacionais e NoSQL, bem como o uso de ETL para alimentar análises em um ambiente de Data Warehouse.

## Funcionalidades

- Criar conta de cliente (`/criarConta`)
- Login de cliente (`/login`)
- Faturar pedido e disparar ETL para carregamento no DW (`/faturarPedido`)
- Executar ETL para pedidos cancelados (`/etlPedidosCancelados`)
- Executar ETL para produtos sem estoque (`/etlProdutosFaltantes`)

## Tecnologias utilizadas

- Python 3.x
- Flask (API REST)
- MySQL (Banco de dados relacional)
- MongoDB (Data Warehouse NoSQL)
- Biblioteca `requests` para testes da API

## Estrutura do projeto

- `app.py`: Aplicação Flask com rotas da API  
- `etl.py`: Funções ETL para extração, transformação e carga dos dados  
- `database.py`: Conexão com MySQL e MongoDB  
- `teste_api.py`: Script para testar as rotas da API via HTTP requests  

## AUTORES

- Ana Beatriz Maranho Oliveira Silva - 23000755  
- Julia Carolina Kimura - 23031075  
- Juliana Prado - 24003497  
- Laura Nogueira Pereira - 24013968  
