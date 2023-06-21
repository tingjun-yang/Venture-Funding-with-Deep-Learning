# Venture Funding with Deep Learning

The goal of this project is to create a model that predicts whether applicants will be successful if funded by the venture capital firm Alphabet Soup. The business team provided a CSV file containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. The project contains three steps:

* Prepare the data for use on a neural network model.
* Compile and evaluate a binary classification model using a neural network.
* Optimize the neural network model.

I tried neural networks with three different architectures and the performance is summarized in this table. 

| NN architecture | Model accuracy |
| :--------: | :-------: |
| 116:58:29:1 | 0.730 |
| 116:116:58:1 | 0.731 |
| 116:23:1 | 0.729 |

The accuracies are similar between different models, which means the performance does not depend much on the network architecture. 

The notebook for this project is [venture_funding_with_deep_learning.ipynb](venture_funding_with_deep_learning.ipynb).