## Projeto de Previsão de Churn
Este é um projeto de previsão de churn, onde utilizamos técnicas de aprendizado de máquina para prever a probabilidade de clientes cancelarem seus serviços. O conjunto de dados utilizado neste projeto contém informações sobre clientes de uma empresa e se eles cancelaram o serviço (churn) ou não.

## Bibliotecas Utilizadas
Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow

## Arquivo do Projeto
O arquivo utilizado no projeto é train_churn.csv, que contém os dados dos clientes.

## Preparação e Análise do Dataset
O dataset foi carregado utilizando o Pandas, e foram realizadas as seguintes etapas de preparação e análise:

Remoção da coluna "Unnamed: 0"
Remoção de valores nulos
Remoção de valores negativos em colunas específicas
Conversão de colunas float para int
Análise exploratória de dados com gráficos de histograma
Balanceamento do dataset
Padronização de valores em colunas categóricas
Binarização do dataset
Codificação de labels com LabelEncoder
Conversão de int para float, removendo valores NaN
Normalização de Dados
As colunas tempoDeServico, FaturaMensal e FaturaTotal foram normalizadas utilizando o MinMaxScaler.

## Divisão do Dataset
O dataset foi dividido em features e labels, e posteriormente em conjuntos de treinamento e teste.

## Construção e Treinamento do Modelo
O modelo de previsão de churn foi construído utilizando TensorFlow com a API Keras. O modelo possui 3 camadas densas com ativação ReLU e uma camada de saída com ativação sigmoid. O modelo foi compilado com otimizador Adam e função de perda binary_crossentropy.

## Resultados da Previsão
O modelo foi treinado utilizando os dados de treinamento e avaliado com os dados de teste. Além disso, foram realizadas previsões utilizando um conjunto de validação contendo as 10 primeiras instâncias do dataset.

Você pode expandir este README adicionando mais detalhes sobre o projeto, sua motivação, análises adicionais dos dados, métricas de avaliação do modelo, entre outros aspectos relevantes.
