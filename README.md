# Exploração de Dados Imobiliários: Prevendo Preços de Casas

O objetivo deste case é analisar o mercado imobiliário nos EUA, explorando os principais fatores que influenciam o preço de venda das casas. A análise visa prever os valores das propriedades utilizando um modelo de Regressão Linear, baseado em variáveis socioeconômicas e características das casas. Para isso, foi necessário:

Identificar os dados mais relevantes para a previsão de preços, como renda média, idade da casa e número de quartos.
Verificar a integridade e limpeza dos dados para garantir análises precisas.
Dividir o conjunto de dados entre treino e teste para aplicar o modelo de regressão e validar sua eficácia.

Etapas do Processo

Carregamento e Visualização de Dados:
O processo inicia com o carregamento do dataset "USA_Housing.csv" e uma análise descritiva das colunas, como preço, renda média da área e número de quartos. As primeiras e últimas linhas do dataset são visualizadas para garantir a integridade dos dados, e colunas desnecessárias, como o endereço, são removidas.

Limpeza e Transformação dos Dados:
Após a inspeção inicial, os nomes das colunas foram ajustados para garantir a consistência e facilitar a manipulação. As correlações entre as variáveis foram analisadas para identificar as que mais impactam o preço das casas.

Análise Visual:
Gráficos de dispersão, boxplots e heatmaps foram gerados para visualizar as relações entre as variáveis, como a renda média da área e o preço das casas. A análise visual é crucial para entender a distribuição dos dados e as correlações entre eles.

Modelagem com Regressão Linear:
Utilizando a biblioteca scikit-learn, foi aplicado um modelo de Regressão Linear para prever o preço das casas. A base de dados foi dividida em conjuntos de treino e teste, e o modelo foi ajustado utilizando as variáveis relevantes. A métrica r2_score foi utilizada para avaliar o desempenho do modelo.

Visualização dos Resultados:
Foi criado um gráfico comparando os preços reais e previstos, visualizando o quão bem o modelo conseguiu prever o preço das casas com base nos dados fornecidos.

As ferramentas e bibliotecas utilizadas: Pandas para a manipulação e limpeza de dados, Seaborn e Matplotlib para a visualização dos dados por meio de gráficos e mapas de calor, scikit-learn para a aplicação do modelo de Regressão Linear e Plotly para a criação de gráficos interativos que facilitam a análise dos dados.
