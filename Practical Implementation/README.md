# MasterThesis - Preliminary Implementation
## Deep Neural Networks for Behavioral Modeling of Analog ICs

This repository aims to store all the information about modeling the behavior of analog circuits.

All this work is of the authorship of André Carneiro Amaral

### Preliminary Dataset

This [dataset](https://github.com/oAndreAmaral/MasterThesis/blob/f382122ac101e8043d407242a48787a5367559b0/Practical%20Implementation/simulation_data_cleaned.csv) was used to train the first model. It is the result of SPICE simulation of an Amplifier and pre-processed using this [data file](https://github.com/oAndreAmaral/MasterThesis/blob/f382122ac101e8043d407242a48787a5367559b0/Practical%20Implementation/Data%20Analysis.ipynb).

### Preliminary LSTM Application

This [model file](https://github.com/oAndreAmaral/MasterThesis/blob/f382122ac101e8043d407242a48787a5367559b0/Practical%20Implementation/LSTM_Preliminary_Model.ipynb) contains the LSTM model, how to train the model and how to evaluate the performance.

### Preliminary MLP Application

Just to compare the performance of two different models in the same dataset, a [multi-layer perceptron model](https://github.com/oAndreAmaral/MasterThesis/blob/f382122ac101e8043d407242a48787a5367559b0/Practical%20Implementation/MLP%20Method.ipynb) was created, trained and evaluated.

### Conclusions

In this work the LSTM methodology was adopted.
