# Venture Funding Applicant Assessment

This module uses `deep learning` to create a model that predicts whether startup applicants will be successful if funded by `Alphabet Soup`.

Three neural network models are used to assess the applicant data each with different charateristics:

1. Model 1 uses a network with 1 hidden layer containing 59 nodes with each layer using the `Rectified Linear Unit` activation function and the output layer using the `sigmoid` activation function resulting in a loss of `0.57289` and an accuracy of `0.73049`. 
2. Model 2 uses a network with `2` hidden layers with `88` and `44` nodes respectively.  Both utilise the `Rectified Linear Unit` activation function whilst the output layer uses the `sigmoid` activation function.  This model delivered a loss of `0.58992` and an accuracy of `0.72804` failing to improve on model 1's result
3. The final model returns to a single hidden layer but with `232` nodes, the `Rectified Linear Unit` activation function whilst the output layer uses the `tanh` activation function.  This model yielded a loss of `0.65237` and an accuracy of `0.72781` also failing to improve on model 1's results.

This exercise confirms that model 1 is the most accurate of the 3 models to assess the likely success of each applicant.