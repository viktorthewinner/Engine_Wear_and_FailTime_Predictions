This is a personal project. I wanted to learn about Machine Learning and to test my knowledge.

Picked a data set to predict the remaining time before the engine will crash.

We use in real life big engines in factories, vehicles, planes, etc. It is very useful to know when the engine will shut off, or when it is needed to fix it. Because engines cause vibrations, the data is taken from a cooler fan with weights distributed on him to provoke the vibration. With the fan's speed, measured vibrations and a legend for the weights and their places on the fan, I created a Neural Network. Because I have no data on the time until failure, I made one function for the wear of the "engine" and another for the remaining time. Using the Neural Network, I created a model who is predicting good enough. I can make it more perfect, but it is risky to overfit. Experimented with different numbers of epochs, batch sizes and neurons, even layers, until I liked the chosen ones.
The loss (or error) between the validation data set and the testing data set is stable, meaning I didn't underfit, nor overfit.
