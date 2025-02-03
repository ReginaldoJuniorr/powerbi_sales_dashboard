# 🗃️ Dashboard Analítico de Vendas Globais

## Cenário Proposto

Neste projeto, atuei como analista de dados de uma empresa fictícia que comercializa produtos globalmente. Minha missão foi criar um dashboard interativo para fornecer insights estratégicos sobre as vendas realizadas em diferentes categorias de produtos, países e prioridades de entrega.
Durante o processo, realizei a limpeza de dados via Power Query, corrigindo erros como linhas duplicadas. Essa tarefa foi facilitada pelo fato de haver poucas duplicatas, permitindo que a limpeza fosse eficiente e precisa.
Utilizei o Power BI como ferramenta de visualização e análise de dados, criando um painel que responde a perguntas-chave sobre o desempenho global da empresa, além de permitir uma exploração interativa com filtros dinâmicos.

## Objetivos e Insights do Dashboard

O dashboard foi desenvolvido para responder às seguintes perguntas de negócios:

- Qual foi o valor total vendido?
  
  Apresentado de forma destacada em um cartão central.

- Quantas vendas foram realizadas por categoria de produto?
  
  Representado em um gráfico de rosca.

- Quantas vendas foram realizadas por país, considerando a prioridade de entrega?
  
  Visualizado em um gráfico de barras empilhadas.

- Qual foi a média de desconto nas vendas por subcategoria de produto?

  Exibido em um gráfico de barras horizontais.

- Quais países tiveram maior média de valor de venda?

  Demonstrado em um mapa interativo com bolhas proporcionais.

## Print do Dashboard pronto:

![Dashboard](https://github.com/user-attachments/assets/5799d6c7-4010-4d62-bff3-5fe1266e6eb7)


## Exploração do Dashboard

### Filtros Disponíveis

Os filtros interativos localizados na lateral do painel permitem refinar as análises de acordo com:

- Ano, Trimestre, Mês e Dia: Para explorar períodos específicos.
- Segmento: Para comparar vendas entre consumidores, empresas ou escritórios domésticos.
- País: Para focar nas vendas de países ou regiões específicas.

### Visualizações Incluídas

- Valor Total Vendido:

  Destacado em um cartão para rápida visualização do total de vendas.

- Vendas por Categoria:

  Gráfico de rosca com a divisão entre Suprimentos, Tecnologia e Móveis.

- Vendas por País e Prioridade:

  Gráfico de barras empilhadas mostrando o desempenho de vendas e suas respectivas prioridades (Baixa, Média, Alta, Crítica).

- Média de Desconto por Subcategoria:

  Gráfico de barras horizontais para analisar o impacto dos descontos por subcategoria.

- Mapa Interativo de Vendas por País:
  
  Apresentando visualmente os países com maior média de vendas.

## Exemplo de Uso

Pergunta: Qual foi o valor total vendido no Brasil em 2014 para consumidores finais?

Passo a passo:

1 - Aplique os filtros:

- Ano: 2014
- Segmento: Consumer
- País: Brazil

2 - Confira o valor no cartão "Valor Total Vendido".

3 - Explore gráficos como "Vendas por País e Prioridade" ou "Média de Desconto por Subcategoria" para insights adicionais.

*Resultado: O valor total foi de $56,46 Mil*

## 📊 Gráficos e Insights Adicionais

### Análise por Categoria

A categoria "Suprimentos" foi responsável pela maior parte das vendas, com 60,97% do total, enquanto "Móveis" e "Tecnologia" representaram 19,26% e 19,77%, respectivamente.

### Mapa Interativo de Vendas

A maior parte das vendas está concentrada na Europa, onde há uma maior densidade de pontos (bolhas) indicando mais países com médias significativas de vendas. Há também atividade considerável na Ásia e América do Norte.

## 📎 Requisitos Técnicos

- [Power BI Desktop](https://www.microsoft.com/pt-br/power-platform/products/power-bi/desktop) ou [Power BI Service (web)](https://app.powerbi.com/singleSignOn?pbi_source=websignin&cmpid=pbi-glob-head-snn-signin&ru=https%3A%2F%2Fapp.powerbi.com%2F%3Fpbi_source%3Dwebsignin%26cmpid%3Dpbi-glob-head-snn-signin%26noSignUpCheck%3D1) para acessar e interagir com o dashboard.
- O arquivo .pbix do dashboard está disponível neste repositório, na pasta [powerbi/](https://github.com/ReginaldoJuniorr/powerbi_sales_dashboard/blob/main/PowerBI/sales_dashboard.pbix).
