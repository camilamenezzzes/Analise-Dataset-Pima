# 👩‍⚕️ Análise de Dados e Classificação de Diabetes (Pima Indians Dataset)

Este repositório documenta um projeto completo de **Análise Exploratória de Dados (EDA)** e **Modelagem Preditiva** (usando Aprendizado Supervisionado) aplicada ao famoso **Pima Indians Diabetes Dataset** da UCI.

O foco é construir um modelo de Machine Learning capaz de prever, com precisão, a ocorrência de diabetes em mulheres da tribo Pima com base em variáveis clínicas e diagnósticas.

## 🎯 Objetivos do Projeto e Metodologia

Nosso objetivo central é aplicar o **Aprendizado Supervisionado** para resolver um problema de classificação binária (Diabetes: Sim ou Não).

* **Fase 1: Preparação de Dados (EDA)**
    * Limpeza e Pré-processamento: Tratamento de valores faltantes e *outliers* na base de dados.
    * Análise Exploratória: Visualização e estudo das distribuições e correlações entre as variáveis preditoras e o *outcome*.
* **Fase 2: Modelagem Preditiva (Regressão Logística)**
    * Implementação do algoritmo de **Regressão Logística** para modelar a probabilidade de ocorrência de diabetes.
    * Treinamento e validação do modelo.
* **Fase 3: Avaliação de Desempenho**
    * Avaliação do modelo utilizando métricas-chave para classificação, como Acurácia, Precisão, Recall e Curva ROC/AUC.

## 🛠️ Tecnologias Utilizadas

* `Python`
* `Pandas` e `NumPy` para manipulação e processamento de dados.
* `Matplotlib` e `Seaborn` para visualização e EDA.
* `Scikit-learn` para implementação do modelo de **Regressão Logística** e avaliação de métricas.

## 📁 Estrutura do Repositório

* `notebooks/`: Contém os Jupyter Notebooks com todo o código (EDA, Modelagem e Avaliação).
* `data/`: O dataset original e versões tratadas.
* `src/`: Scripts Python auxiliares (se aplicável).
