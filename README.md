# Nested_CV_Optuna

This repository contains an example of how to use Optuna with different classification algorithm to optimize the hyperparameters of classification. In this example, we use the dataset to train and evaluate classifiers.

Getting Started <br/>
To run this code, you will need to have Python 3 installed on your machine. You can download Python 3 from the official Python website.

You will also need to install the following Python packages:

Optuna
TensorFlow
Keras
Scikit-learn
lightgbm
catboost

You can install these packages using pip:

```
pip install optuna tensorflow keras scikit-learn
pip install lightgbm
pip install catboost
```

Usage <br/>
To run the code, simply run the optuna_keras.py script:

```
python optuna_nested_cv.py
```

The script will start the hyperparameter optimization process using Optuna. After the optimization is complete, the script will print the optimal hyperparameters and their score.

You can modify the hyperparameters to optimize by editing the objective function in the optuna_nested_cv.py script. You can also modify the dataset to suit your needs.

Contributing <br/>
Contributions to this repository are welcome. If you find a bug or have a suggestion for improvement, please open an issue or submit a pull request.

Acknowledgments <br/>
Find more in Optuna Documentation https://optuna.readthedocs.io/en/stable/
