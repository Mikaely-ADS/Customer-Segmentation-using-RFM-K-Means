# Customer-Segmentation-using-RFM-K-Means
Este projeto aplica técnicas de Machine Learning Não Supervisionado para segmentar clientes de um e-commerce utilizando a metodologia RFM (Recency, Frequency e Monetary)

Sobre o projeto
Este projeto aplica técnicas de Machine Learning Não Supervisionado para segmentar clientes de um e-commerce utilizando a metodologia RFM (Recency, Frequency e Monetary).

O objetivo é identificar grupos de clientes com comportamentos semelhantes para apoiar estratégias de CRM, retenção e marketing personalizado.

Objetivos
Explorar os dados
Realizar tratamento e limpeza
Construir métricas RFM
Aplicar normalização
Encontrar o número ideal de clusters
Treinar o algoritmo K-Means
Interpretar os segmentos encontrados
Gerar insights de negócio
Tecnologias
Python
Pandas
NumPy
Scikit-Learn
Matplotlib
Seaborn
Plotly
Pipeline
Importação dos dados
Limpeza
Tratamento de devoluções
Construção do RFM
Escalonamento
PCA
Elbow Method
Silhouette Score
K-Means
Análise dos clusters
Resultados
O modelo identificou dois segmentos principais:

Cluster 1 — VIP
Compras recentes
Alta frequência
Alto valor gasto
Responsável por aproximadamente 86% da receita
Cluster 0 — Risco de Churn
Longo tempo sem comprar
Poucas compras
Baixo valor gasto
Insights
Criar programas de fidelidade para clientes VIP.
Desenvolver campanhas de reativação para clientes inativos.
Personalizar ofertas conforme o comportamento de compra.
Autor
Seu nome

LinkedIn

GitHub

Eu também notei alguns pontos interessantes no seu código:

Você utilizou RobustScaler, uma escolha excelente para dados com outliers.
Aplicou transformação logarítmica nas variáveis RFM para reduzir assimetria.
Validou o número de clusters usando tanto Elbow quanto Silhouette, o que demonstra uma boa prática.
Utilizou PCA apenas para visualização, preservando o treinamento no espaço original.
Interpretou os clusters com foco em negócio, algo valorizado em processos seletivos.
