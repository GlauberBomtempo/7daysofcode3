# Análise de Machine Learning - Classificação da Popularidade Musical 🎶

Este repositório contém a resolução do **3º Desafio** do projeto #7DaysOfCode - Machine Learning. O foco principal é realizar o pré-processamento de dados, criar uma variável binária para popularidade e explorar duas estratégias de divisão dos dados: divisão fixa e validação cruzada.

## 📌 Sobre o Projeto

Este projeto aborda as seguintes etapas:
- Limpeza e preparação dos dados;
- Criação da variável binária `popular_binaria` com base na popularidade das músicas;
- Criação de variável binária `artistas_relevantes` com base nos 5000 artistas mais populares;
- Aplicação de OneHotEncoding para variáveis categóricas;
- Divisão dos dados em treino, validação e teste via **divisão fixa**;
- Implementação de **validação cruzada StratifiedKFold** com 5 folds.

## 📊 Principais Etapas

- **Pré-processamento completo**: tratamento de colunas irrelevantes, criação de novas features e one-hot encoding.
- **Balanceamento monitorado**: análise da proporção de classes em todas as etapas.
- **Divisão dos dados**:
  - **Divisão Fixa**: 70% treino, 10% validação, 20% teste.
  - **Validação Cruzada (StratifiedKFold)**: 80% treino, 20% validação rotacionados em 5 folds.
- Comparação entre as duas estratégias de divisão para entender impactos no pipeline de machine learning.


##📊 Desenvolvido por Gláuber Lopes Bomtempo


