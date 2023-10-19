# Golf-Regress

# Projeto de Classificação de Jogar Golfe

Este é um projeto de classificação que utiliza regressão logística para prever se é apropriado jogar golfe com base nas condições climáticas, temperatura, umidade e vento.

## Conjunto de Dados

Os dados são carregados a partir de um arquivo 'golf_df.xlsx' usando a biblioteca Pandas.

## Pré-processamento de Dados

- As variáveis categóricas (clima, temperatura, umidade, vento, jogar) são codificadas em valores numéricos usando LabelEncoder.

## Modelo de Regressão Logística

- O modelo de regressão logística é treinado usando as características (condições climáticas, temperatura, umidade, vento) como variáveis independentes e a variável 'jogar' como a variável de destino.

## Resultados

- O modelo faz previsões e adiciona uma coluna 'prediction' ao DataFrame original.

- A coluna 'real' é adicionada com os valores reais para comparação.

## Uso

- Você pode usar este modelo para prever se é apropriado jogar golfe com base nas condições climáticas.

## Licença

Este projeto é distribuído sob a Licença. Consulte o arquivo LICENSE para obter mais informações.
