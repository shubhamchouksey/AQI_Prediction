# AQI_Prediction

## Parameter Used:

* Average Temperature (°C)
* Maximum temperature (°C)
* Minimum temperature (°C)
* Atmospheric pressure at sea level (hPa)
* Average relative humidity (%)
* Average visibility (Km)
* Average wind speed (Km/h)
* Maximum sustained wind speed (Km/h)

## Algorithm Used:

* Linear Regressor
* KNN Regressor
* Decision Tree Regressor
* Random Forest Regressor
* XGBoost Regressor

## Data Sources:

* [Mateorological Data](https://en.tutiempo.net/climate/05-2019/ws-421820.html)
* [PM 2.5 Ratings](https://en.wikipedia.org/wiki/Air_quality_index#India)


| PM 2.5        | Condition           | Rating  |
| ------------- |:-------------| :-----|
| 0-30      | Good | 1 |
| 31-60     | Satisfactory      |   2 |
| 61-90 | Moderately Polluted    |   3 |
| 91-120      | Poor | 4 |
| 121-250     | Very Poor     |   5 |
| 250+ | Severe    |   6 |

