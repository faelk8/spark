<h1 align="center">
  <img src="../image/spark.png" alt="pyspark" width=360px height=200px >
  <br>

</h1>

<div align="center">

<!-- [![Status](https://img.shields.io/badge/version-1.0-blue)]() -->
[![Status](https://img.shields.io/badge/status-active-success.svg)]()

</div>

Desenvolvendo um sistema de recomendação

# Dicionário de Dados
Contém as informações de cada coluna

# Análise
* Ano 
  * Loudness
  * Acousticness
  * Valence
  * Danceability
  * Energy
  * Instrumentalness
  * Liveness
  * Speechiness

* Correlação 

# PCA
Os dados foram colocado na mesma escala para aplicar o PCA com redução para 2 colunas. Depois no dataset original foi adionado as 2 colunas como nova features.

# K-means
Os dados foram agrupados utilizando o K-means e o seu valor foi adicionado no dataset como uma nova feature.

# Sistema de recomendação 
Distância Euclidiana