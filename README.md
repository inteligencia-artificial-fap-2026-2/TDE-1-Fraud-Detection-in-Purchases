# Detecção de Fraudes em Compras

## 📋 Descrição

A detecção de fraudes em cartões de crédito é fundamental para proteger consumidores e instituições financeiras contra atividades ilícitas.

O uso de técnicas de **Aprendizado de Máquina (Machine Learning)** tem papel central nesse processo, possibilitando a identificação de padrões complexos e anomalias em dados de transações.

Por meio da análise automatizada de grandes volumes de informações, algoritmos podem detectar comportamentos suspeitos com rapidez e precisão. Essa capacidade é essencial para:

- Mitigar riscos;
- Prevenir perdas financeiras;
- Identificar comportamentos suspeitos;
- Aumentar a segurança das transações.

Ao adotar métodos avançados de aprendizado de máquina, empresas podem fortalecer suas estratégias de segurança e proporcionar transações mais seguras aos seus clientes.

---

## 📊 Dataset

O conjunto de dados utilizado neste projeto é composto por aproximadamente **100 mil registros de transações online**, fornecidos pela empresa **Vesta**.

Cada transação é representada por um conjunto de atributos que incluem informações relacionadas à compra e à identidade/conexão associada à transação, como:

- Valor da transação;
- Tempo da transação;
- Informações de identidade;
- Informações de dispositivo;
- Informações relacionadas à conexão e ao ambiente da transação.

O dataset faz parte da competição **IEEE-CIS Fraud Detection**, disponibilizada no Kaggle.

- **Dataset:** [IEEE-CIS Fraud Detection](https://www.kaggle.com/c/ieee-fraud-detection/overview)
- **Descrição dos campos:** [Data Description](https://www.kaggle.com/c/ieee-fraud-detection/discussion/101203)

---

## 🎯 Objetivo Principal

Este projeto aborda um problema de **Classificação Binária**, cujo objetivo é determinar se uma determinada transação é:

- **Legítima**
- **Fraudulenta**

A variável alvo indica, portanto, a ocorrência ou não de fraude em cada transação.

Para comparar o desempenho das soluções e modelos candidatos, serão utilizadas principalmente as seguintes métricas:

- **Acurácia Balanceada (Balanced Accuracy)**
- **Área sob a Curva ROC (ROC AUC)**

Essas métricas são especialmente importantes devido ao **desbalanceamento entre transações legítimas e fraudulentas** presente nesse tipo de problema.

---

## 🧠 Técnicas Envolvidas

Durante o desenvolvimento do projeto, serão exploradas técnicas relacionadas a:

- Processamento de dados tabulares;
- Análise exploratória dos dados;
- Balanceamento de dados;
- Tratamento de dados faltantes;
- Preparação e transformação de atributos;
- Classificação binária;
- Avaliação e comparação de modelos de Machine Learning.

---

## 🚧 Desafios

Os principais desafios abordados neste projeto são:

### 1. Processamento de dados tabulares

Preparar e transformar os dados para utilização eficiente pelos modelos de Machine Learning.

### 2. Desbalanceamento dos dados

Como transações fraudulentas representam uma parcela menor do conjunto de dados, será necessário avaliar estratégias adequadas para evitar modelos enviesados para a classe majoritária.

### 3. Tratamento de dados faltantes

Identificar valores ausentes e definir estratégias apropriadas para seu tratamento.

### 4. Classificação de transações fraudulentas

Construir modelos capazes de distinguir transações legítimas de fraudulentas, buscando minimizar erros e melhorar a capacidade de detecção de fraudes.

---

## 📈 Métricas de Avaliação

### Balanced Accuracy

A **Acurácia Balanceada** considera o desempenho do modelo em cada classe separadamente, sendo especialmente útil em conjuntos de dados desbalanceados.

### ROC AUC

A **Área sob a Curva ROC (ROC AUC)** avalia a capacidade do modelo de distinguir entre transações legítimas e fraudulentas em diferentes limiares de classificação.

Quanto maior o valor da ROC AUC, melhor a capacidade do modelo de separar as duas classes.

---

## 🔗 Referências

- [IEEE-CIS Fraud Detection — Kaggle](https://www.kaggle.com/c/ieee-fraud-detection/overview)
- [Descrição dos campos do dataset](https://www.kaggle.com/c/ieee-fraud-detection/discussion/101203)