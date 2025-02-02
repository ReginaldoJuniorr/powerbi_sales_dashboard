# Documentação de Uso do Dashboard de Vendas

Este dashboard foi desenvolvido no Power BI para analisar dados de vendas de uma empresa fictícia. Ele permite visualizar informações sobre vendas globais, categorias de produtos, países, descontos e muito mais. Abaixo, você encontrará instruções sobre como usar o dashboard e explorar os dados.

## Funcionalidades do Dashboard
O dashboard permite responder às seguintes perguntas:

- Qual o valor total vendido?
  
- Quantas vendas foram realizadas por categoria de produto?

- Quantas vendas foram realizadas por país, considerando a prioridade de entrega?

- Qual foi a média de desconto nas vendas por subcategoria de produto?

- Quais países tiveram maior média de valor de venda? (Visualizado em um mapa)

Além disso, o dashboard oferece filtros interativos para explorar os dados de forma dinâmica.

## Filtros Disponíveis
O dashboard possui três filtros principais, localizados na lateral esquerda do painel. Eles permitem que você refine os dados de acordo com suas necessidades:

### Filtrar por Ano, Trimestre, Mês e Dia:

<details>
<summary>Ano</summary>
Selecione um ou mais anos para visualizar os dados específicos daquele período.

Exemplo: Selecione "2013" para ver apenas as vendas realizadas em 2013

</details>

<details>
<summary>Trimestre</summary>
Escolha um trimestre específico (Trim 1, Trim 2, Trim 3, Trim 4) para analisar as vendas em períodos trimestrais.

Exemplo: Selecione "Trim 1" para visualizar as vendas do primeiro trimestre.

</details>

<details>
<summary>Mês</summary>
Selecione um ou mais meses para focar em vendas específicas ao longo do ano.

Exemplo: Selecione "Janeiro" e "Dezembro" para comparar as vendas no início e no fim do ano.

</details>

<details>
<summary>Dia</summary>
Escolha dias específicos para uma análise mais detalhada.

Exemplo: Selecione "15/03/2013" para ver as vendas realizadas nesse dia.

</details>

### Filtrar por Segmento:

Escolha um segmento de mercado para analisar as vendas por categoria de cliente.

Exemplo: Selecione "Consumer" para visualizar apenas as vendas para consumidores finais.

### Filtrar por País:

Selecione um ou mais países para focar nas vendas realizadas nessas regiões.

Exemplo: Selecione "Brazil" e "United States" para comparar as vendas entre esses dois países.

## Como Usar os Filtros
### Seleção Única:

Clique em um valor nos filtros (por exemplo, um ano específico) para aplicar a seleção.

O dashboard será atualizado automaticamente para mostrar apenas os dados correspondentes.

### Seleção Múltipla:

Para selecionar mais de um valor, segure a tecla Ctrl (Windows) ou Command (Mac) e clique nos valores desejados.

Exemplo: Selecione "2013" e "2014" para comparar as vendas entre esses dois anos.

### Limpar Filtros:

Para remover todos os filtros, clique no ícone de "borracha" (ou "limpar filtros") no canto superior direito do painel.

## Visualizações Disponíveis
O dashboard contém as seguintes visualizações interativas:

### Valor Total Vendido:

- Um cartão que exibe o valor total das vendas com base nos filtros aplicados.

### Vendas por Categoria de Produto:

- Um gráfico de rosca que mostra a quantidade de vendas por categoria (por exemplo, Suprimentos, Tecnologia, etc.).

### Vendas por País e Prioridade de Entrega:

- Um gráfico de barras empilhadas que exibe as vendas por país, com destaque para a prioridade de entrega (Baixa, Média, Alta e Crítico).

### Média de Desconto por Subcategoria:

- Um gráfico de barras clusterizado que mostra a média de desconto aplicada em cada subcategoria de produto.

### Mapa de Vendas por País:

- Um mapa interativo que destaca os países com maior média de valor de venda. Quanto maior a bolha, maior a média de vendas.

## Dicas de Uso
### Interaja com as Visualizações:

Passe o mouse sobre os gráficos para ver detalhes específicos, como valores exatos e porcentagens.

Clique em uma barra ou segmento do gráfico para aplicar um filtro adicional.

## Exportar Dados:

Para exportar os dados de uma visualização, clique no ícone de três pontos no canto superior direito da visualização e selecione "Exportar dados".

## Atualizar Dados:

Se o dataset for atualizado, clique em "Atualizar" no Power BI Service para carregar os dados mais recentes.

## Exemplo de Uso

Suponha que você queira responder à pergunta: "Qual foi o valor total vendido no Brasil em 2012 para o segmento Consumer?"

## Aplique os filtros:

- Ano: Selecione "2014".

- Segmento: Selecione "Consumidor".

- País: Selecione "Brazil".

Observe o cartão "Valor Total Vendido" para ver o resultado.

Explore outras visualizações para obter mais insights, como a média de desconto por subcategoria ou as vendas por prioridade de entrega.

## Requisitos Técnicos
Para visualizar o dashboard, é necessário ter o Power BI Desktop instalado ou acessar o Power BI Service (versão web).

O arquivo do dashboard está disponível na pasta powerbi/ deste repositório.
