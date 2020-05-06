#Keras Introduction

[Keras document](https://keras.io/)
Keras: The Python Deep Learning Library

Use of the simplest model - "Sequential"

`from keras.models import Sequential
model = Sequential()
`

`from keras.layers import Dense
model.add(Dense(units = 64, activation = 'relu', input_dim = 100))
model.add(Dense(units = 10, activation = 'softmax'))
`