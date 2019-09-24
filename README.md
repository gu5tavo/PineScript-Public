# Tradingview
Indicadores y estrategias en Pine Script para TradingView

[TrandingView Profile](https://www.tradingview.com/u/gu5tavo71/#published-scripts)

***

## Trend Channel [Gu5]
[Script Publish](https://www.tradingview.com/script/nApbXCts-Trend-Channel-Gu5/)

SMA200 determines the trend

Bullish trend, green candles. Downtrend, red candles.

If the market value is narrow to the SMA200 channel, yellow candles.
```
Setting recommended for SMA Range
BTCUSD = 100
EURUSD = 1000
SPX = 100
ETHUSD = 10
```

--

SMA200 determina la tendencia

Tendencia alcista, velas verdes. Tendencia bajista, velas rojas

Show Channel muestra el canal del al SMA200

El valor de 0.618 de SMA Range es arbitrario (No Backtesting). Cambia la amplitud de canal que determina cuando es rango (barras amarillas por estar muy cerca del SMA200, sin tendencia definida)

Range Multiplier adapta el indicador a distintos mercados 

***
## Mix1 : Ema Cross + Trend Channel [Gu5]
[Script Publish](https://www.tradingview.com/script/YflOVb17-Mix1-Ema-Cross-Trend-Channel-Gu5/)

Based on Trend Channel [Gu5]

Ema-crossover is added

Crossing alerts, only on trend

--

Basado en mi anterior indicador, Trend Channel [Gu5]

Se agrega Cruce de Medias Moviles (Ema-crossover)

Las alertas solo son en favor a la tendencia


***
## ROC Alert [Gu5]
[Script Publish](https://www.tradingview.com/script/KvX3zVVE-ROC-Alert-Gu5/)

If the value drops (or rises) SHARPLY, we will receive an alert

--

Cuando el valor sube ( o baja) ABRUPATMENTE, recibiremos un alerta

```
Setting recommended for ROC Alert
"ROC Length" setea la cantidad de velas a monitorear, (por defecto en 4 períodos)
"% Change" setea el porcentaje del valor, (por defecto en 1.5%) 
```

***
## ADX Di+ Di- [Gu5]
[Script Publish](https://www.tradingview.com/script/RNcqYq6w-ADX-Di-Di-Gu5/)

Fill indicates Strong Trend

Cross indicates End of Trend

--

El relleno indica una fuerte tendencia cuando el Di supera "Level Trend"

El cruce de Di+ con Di- indica el fin de la tendencia

Cuando el valor del ADX es menor a "Level Range", estamos en Rango

***
## MACD [Gu5]
[Script Publish](https://www.tradingview.com/script/LDAhPFZs-MACD-Gu5/)

Extremely popular indicator MACD (Moving Average Convergence/Divergence) 

Same design of my previous indicators

Show Cross Line for a better visualization

```
Setting recommended for BTC
"Fast Length" = 21
"Slow Length" = 55
"Signal Smoothing" = 14

Other markets try
"Fast Length" = 12
"Slow Length" = 26
"Signal Smoothing" = 9

```
--

El MACD (Convergencia/Divergencia de Medias Móviles) es unon de los mas populares indicadores

Continuando con la misma linea de diseño de mis anteriores indicadores

Destaca el cruce de medias para una mejor visualizacion

***
## Stochastic [Gu5]
[Script Publish](https://www.tradingview.com/script/K5Wd0xCy-Stochastic-Gu5/)

To know if we are in range, I recommend my other indicator "Trend Channel [Gu5]"

Stochastic shows overbought / oversold

--

Para saber cuando no hay tendencia y estamos en rango, recomiendo usar mu indicador "Trend Channel [Gu5]"

El cruce de K & D nos muestra cuando el mercado esta en sobre-compra o sobre-venta

Las alertas con banderas ayudan a visualizar mas claramente, evitando las alertas duplicadas
.

***
## RSI [Gu5]
[Script Publish](https://www.tradingview.com/script/YflOVb17-Mix1-Ema-Cross-Trend-Channel-Gu5/)

Highlights Oversold and Overbought

Show Cross Line when the momentum ends

Same design of my previous indicators

```
Setting recommended for EURUSD:
Length = 14
Oversold = 68
Overbought = 32

Other markets try:
Length = 14
Oversold = 70
Overbought =30
```

--

El indicador destaca cuando el mercado esta en sobre-compra o sobre-venta

Para una mejor visualizacion, marca con un cruce cuando finaliza el movimiento

Continuando con el mismo estilo de diseño de mis anteriores indicadores

--

If any of these indicators were useful, you can buy me a beer;)

Si alguno de estos indicadores te fue util, puedes comprarme una cerveza ;)

BTC: 1MbHMN63WnsFYEavsGK4nMWSUoEiuiScny

Paypal: https://www.paypal.me/gu5tavo71
