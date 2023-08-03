# `tcma-environmental-justice-prediction` : Environmental Justice Concern Prediction Using Random Forest


This project was completed as a requirement for GIS 5572: Principles of Geocomputing at the University of Minnesota.

## About

The objective of this project was to use Random Forest to predict whether census tracts in the
Twin Cities Metro Area (TCMA) are areas of environmental justice concern and visually display the predictions using an interactive map.

The solution to the problem stated above is to use a Random Forest machine learning model to aid in predicting areas of environmental justice concern in the TCMA using equity consideration data from the Metropolitan Council. We also use census data to get the geometry of the tracts. Folium will be used to present the tracts, visualize their environmental justice predictions, etc.

### Methods
- Random Forest `scikit-learn`

### Results 

| MSE  | r2 |
| ---- | ------- |
| 0.02  |  0.88  |

![results](ej_prediction_map.html)

## Author(s)


[`Mattie Gisselbeck`](https://github.com/mattiegisselbeck)
<br>
[`Nikunj Chawla`](https://github.com/nik312123)
