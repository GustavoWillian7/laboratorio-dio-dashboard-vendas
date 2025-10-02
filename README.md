# Dashboard de Vendas em Excel

## Sobre o Projeto

Este projeto apresenta um dashboard de vendas interativo, desenvolvido inteiramente no Microsoft Excel. O principal objetivo é transformar dados brutos de vendas em um painel visual claro e funcional, que permita uma análise rápida e eficaz do desempenho de diferentes produtos ao longo do tempo.

A solução foi criada para ser intuitiva, utilizando recursos nativos do Excel para proporcionar uma experiência de análise de dados dinâmica e acessível.

## Funcionalidades Principais

O dashboard foi estruturado para facilitar a análise de vendas através dos seguintes componentes:

- **Visualização Consolidada:** Apresenta múltiplos gráficos e filtros em uma única tela para uma visão geral e completa do desempenho de vendas.
- **Gráfico de Vendas Mensais:** Um gráfico de colunas (`Total de Vendas por mês`) que exibe a performance de vendas ao longo dos meses, facilitando a identificação de tendências e sazonalidade.
- **Gráfico Comparativo de Produtos:** Um gráfico de barras que compara o valor total de vendas (`Soma de Total Value`) e o preço das assinaturas (`Soma de Subscription Price` e `Soma de Minecraft Season Pass Price`), permitindo uma análise de quais produtos geram mais receita.
- **Filtros Interativos (Segmentação de Dados):**
  - **Produtos:** Filtre os dados por tipo de assinatura (`Subscription Price`, `EA Play Season Pass`, etc.).
  - **Valores:** Analise o desempenho com base em faixas de preço específicas (`Total Value`).
  - **Período:** Selecione meses específicos para focar a análise em um determinado período.
- **Interatividade Total:** Todos os gráficos e dados são atualizados dinamicamente ao aplicar qualquer um dos filtros, proporcionando uma análise ágil e personalizada.

## Dados Utilizados

Os dados aplicados neste dashboard são fictícios e simulam um cenário de vendas de assinaturas de produtos digitais, como serviços de jogos. A base de dados foi estruturada em planilhas separadas (`Bases` e `Cálculos`) e contém informações como:

- **Produto/Assinatura:** Nome do produto vendido (ex: `EA Play`, `Minecraft Season Pass`).
- **Preço da Assinatura:** O valor de cada tipo de assinatura.
- **Valor Total:** O valor total da transação.
- **Mês:** O mês em que a venda foi realizada.

## Ferramentas Utilizadas

- **Microsoft Excel:**
  - Fórmulas e Funções
  - Tabelas Dinâmicas
  - Gráficos Dinâmicos
  - Segmentação de Dados para filtros interativos

## Como Utilizar o Dashboard

Para explorar as funcionalidades do dashboard, siga as instruções abaixo:

1. **Faça o download do repositório:**
   - Você pode clonar o repositório ou baixar o arquivo `.zip`.
2. **Abra o arquivo:**
   - Abra o arquivo `.xlsx` no Microsoft Excel (versão 2013 ou superior recomendada para total compatibilidade).
3. **Interaja com os filtros:**
   - Utilize as caixas de **Segmentação de Dados** localizadas nas laterais do dashboard para filtrar as informações.
   - Clique em um ou mais itens para ver os gráficos se ajustarem automaticamente. Para selecionar múltiplos itens, mantenha a tecla `Ctrl` pressionada ao clicar.
   - Para limpar um filtro, clique no ícone de funil com um "x" vermelho no canto superior direito da caixa de segmentação.
