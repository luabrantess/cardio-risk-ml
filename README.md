# Heart Disease ML Comparison 🩺

Este projeto utiliza técnicas de Machine Learning para prever o risco de doenças cardíacas com base em indicadores clínicos. O objetivo principal foi comparar o desempenho de diferentes algoritmos de classificação e entender quais variáveis (como dor no peito, colesterol e frequência cardíaca) mais influenciam o diagnóstico.

## 🚀 O que foi feito

1.  **Exploração e Limpeza de Dados:** Tratamento de valores duplicados e análise estatística inicial.
2.  **Feature Engineering:** Criação de novas variáveis de interação (ex: `thal_chol`) para testar se a combinação de fatores aumentava o poder preditivo.
3.  **Processamento:** Normalização dos dados para garantir que modelos sensíveis à escala (como KNN e Regressão Logística) funcionassem corretamente.
4.  **Modelagem e Comparação:** Treinamento e teste de três algoritmos distintos para avaliar o melhor equilíbrio entre acurácia e interpretação clínica.
5.  **Análise de Importância:** Geração de gráficos.
## 📊 Comparativo de Modelos

| Algoritmo | Estilo | F1-Score | Ponto Forte |
| :--- | :--- | :--- | :--- |
| **Random Forest** | Floresta de Árvores | **0.86** | **Vencedor:** Melhor capacidade de captura de padrões complexos. |
| **KNN** | Vizinhança (K=5) | 0.81 | Simplicidade e intuição baseada em casos similares. |
| **Regressão Logística** | Linear | 0.72 | Excelente para explicar o risco (Odds Ratio) de cada variável. |

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3.12
* **Bibliotecas de Dados:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn
* **Visualização:** Matplotlib, Seaborn
* **Ambiente:** Google Colab

---
Projeto desenvolvido para fins de estudo em Machine Learning.
