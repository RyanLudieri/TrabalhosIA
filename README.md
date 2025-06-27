# 🤖 Trabalhos de Inteligência Artificial (IA)

Este repositório reúne projetos de Inteligência Artificial com foco em Análise Exploratória de Dados (EDA) e aplicação de modelos de Aprendizado de Máquina.

## 📁 Projetos

### 1. 🧠 Projeto Final - Redes Neurais Artificiais (RNAs)

* **Objetivo:** Classificação de pacientes para identificar padrões relacionados à condição de Parkinson.
* **Dataset:** Dados de pacientes com Parkinson.
* **Modelos:** Rede Neural (MLPClassifier).
* **Metodologia:** Normalização de dados, análise de correlação, exploração de diferentes arquiteturas de rede e otimizadores.
* **Tecnologias:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`.

### 2. 📊 Análise Exploratória de Dados (EDA) com Modelagem Supervisionada para TNDs

* **Objetivo:** Identificar possíveis traços de Transtornos do Espectro Autista (TEA) em crianças, através de EDA e modelagem supervisionada.
* **Dataset:** Respostas de questionário (A1-A10), idade, pontuação Qchat-10 e características demográficas.
* **Modelos:** RandomForestClassifier, Regressão Logística.
* **Metodologia:** Pré-processamento, codificação e normalização de variáveis, balanceamento de classes (SMOTE), criação de novas features (faixas etárias).
* **Tecnologias:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`.

### 3. 👸 Classificação - Rede Neural, KNN e Árvore de Decisão (Princess Dataset)

* **Objetivo:** Classificar dados para um indicador (`Cured`) utilizando múltiplos modelos de classificação.
* **Dataset:** Características fictícias como "Phoenix Feather", "Unicorn Horn", etc.
* **Modelos:** Rede Neural (MLPClassifier), Árvore de Decisão (DecisionTreeClassifier), K-Nearest Neighbors (KNeighborsClassifier).
* **Metodologia:** Normalização de preditores, divisão em treino/teste (70/30), execuções múltiplas para avaliação robusta.
* **Tecnologias:** `numpy`, `pandas`, `seaborn`, `matplotlib`, `scikit-learn`.

### 4. 🔬 Classificação - Rede Neural, KNN e Árvore de Decisão para Diagnóstico de Câncer

* **Objetivo:** Diagnosticar câncer (Maligno/Benigno) aplicando diferentes modelos de classificação em dados de tumores.
* **Dataset:** `wdbc.data` (características de tumores).
* **Modelos:** Rede Neural (MLPClassifier), K-Nearest Neighbors (KNeighborsClassifier), Árvore de Decisão (DecisionTreeClassifier).
* **Metodologia:** Pré-processamento (remover ID, mapear diagnóstico para numérico, normalização), divisão em treino/teste.
* **Tecnologias:** `numpy`, `pandas`, `seaborn`, `matplotlib`, `scikit-learn`.
