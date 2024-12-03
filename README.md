# sistema_recomendacao_musica
Título: Sistema de Recomendação Musical baseado em Clustering e Análise de Componentes Principais

Descrição:

Este projeto tem como objetivo desenvolver um sistema de recomendação musical personalizado, utilizando técnicas de aprendizado de máquina. Através da análise de um vasto conjunto de dados 
musicais, exploramos a relação entre diferentes características das músicas e agrupamos as músicas em clusters semelhantes. Com base nesses clusters, desenvolvemos um algoritmo de recomendação 
que sugere novas músicas aos usuários com base em suas preferências.

Metodologia:

Coleta e Preparação dos Dados:
Coleta de dados de diversas fontes, incluindo informações sobre as músicas, artistas e gêneros.
Limpeza e tratamento dos dados, garantindo a qualidade e consistência das informações.
Criação de um dicionário de dados para documentar as features utilizadas.
Análise Exploratória de Dados:
Visualização dos dados através de gráficos e tabelas para identificar padrões e correlações.
Cálculo da matriz de correlação para entender as relações entre as features.
Pré-processamento dos Dados:
Vetorização das features numéricas.
Normalização dos dados utilizando o StandardScaler.
Redução da dimensionalidade com PCA para facilitar a visualização e o agrupamento.
Agrupamento:
Utilização do algoritmo K-Means para agrupar as músicas em clusters.
Análise dos clusters para avaliar a qualidade do agrupamento e a interpretação dos resultados.
Recomendação:
Cálculo da distância euclidiana entre as músicas para encontrar as mais similares dentro de um mesmo cluster.
Utilização da biblioteca Spotipy para enriquecer as recomendações com informações como nome da música e capa do álbum.
Desenvolvimento do Sistema de Recomendação:
Criação de uma função que recebe uma música como entrada e retorna um conjunto de recomendações personalizadas.

Resultados:

O sistema de recomendação desenvolvido mostrou-se eficaz em sugerir músicas relevantes aos usuários, com base em suas preferências musicais. A utilização do PCA e do K-Means permitiu agrupar as músicas de forma eficiente e identificar padrões interessantes nos dados. A integração da biblioteca Spotipy enriqueceu a experiência do usuário, fornecendo informações visuais sobre as músicas recomendadas.

Tecnologias Utilizadas:

Linguagem de Programação: Python
Bibliotecas: Pyspark, Pyspark.sql, Pyspark.ml, plotly, numpy, scipy, spotipy, matplotlib, skimage.
Ambiente: Google Colab.
