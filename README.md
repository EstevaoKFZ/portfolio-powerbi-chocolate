# Dashboard de Análise de Vendas — Indústria de Chocolates

Dashboard em Power BI para análise de desempenho comercial de uma
indústria de chocolates, com modelagem dimensional em Star Schema
e métricas de inteligência de tempo em DAX.



## Modelagem de Dados

O modelo segue o padrão Star Schema, com 1 tabela fato e 4 tabelas
dimensão:

**Dimensões:**
- Dim Produto
- Dim Data
- Dim Vendedor
- Dim País

*(ajuste os nomes das dimensões reais que você usou — coloquei os que
fazem sentido pelo contexto de vendas)*

## Tratamento de Dados (Power Query)

- Padronização de texto (nomes de produtos/vendedores em formato consistente)
- Tratamento de valores nulos
- Remoção de duplicatas




## Principais Achados

- Faturamento consolidado de $6,02M em vendas
- Recuo de -23,87% no crescimento anual — [PREENCHER: qual hipótese
  isso levanta? sazonalidade, perda de mercado, período incompleto
  no dataset?]
- Volume total de 197,57 mil itens comercializados

## Tecnologias

Power BI Desktop · Power Query (M) · DAX

## Como Visualizar

1. Instale o Power BI Desktop
2. Baixe o arquivo `Chocolate.pbix` deste repositório
3. Abra para explorar o modelo, relacionamentos e medidas DAX
