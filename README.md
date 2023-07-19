Este é um projeto de Ciência de Dados que tem como objetivo desenvolver um modelo de máquina preditiva para classificar companhias
com potencial de falência, de acordo com os Dados de falência do Taiwan Economic Journal para os anos de 1999-2009.
Pensando na otimização do tempo, a etapa de análise exploratória dos dados foi automatizada com a utilização do pacote 'dataprep'.
Sendo assim, a Análise é mais generalista, com foco na distribuição das variáveis e suas correlações.
Também foi utilizada a biblioteca'feature engine', com o objetivo de automatizar a tarefa de seleção de variáveis e
tornar o modelo computacionalmente menos oneroso.

O projeto consiste na seguintes etapas:
  * Análise exploratória dos dados, de forma manual, mais simples e com menos insights;
  * Pré-processamento dos dados com split em dados de treino e teste, seleção de variáveis para o modelo e padronização dos dados;
  * Modelagem de máquinas preditivas, com análise de desempenho de vários modelos testados, tunagem de hiperparâmetros e elaboração
    de um modelo Ensemble de Classificador de Votação.

A principal métrica para avaliação do desempenho dos modelos é o Recall Score (revocação).
Dessa forma, os melhores modelos serão aqueles com menores indicações de falsos negativos.

Enjoy!
