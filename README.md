![image](https://github.com/Fonzorg/proyecto_individual_Cripto/assets/108815192/bf8a04cb-34c5-411f-9ce9-3d121ab9ab66)

# Proyecto Individual Cripto
Proyecto Individual N°2: Criptomonedas
Alfonzo Rubianes Gravier
Henry - DA – PT02

En el siguiente trabajo se ha explorado los datos extraídos del api de CoinGecko. 
CoinGecko es un sitio web y una aplicación móvil que se utiliza para agregar los datos sobre el rendimiento de la mayoría de las criptomonedas disponibles, con más de 10,000 criptoactivos diferentes rastreados en más de 800 intercambios de todo el mundo.

# EDA

Luego de extraer los datos sobre los criptoactivos aludidos para un momento determinado (en este caso, la última actualización de los datos sobre los que se trabajo fue el día de hoy, 25-8-2023), se exploro la consistencia de los mismos, proceso este incluido en el EDA (eda.ipynb) ubicado en el presente repositorio. En dicho EDA, además de la exploración propiamente dicha, se encontrará un Diccionario del dataset base sobre el que se trabaja para lograr los objetivos del EDA.
El objetivo de dicho EDA fue aportar criterios que faciliten la elección de una cartera acotada a 10 criptomonedas.
Finalmente, producto de dicho análisis exploratorio, se optó por seguir como criterio de elección la presencia de valores atípicos en las variables precio, capitalización de mercado y volumen de operación, priorizando las que presentan dicho comportamiento atípico en la mayor cantidad de dichas variables.
Dicha cartera fue definida con las siguientes criptomonedas:
Las criptomonedas seleccionadas son:
Bitcoin (BTC)
Ethereum (ETH)
Tether (USDT)
Binance Coin (BNB)
Solana (SOL)
XRP
Lido Staked Ether
USD Coin
GALA
TrueUSD

Generándose con ellas un dataset denominado cartera_cripto
 ![image](https://github.com/Fonzorg/proyecto_individual_Cripto/assets/108815192/c175dc79-282d-4159-98f5-0216f91b6f32)


Y el archivo cartera_cripto.csv.

# Serie de tiempo.

Una vez definida la cartera de criptomonedas sobre la que trabajar, se ha generado otro dataset considerando una serie de tiempo. 
He considerado los ultimos 5 años. 
Si fuese menos, siendo un mercado tan volátil, podría perder representatividad; y por otro lado, porque más atrás en el tiempo, parte de las criptomonedas consideradas o no eran relevantes como hoy, o no existían.

El dataset resultante es serie_cartera_cripto:
 ![image](https://github.com/Fonzorg/proyecto_individual_Cripto/assets/108815192/6b301583-55fd-4fbc-be74-b9b592749135)


Y el archivo serie_cartera_cripto.csv.

# KPI

KPI es la sigla en inglés que significa “Indicador Clave de Rendimiento”. 
Son métricas cuantitativas muestran, en el caso particular de este proyecto, el desempeño de cada criptomoneda componente de la cartera definida en forma comparativa a los efectos de la toma de decisión respecto a la inversión, plazo de inversión y monto de inversión en cada una de ellas.

He considerado como KPIs la volatilidad del precio, la liquidez y la capitalización de mercado. 

Capitalización de mercado: La capitalización de mercado se utiliza para evaluar el tamaño relativo de una criptomoneda en comparación con otras. Las criptomonedas con una mayor capitalización de mercado suelen ser menos volátiles y más líquidas.

Volatilidad: La volatilidad se mide mediante la desviación estándar del precio de una criptomoneda en un período determinado. Un alto nivel de volatilidad puede indicar un mayor riesgo para los inversores.

Liquidez: La liquidez se mide mediante el volumen de operaciones. Un alto nivel de liquidez puede indicar una mayor facilidad para comprar y vender una criptomoneda.

# Conclusiones Personales.

Teniendo en cuenta estos aspectos, aquí presento tres opciones de cartera:

1-	Cartera conservadora: Tether (USDT) y USD Coin.
2-	Cartera moderada: Bitcoin (BTC), Ethereum (ETH) y Binance Coin (BNB).
3-	Cartera agresiva: Solana (SOL), XRP, Lido Staked Ether, GALA y TrueUSD.

Es importante tener en cuenta que estas son solo sugerencias y que siempre debe hacer su propia investigación antes de invertir en cualquier criptomoneda.

Alfonzo Rubianes - agosto 2023

