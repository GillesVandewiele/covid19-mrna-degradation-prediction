# OpenVaccine: COVID-19 mRNA Vaccine Degradation Prediction (Fourth Place)

fourth place solution to the "OpenVaccine: COVID-19 mRNA Vaccine Degradation Prediction" competition organized by Stanford University and Kaggle

By team FromTheWheel & [Dyed](https://www.kaggle.com/mtinti) & [StoneShop](https://www.kaggle.com/bsteenwi).


In order to fully reproduce our approach, the following changes need to be made:

* the cross-validation scheme needs to be changed from 5 folds to 10 folds

* 3 variants of the notebook in this repository need to be made. In the provided notebook, LSTM+LSTM is used as final layers. 3 other notebooks with LSTM+GRU, GRU+LSTM and GRU+GRU variants need to made. The four submission files need to be blended together (uniform weights).
