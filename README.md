# Spark-MLLib-Radom-Forest

O intuito deste codigo é mostrar como se aplicar o algoritmo Random Forest através do PySpark, mostrar as bibliotecas, fazer análise exploratória, alguns jeitos de programar para poder fazer a limpeza e o pré-processamento dos dados.

Vou estar utilizando o dataset de um banco para fazer uma análise de crédito com o objetivo de classificar clientes de acordo com a possibilidade de pagar ou nao o credito.

### Random Forest:

#### Descrição

- Um dos algoritmos mais populares.
- É um algoritmo de Método Ensemble.
- Um modelo de Random Forest constrói diversos modelos e cada modelo é usado para prever resultados de forma individual. Uma votação é feita pelo Random Forest para escolher o melhor modelo.

#### Vantagens
- Normalmente oferece boa acurácia
- Eficiente com muitas variáveis preditoras
- Funciona muito bem de forma paralelizada
- Excelente com valores missing

#### Desvantagens
- Mais lento
- Bias podem ocorrer com frequência

#### Aplicação
- Pesquisa científica
- Diagnóstico médico
