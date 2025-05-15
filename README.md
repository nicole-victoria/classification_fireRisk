# Classificação do Risco de Fogo na cidade de Altamira- PA

Os incêndios florestais são um problema recorrente no Brasil, especialmente na região amazônica, que é considerada o bioma mais atingido por incêndios florestais no país, tendo as cidades de Altamira e São Félix do Xingu como as mais afetadas Por isso, o objetivo desse projeto é classificar os riscos de incêndio no município de Altamira como baixo, médio e alto, a fim de servir de suporte para tomadas de decisões estratégicas para prevenir ocorrências de incêndio.

---
## 🎲 Base de dados 

Todas as bases de dados utilizadas são de domínio público

- 🌧️ Dados metereológicos: [INMET](https://tempo.inmet.gov.br/TabelaEstacoes/A001) &nbsp;
- 🔥 Dados de queimadas: [INPE](https://terrabrasilis.dpi.inpe.br/queimadas/bdqueimadas/#exportar-dados).

> Os anos escolhidos para este projeto foram 2019 e 2020 devido à quantidade de dados disponíveis na Estação Metereológica de Altamira-PA e pelo Instituto Nacional de Pesquisas Espaciais(INPE)

## 🚀 Organização do Projeto

A [Parte 1](https://github.com/nicole-victoria/classification_fireRisk/blob/main/parte1.ipynb) corresponde à fase de de Limpeza e Processamento dos dados;

A [Parte 2](https://github.com/nicole-victoria/classification_fireRisk/blob/main/parte2.ipynb) corresponde à fase de Análise Estatística para escolha das melhores features e a Criação dos Modelos de ML.

## 📊 Algoritmos comparados e resultados

- Extra Trees: 95,2%
- Random Forest: 91,2%
- K-Nearest Neighbors(KNN): 89%
- Support Vector Machine(SVM): 86,6%

  > Os resultados correspondem ao valor médio da acurácia, mas o projeto também avalia os resultados para F1-score, Recall e Precision.
