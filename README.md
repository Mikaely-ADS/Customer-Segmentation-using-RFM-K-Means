# Customer-Segmentation-using-RFM-K-Means
Este projeto aplica técnicas de Machine Learning Não Supervisionado para segmentar clientes de um e-commerce utilizando a metodologia RFM (Recency, Frequency e Monetary)

Projeto de Ciência de Dados desenvolvido para segmentação de clientes utilizando técnicas de Machine Learning Não Supervisionado.

Visão Geral
Este projeto aplica técnicas de Clusterização para identificar diferentes perfis de clientes a partir do histórico de compras de um e-commerce.

A segmentação foi construída utilizando a metodologia RFM (Recency, Frequency e Monetary), seguida pela aplicação do algoritmo K-Means para descoberta de padrões de comportamento.

O resultado permite apoiar decisões estratégicas nas áreas de:

CRM
Marketing
Retenção de clientes
Fidelização
Campanhas de reativação
Objetivo
Desenvolver um modelo capaz de identificar grupos de clientes com comportamentos semelhantes através de técnicas de Machine Learning Não Supervisionado.

Tecnologias
Python
Pandas
NumPy
Scikit-Learn
Matplotlib
Seaborn
Plotly
PCA
K-Means
RobustScaler
Pipeline do Projeto
Base de Dados
      │
      ▼
Análise Exploratória
      │
      ▼
Tratamento dos Dados
      │
      ▼
Construção do RFM
      │
      ▼
Transformação Log
      │
      ▼
RobustScaler
      │
      ▼
PCA (Visualização)
      │
      ▼
Elbow Method
      │
      ▼
Silhouette Score
      │
      ▼
K-Means
      │
      ▼
Análise dos Clusters
      │
      ▼
Insights de Negócio
Análise Exploratória
Durante a etapa de exploração foram realizadas:

Identificação de valores nulos
Conversão de datas
Tratamento de devoluções
Remoção de registros inconsistentes
Análise de outliers
Winsorização das variáveis
Estatísticas descritivas
Engenharia de Atributos
Foram construídas três métricas fundamentais para segmentação:

Recency
Quantidade de dias desde a última compra.

Frequency
Número de compras realizadas.

Monetary
Valor total gasto pelo cliente.

Pré-processamento
Antes do treinamento foram aplicadas:

Transformação Log (log1p)
RobustScaler
PCA para visualização
Escolha do Modelo
O algoritmo selecionado foi:

✅ K-Means

A escolha foi baseada em:

Elbow Method
Silhouette Score
Resultado obtido:

Melhor número de clusters: 2
Silhouette Score ≈ 0.43
Resultados
Cluster 1 — VIP / Alta Lealdade
Características:

Compras recentes
Alta frequência
Alto gasto
Responsável pela maior parcela da receita
Estratégias recomendadas:

Programa de fidelidade
Cross Sell
Upsell
Benefícios exclusivos
Cluster 0 — Risco de Churn
Características:

Longo período sem compras
Baixa frequência
Baixo valor gasto
Estratégias recomendadas:

Campanhas de reativação
Cupons de desconto
Frete grátis
Comunicação personalizada
Principais Insights
A análise demonstrou que uma pequena parcela dos clientes concentra a maior parte do faturamento.

A utilização de técnicas de segmentação permite direcionar campanhas específicas para cada perfil, aumentando o ROI das ações de marketing.

Estrutura do Projeto
customer-segmentation-rfm-kmeans/

├── notebook.ipynb
├── README.md
├── requirements.txt
├── data/
├── images/
├── docs/
│   └── documentacao_profissional_desafio7.pdf
Competências Demonstradas
Data Cleaning
Exploratory Data Analysis (EDA)
Feature Engineering
Customer Analytics
RFM Analysis
Machine Learning
Unsupervised Learning
K-Means Clustering
Data Visualization
Business Intelligence

Autor: Mikaely Alves Dias

LinkedIn: https://www.linkedin.com/in/mikaely-alves-745426218/

GitHub: https://github.com/Mikaely-ADS


      │
  
