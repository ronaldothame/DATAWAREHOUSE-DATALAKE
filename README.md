# Data Warehouse e DataLake

## Visão Geral
Este projeto aborda conceitos de engenharia de dados e análise exploratória utilizando Python, Pandas, Matplotlib, Seaborn e SQLAlchemy. Um dos focos principais é a implementação de um Data Lake e um Data Warehouse para gerenciar e analisar dados relacionados a vendas de produtos.

## Estrutura do Projeto
O projeto está estruturado em duas partes principais:
1. **Engenharia de Dados**
   - Geração de dados aleatórios para simulação de vendas e armazenamento em arquivos CSV.
   - Utilização do SQLite e SQLAlchemy para criar um banco de dados `data_lake.db` e armazenar os dados gerados em tabelas separadas.
2. **Análise de Dados**
   - Carregamento dos dados do banco de dados SQLite em DataFrames Pandas.
   - Análise exploratória das vendas por produto, categoria e tendências temporais.
   - Criação de visualizações gráficas usando Matplotlib e Seaborn.

## Detalhes do Código
- **Geração de Dados e Armazenamento:**
  - Criação de 10 arquivos CSV com dados aleatórios.
  - Armazenamento desses dados no diretório `data_lake/` e no banco de dados SQLite `data_lake.db`.

- **Análise de Dados e Visualizações:**
  - Leitura dos dados do arquivo `data_warehouse.csv` e do banco de dados SQLite.
  - Análise de vendas por produto, categoria e tendências temporais.
  - Criação de gráficos de dispersão, histogramas e boxplot para análise visual dos dados.

## Resultados e Visualizações
1. **Análise de Vendas por Produto e Categoria:**
   - Demonstração da quantidade vendida e valor total por produto e categoria.
   - Visualização das análises em formato tabular.

2. **Análise de Tendências Temporais:**
   - Exibição da evolução das vendas ao longo do tempo em relação à quantidade vendida e valor total.

3. **Análise de Desempenho de Produtos:**
   - Avaliação do desempenho de cada produto com base no valor total de vendas.

4. **Visualizações Gráficas:**
   - Gráfico de vendas ao longo do tempo.
   - Gráficos de dispersão, histograma e boxplot para análise detalhada dos dados.
