# Basic in Machine Learning

Machine Learning (ML) é um subcampo da Inteligência Artificial (IA) que se concentra no desenvolvimento de algoritmos e modelos que permitem que computadores aprendam a partir de dados e façam previsões ou decisões sem serem explicitamente programados para executar essas tarefas.

## Principais Conceitos de Machine Learning

### 1. Aprendizado Supervisionado
O modelo é treinado com dados rotulados, ou seja, ele aprende a partir de um conjunto de entradas e saídas esperadas.  
**Exemplo**: Classificação de e-mails como spam ou não spam.

### 2. Aprendizado Não Supervisionado
O modelo trabalha com dados não rotulados e tenta identificar padrões ou estruturas nesses dados.  
**Exemplo**: Agrupamento de clientes com base em seu comportamento de compra.

### 3. Aprendizado por Reforço
O modelo aprende através de tentativa e erro, recebendo recompensas ou penalidades com base nas ações tomadas.  
**Exemplo**: Treinar um agente para jogar xadrez ou controlar um robô.

## Técnicas para Valores Ausentes

A remoção de dados faltantes é recomendada quando há 5% ou menos de valores ausentes e estes sejam **MCAR** (Missing Completely at Random). Nesse caso, remover os dados seria equivalente a excluir aleatoriamente alguns registros, mantendo a distribuição original das variáveis. Nessa técnica, são mantidas apenas as linhas com dados completos.

A imputação de dados preenche os valores ausentes com estimativas ou cálculos. As principais técnicas são:

- **Média, Mediana ou Moda**: Preencher valores numéricos com a média ou mediana e categóricos com a moda.
- **Valor Específico**: Usar um valor padrão (ex.: 0, -1 ou "Desconhecido").
- **KNN (K-Nearest Neighbors)**: Estimar valores com base em registros semelhantes.
- **Modelos Preditivos**: Usar algoritmos como regressão para prever os valores ausentes com base em outras variáveis.

Algoritmos como **árvores de decisão** e **Random Forests** lidam nativamente com dados ausentes, utilizando mecanismos internos para tratar esses valores, como a divisão de dados com base na presença ou ausência de informações.

## Matriz de Confusão

A matriz de confusão é uma tabela usada para avaliar o desempenho de um modelo de classificação, comparando previsões com os valores reais. Em problemas binários, ela contém quatro entradas:

- **Verdadeiros Positivos (VP)**: previsões corretas da classe positiva.
- **Falsos Positivos (FP)**: previsões incorretas da classe positiva.
- **Verdadeiros Negativos (VN)**: previsões corretas da classe negativa.
- **Falsos Negativos (FN)**: previsões incorretas da classe negativa.

A matriz permite calcular métricas como **acurácia**, **precisão**, **recall** e **F1-score**, ajudando a identificar onde o modelo está cometendo erros e ajustar seu desempenho.

---

Particularmente, eu gosto da área de saúde, pois posso aplicar esse conceito para melhorar o diagnóstico de doenças usando machine learning.
