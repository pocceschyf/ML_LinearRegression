🤖 Treinamento e Comparação de Modelos de Regressão
Este projeto demonstra o treinamento, avaliação e comparação de diferentes modelos de Machine Learning (Aprendizado de Máquina) para uma tarefa de Regressão. O objetivo é analisar o desempenho de cada algoritmo em um conjunto de dados sintético.

📁 Conteúdo do Repositório
Trabalho treino machine learning.ipynb: O notebook principal contendo todo o código, treinamento de modelos, análise e visualizações.

🛠️ Tecnologias Utilizadas
O projeto foi desenvolvido em Python e utiliza as seguintes bibliotecas:

scikit-learn (sklearn): Para implementação dos modelos de regressão (Árvore de Decisão, K-Nearest Neighbors e Regressão Linear), geração de dados sintéticos (make_regression) e divisão de conjuntos de treino/teste.

matplotlib: Para visualizações gráficas, incluindo a análise do impacto de hiperparâmetros.

pandas: Para manipulação de dados e exibição da tabela de resultados.

🧪 Modelos e Métricas de Avaliação
Foram treinados e comparados três modelos de regressão:

Decision Tree Regressor (Árvore de Decisão)

K-Nearest Neighbors Regressor (KNN)

Linear Regression (Regressão Linear)

O desempenho dos modelos foi avaliado usando as seguintes métricas de regressão:

MSE (Mean Squared Error): Erro Quadrático Médio.

MAE (Mean Absolute Error): Erro Absoluto Médio.

R² (R-squared ou Coeficiente de Determinação): Indica a proporção da variância na variável dependente que é previsível a partir das variáveis independentes (quanto mais próximo de 1, melhor).


Conclusão dos Resultados:

O modelo de Regressão Linear apresentou o melhor desempenho geral, com o menor MSE e o maior R² (0.634106).

A análise de hiperparâmetros (como o max_depth na Árvore de Decisão) foi crucial para ilustrar a famosa troca entre Viés (Underfitting) e Variância (Overfitting).

Um modelo muito simples (alto Viés) não aprende os detalhes do conjunto de treino.

Um modelo excessivamente complexo (alta Variância) memoriza os dados de treino, falhando em dados novos (teste).

A otimização de hiperparâmetros busca o ponto ideal onde o modelo é complexo o suficiente para aprender o padrão, mas não a ponto de confundir ruído com informação.
