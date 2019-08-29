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
.

.

--

Si alguno de estos indicadores te fue util, puedes comprarme una cerveza ;)

BTC: 1MbHMN63WnsFYEavsGK4nMWSUoEiuiScny

Paypal: https://www.paypal.me/gu5tavo71
