# Atlantico-Avanti
Aqui postarei as respostas da minhas atividades requisitadas ao longo do bootcamp de Machine Learning
1. Explique, com suas palavras, o que é machine learning?
2. Explique o conceito de conjunto de treinamento, conjunto de validação e
conjunto de teste em machine learning.
3. Explique como você lidaria com dados ausentes em um conjunto de dados
de treinamento.
4. O que é uma matriz de confusão e como ela é usada para avaliar o
desempenho de um modelo preditivo?
5. Em quais áreas (tais como construção civil, agricultura, saúde, manufatura,
entre outras) você acha mais interessante aplicar algoritmos de machine
learning?

1. Machine learning é uma área da inteligência artificial que envolve o desenvolvimento de algoritmos e modelos que permitem que computadores aprendam a partir de dados. Em vez de serem explicitamente programados para realizar uma tarefa, esses modelos são treinados com grandes quantidades de dados para identificar padrões e fazer previsões ou tomar decisões. Basicamente, é um método para permitir que máquinas melhorem seu desempenho em uma tarefa específica através da experiência.

2. 
Conjunto de treinamento: É o conjunto de dados usado para treinar o modelo. Os algoritmos de machine learning ajustam os parâmetros internos do modelo com base nos dados de treinamento para minimizar o erro e melhorar o desempenho.
Conjunto de validação: É usado para ajustar os hiperparâmetros do modelo e evitar o overfitting (quando o modelo se ajusta demais aos dados de treinamento e não generaliza bem para novos dados). O desempenho no conjunto de validação é usado para comparar diferentes modelos ou configurações.
Conjunto de teste: É um conjunto de dados separado que não foi usado durante o treinamento ou validação. Ele é usado para avaliar o desempenho final do modelo e fornecer uma estimativa de quão bem ele generaliza para novos dados.

3. 
Lidar com dados ausentes é uma parte crucial da preparação de dados. Existem uma série de abordagems que me permitem trabalhar com um conjunto de dados
a despeito dessas lacunas. Uma delas é a remoção de linhas ou colunas, caso os dados - em formato csv por exemplo - apresentem linhas ou colunas ausentes, pode ser apropriado remover essas linhas ou colunas inteiras.
É também possível substituir os valores ausentes por valores estimados, como a média, mediana ou moda dos valores conhecidos.
Há a possibilidade de utilizar algoritmos de machine learning para prever os valores ausentes com base nas outras características presentes no conjunto de dados.

5. 
Uma matriz de confusão é uma ferramenta para avaliar o desempenho de um modelo de classificação. Ela compara as previsões do modelo com os valores reais e organiza esses resultados em uma matriz que mostra:

Verdadeiros positivos (TP): Casos em que o modelo previu corretamente a classe positiva.
Falsos positivos (FP): Casos em que o modelo previu incorretamente a classe positiva.
Verdadeiros negativos (TN): Casos em que o modelo previu corretamente a classe negativa.
Falsos negativos (FN): Casos em que o modelo previu incorretamente a classe negativa.
A partir dessa matriz, várias métricas podem ser calculadas, como precisão, recall, F1-score, entre outras, para fornecer uma visão detalhada do desempenho do modelo.

5. 
Acredito que uma das áreas mais interessantes da implementação de ML é na processamento de linguagem natural, nesta área observa-se aplicações muito relevantes tais
como identificação de discurso de ódio e melhorar a qualidade de traduções - vide os métodos de empresas como a deepl.
