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

## 📝 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/SEU_USUARIO/7daysofcode3.git

2. Instale as bibliotecas necessárias:
pip install pandas numpy matplotlib seaborn scikit-learn

3. Execute o notebook 7daysofcode3.ipynb no ambiente de sua preferência (Jupyter Notebook, Jupyter Lab, Databricks, Google Colab).

📂 Estrutura do Repositório
bash
Copiar
Editar

🚩 Reflexões Finais
Neste desafio, foram realizadas análises importantes sobre divisão de dados:

A divisão fixa permite uma separação clara para validação final.

A validação cruzada oferece maior robustez para avaliação de modelos durante o processo de treino.

Para fases futuras, o foco será testar modelos (Árvore de Classificação, Floresta Aleatória, XGBoost) utilizando estas estratégias de treino/validação.

📢 Observação
Este projeto é parte do desafio educacional #7DaysOfCode proposto pela Alura, com objetivo didático para reforçar conceitos práticos de Machine Learning.

📊 Desenvolvido por Gláuber Lopes Bomtempo

go
Copiar
Editar
