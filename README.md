# Tws RTD Server

An imporved TWS RTD Server for excel baseed on interactive brokers' TWS RTD Server.

- Original version: 9.73.07
- Original documentation: [here](https://interactivebrokers.github.io/tws-api/tws_rtd_server.html)

Add support for delayed option ticks.

| Tick Name | Topic String | Description |
| :--- | :--- | :--- |
|Delayed Bid Delta | "DelayedBidDelta" |  Delta calculated from the delayed option bid prices. |
| Delayed Bid Gamma | "DelayedBidGamma" | The option gamma value calculated from the delayed option bid prices. |
| Delayed Bid Vega | "DelayedBidVega" | The option vega value calculated from the delayed option bid prices. |
| Delayed Bid Theta | "DelayedBidTheta" | The option theta value calculated from the delayed option bid prices. |
|Delayed Model Delta | "DelayedModelDelta" |  Delta calculated from the delayed option model prices. |
| Delayed Model Gamma | "DelayedModelGamma" | The option gamma value calculated from the delayed option model prices. |
| Delayed Model Vega | "DelayedModelVega" | The option vega value calculated from the delayed option model prices. |
| Delayed Model Theta | "DelayedModelTheta" | The option theta value calculated from the delayed option model prices. |