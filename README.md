
# 📊 Projeto Telecom X — Previsão de Cancelamento de Clientes

Este projeto faz parte do desafio **Telecom X - Parte 2**, com foco em **Data Science aplicada à retenção de clientes**. A missão foi desenvolver modelos de Machine Learning capazes de prever com antecedência quais clientes estão mais propensos a cancelar seus serviços.

---

## 🎯 Objetivo

Antecipar o cancelamento de clientes por meio de algoritmos de classificação, permitindo que a empresa possa agir preventivamente para reduzir a evasão.

---

## 🧠 Etapas do Projeto

1. **Importação e Exploração Inicial dos Dados**  
   Carregamento da base de clientes e visualização geral das colunas e tipos de dados.

2. **Pré-processamento**  
   - Remoção de colunas irrelevantes ou redundantes  
   - Codificação de variáveis categóricas (One-Hot Encoding)  
   - Análise de balanceamento da variável-alvo (cancelamento)  
   - Aplicação de técnicas como **SMOTE** para equilibrar as classes  
   - Normalização dos dados para modelos sensíveis à escala

3. **Análise Exploratória (EDA)**  
   - Visualização da relação entre tempo de contrato, valor mensal e evasão  
   - Matriz de correlação para variáveis numéricas  
   - Boxplots e scatter plots para identificar padrões

4. **Modelagem Preditiva**  
   Modelos testados:
   - Regressão Logística (com normalização)  
   - Random Forest  
   - KNN  
   - Árvore de Decisão

   Cada modelo foi avaliado com métricas como:
   - Acurácia  
   - Precisão  
   - Recall  
   - F1-Score  
   - Matriz de Confusão

5. **Interpretação dos Resultados**  
   - Avaliação da importância das variáveis  
   - Identificação de fatores-chave que influenciam a evasão  
   - Escolha do melhor modelo para uso estratégico

---

## 🏆 Resultados

- O modelo de **Regressão Logística** apresentou o melhor desempenho geral, com equilíbrio entre **precisão**, **recall** e **interpretação dos coeficientes**.
- Fatores como **tempo de contrato**, **valor mensal** e **serviços adicionais contratados** foram os principais influenciadores da evasão.

---

## 💡 Conclusão Estratégica

Este projeto demonstra como a aplicação de técnicas de ciência de dados pode gerar insights relevantes e apoiar decisões estratégicas. Com base nos resultados, a empresa pode:

- Criar campanhas de retenção para clientes com contratos mais curtos
- Oferecer pacotes promocionais para quem paga valores mensais mais altos
- Usar o modelo preditivo em tempo real para monitorar e agir antes da evasão acontecer

---

## 🛠️ Tecnologias Utilizadas

- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Imbalanced-learn (SMOTE)

---

## ✍️ Autor

Projeto adaptado por **João Vitor Lima Magalhães**, com base no desafio proposto na trilha de aprendizado em Ciência de Dados.
