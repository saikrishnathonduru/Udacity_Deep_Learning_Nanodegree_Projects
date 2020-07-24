# Predicting Bike-Sharing Patterns
The first Udacity Project from the Deep Learning Nanodegree. Using only Numpy to implement forward and back propagation to predict Bike-Sharing Patterns.
![GitHub Logo](/assets/neural_network.png)
## Setup:
1. Create a conda environment:
Make sure you have installed: numpy matplotlib pandas jupyter notebook
```
conda create --name deep-learning python=3
conda install numpy matplotlib pandas jupyter notebook
```

2. Activate your environment:
* Windows:
```
activate deep-learning
```
* Mac/Linux:
```
source activate deep-learning
```

3. Run the notebook server in the root directory of the project:
```
jupyter notebook
```
* The server is located in: [localhost:8888](localhost:8888/tree)
4. Open the Jupyter notebook called: [Your_first_neural_network.ipynb](/Your_first_neural_network.ipynb)
* The data comes from: [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)
## Results to expect:
### Training and validation loss:
![GitHub Logo](/assets/loss.png)
### Predictions after training:
![GitHub Logo](/assets/predictions.png)
## Conclusions
The predictions are acceptable but in the December the model overestimes bike ridership because it hasn't had sufficient holiday season training examples.
