# LH_CD_LUIZFERNANDODEBARROSCAIXETA
Desafio Cientista de Dados - indicium 

Neste código foi desenvolvido o enunciado do Desafio Cientista de Dados - indicium: **Seu objetivo é desenvolver um modelo de previsão de preços a partir do dataset oferecido, e avaliar tal modelo utilizando as métricas de avaliação que mais fazem sentido para o problema.**

Para isso, foi utilizado o dataframe sugerido e acrescentadas as seguintes informações:

- distância de cada imóvel em relação a estação de metrô e ponto de ônibus mais próximos;

  Para isso foi utilizado: 'https://data.ny.gov/Transportation/MTA-Subway-Entrances-and-Exits-2024/i9wp-a4ja/about_data',
                            'https://data.cityofnewyork.us/Transportation/Bus-Stop-Shelters/qafz-7myz'

  (os arquivos estão disponíveis neste repositório)

- distância de cada imóvel em relação aos principais pontos turísticos da cidade;

- quantidade de quartos e banheiros da coluna 'nome' (extraído da coluna 'nome');

- número de crimes cometidos para cada 1000 habitantes de cada bairro_group;

Para isso foi utilizado: 'https://www.nyc.gov/site/nypd/stats/crime-statistics/historical.page',
                          'https://www.nyc.gov/site/nypd/bureaus/patrol/precincts-landing.page'
                          
(os arquivos estão disponíveis neste repositório)

E então, foi necessário realizar uma análise exploratória do dataframe, onde foram estudados:

- distribuição geográfica dos imóveis e tipos de imóvel ao longo de toda a cidade de Nova York;

![latitude_longitude](https://github.com/user-attachments/assets/1b3cf852-8db4-47f8-86d4-3407a0c4075f)

- análise de hipóteses para a precificação dos imóveis

Posteriormente, esse estudo e dados foram utilizados para treinar modelos de regressão com o objetivo de prever o valor do target 'price'. Para isso, foram utilizados os modelos XGBRegressor, Ridge, RandomForestRegressor, LinearRegression, ExtraTreesRegressor, LGBMRegressor e CatBoostRegressor. Para os testes, o modelo CatBoostRegressor foi o que apresentou melhor resultado, com parâmetros

--------------------------------------------------
Modelo: CatBoostRegressor
  Treino - R²: 0.6879, MAE: 27.5288, RMSE: 38.1353
  Teste  - R²: 0.5980, MAE: 30.8878, RMSE: 43.0422
--------------------------------------------------

Este modelo foi utilizado para precificar o imóvel enunciado pelo desafio.

Agradeço a oportunidade de participar deste desafio, que tornou-se muito produtivo para o meu desenvolvimento como estudante de ciência de dados.
