# Deteccao-de-Fraudes-em-Transacoes-Bancarias-utilizando-Machine-Learning

## Detecção de Fraudes em Transações Bancárias utilizando Machine Learning

### Visão Geral

Este projeto apresenta um estudo completo de Machine Learning para detecção de fraudes em transações bancárias utilizando Python.

Foram comparados diversos algoritmos de classificação supervisionada em um conjunto de dados público contendo milhares de transações financeiras, sendo o objetivo identificar automaticamente operações fraudulentas.

Ao final dos experimentos, o algoritmo Gradient Boosting apresentou o melhor desempenho geral, alcançando os maiores índices de precisão, revocação e F1-Score.

---

### Objetivos

- Detectar transações fraudulentas
- Comparar diferentes modelos de Machine Learning
- Avaliar métricas para bases altamente desbalanceadas
- Selecionar o melhor algoritmo
- Demonstrar um pipeline completo de Data Science

---

### Dataset

Dataset público utilizado:

Credit Card Fraud Detection Dataset

https://storage.googleapis.com/download.tensorflow.org/data/creditcard.csv

Características:

- 284.807 transações
- 492 fraudes
- 30 atributos
- Base altamente desbalanceada

---

### Tecnologias

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

---

### Fluxo do Projeto

1. Importação dos dados
2. Limpeza
3. Análise Exploratória
4. Tratamento do desbalanceamento
5. Separação treino/teste
6. Treinamento dos modelos
7. Avaliação
8. Escolha do melhor modelo

---

## Modelos Comparados

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- AdaBoost

---

### Métricas Avaliadas

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

---

### Resultado Final

O modelo **Gradient Boosting** apresentou o melhor desempenho entre todos os algoritmos testados.

Principais vantagens observadas:

- Excelente capacidade de identificar fraudes
- Alto Recall
- Melhor equilíbrio entre Precision e Recall
- Elevado F1-Score
- Baixa taxa de falsos positivos

---

### Conclusão

Este projeto demonstra um pipeline completo para detecção de fraudes financeiras utilizando Machine Learning.

Além da construção dos modelos, foi realizada uma análise comparativa entre diferentes algoritmos, evidenciando a importância da escolha adequada do modelo em problemas de classificação desbalanceada.

Os resultados mostram que técnicas de Boosting podem oferecer desempenho superior em cenários de detecção de fraudes.

---

### Autor

Iacer Duarte
