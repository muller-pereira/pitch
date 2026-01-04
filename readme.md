# 🍊 Previsão e Classificação da Qualidade de Laranjas com Aprendizado de Máquina

> Este projeto aplica técnicas de Aprendizado de Máquina supervisionado para prever e classificar a qualidade de laranjas a partir de características físicas e químicas, utilizando dados reais. O estudo compara modelos de regressão e classificação, enfatizando interpretação, robustez e boas práticas de avaliação.
---

## 📌 Objetivos
### 🎯 Objetivo Geral

> Investigar a relação entre características físicas e químicas das laranjas e sua qualidade final, utilizando modelos de regressão e classificação baseados em aprendizado de máquina.
---

### 🎯 Objetivos Específicos

* Realizar análise exploratória dos dados (EDA)

* Prever a qualidade contínua das frutas por meio de Regressão Linear

* Classificar frutas em boa ou baixa qualidade usando Perceptron

* Comparar os fatores mais relevantes em cada abordagem

* Avaliar a robustez do classificador com validação cruzada
---

## 📊 Base de Dados

Dataset real obtido no Kaggle.

Cada amostra representa uma fruta com atributos físicos e químicos.

Principais variáveis utilizadas:

* Brix (Sweetness) – doçura

* pH (Acidity) – acidez

* Softness – maciez

* Ripeness – maturação

* HarvestTime – tempo de colheita

* Quality – qualidade (1 a 5, contínua)

Para a tarefa de classificação:

* Quality ≥ 3 → Boa qualidade

* Quality < 3 → Baixa qualidade
---

## 🧪 Metodologia

### Análise Exploratória de Dados (EDA)

* Histogramas, boxplots, scatterplots

* Mapa de correlação

* Análise de variáveis qualitativas e quantitativas
---

### Regressão Linear

* Previsão do valor contínuo da qualidade

* Dados normalizados (StandardScaler)

* Interpretação dos coeficientes
---

### Classificação com Perceptron

* Classificação binária (boa × ruim)

* Análise dos pesos do modelo

* Matriz de confusão e métricas de desempenho
---

### Validação Cruzada

* Stratified 5-fold cross-validation

* Métrica: F1-score ponderado

## 📈 Principais Resultados
🔹 Regressão Linear

* Brix (doçura) apresentou o maior impacto positivo sobre a qualidade

* HarvestTime apresentou impacto negativo relevante

* Softness, pH e Ripeness apresentaram efeitos secundários
---

🔹 Perceptron

* Acurácia ≈ 79%

* F1-score ponderado ≈ 0,84 (validação cruzada)

Variáveis mais importantes:

* Brix (positivo)

* HarvestTime (negativo)

* Softness (negativo)
---
> Os resultados mostraram consistência entre regressão e classificação, com boa interpretabilidade dos modelos.
---

## ⚠️ Limitações

* Base de dados pequena e desbalanceada

* Dificuldade em identificar a classe minoritária (baixa qualidade)

* Modelos lineares não capturam relações não lineares mais complexas
---

## 🚀 Trabalhos Futuros

* Ampliação e balanceamento do conjunto de dados

* Teste de modelos não lineares (SVM, redes neurais, regressão polinomial)

* Ajuste do limiar de classificação

* Inclusão de variáveis ambientais e temporais
---

## 🛠️ Tecnologias Utilizadas

* Python

* Pandas

* NumPy

* Matplotlib

* Seaborn

* Scikit-learn
---
## 🧠 Conclusão

> Este projeto demonstra que modelos simples e interpretáveis, quando bem fundamentados por análise exploratória e avaliação adequada, são capazes de fornecer previsões e classificações confiáveis, contribuindo para a tomada de decisão no controle de qualidade agrícola.
---
## 👤 Autor

Müller Pereira

>Professor de Matemática | Ciência de Dados | Aprendizado de Máquina

---
