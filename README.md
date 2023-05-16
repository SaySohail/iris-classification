



<h3 align="center"> Iris Classification using Logistic Regression and Neural Networks</h3>

<div align="center">

  [![code coverage](coverage.svg "Code coverage")]()
</div>

---


## 🧐 About <a name = "about"></a>

In this machine learning project, I aim to classify iris plants into three classes based on their sepal and petal measurements. The dataset consists of 150 instances, with 50 instances for each of the three classes: Iris-Setosa, Iris-Versicolour, and Iris-Virginica. I will apply classification algorithms, including logistic regression and neural networks, to build models that can accurately classify new iris samples based on their measurements.

## 🔖 Project structure

```
Project_folder/
|- bin/          # contains scripts and main files that should be run
|- config/       # config files
|- notebooks/    # notebooks for EDA, exploration, predictions and results and conclusions
|- src/          # source code - contains functions
|- tests/        # Test files should mirror the src folder
|- Makefile      # automatize taks through make utility
```

## 🏁 Getting Started <a name = "getting_started"></a>
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Setup your environement and install project dependencies
```
conda create -n my_project python=3.10
source activate my_project

python -m pip install pip-tools
pip-compile --output-file requirements.txt requirements.in requirements_dev.in
python -m pip install -r requirements.txt
```

### Installing

## 🔧 Running the tests
Tests are implemented in ./tests, you need to run the following command to run them.
```
make tests
```
### Data Exploration and Preprocessing:
* Load the iris dataset, which contains four numeric predictive attributes: sepal length, sepal width, petal length, and petal width.
* Analyze the dataset's structure, including the number of instances, attributes, and class distribution.
* Check for missing values and handle them if any are found.
* Visualize the data using scatter plots, histograms, or other relevant visualizations to gain insights into the relationships between the attributes and the class labels.

### Logistic Regression:
* Start with logistic regression, a popular classification algorithm for binary and multiclass problems.
* Split the dataset into training and testing sets.
* Fit a logistic regression model using the training data.
* Evaluate the model's performance using appropriate metrics such as accuracy, precision, recall, and F1-score.
* Visualize the decision boundaries or predicted probabilities for each class.
* Analyze the model's limitations, such as cases where the classes are not linearly separable.
### Neural Networks:
* Explore the use of neural networks, a powerful algorithm for complex classification tasks.
* Preprocess the data, including scaling the numeric attributes and one-hot encoding the class labels.
* Split the dataset into training and testing sets.
* Design and train a neural network model using frameworks like TensorFlow or Keras.
* Optimize hyperparameters such as the number of hidden layers, neurons, and learning rate using techniques like grid search or random search.
* Evaluate the trained neural network model using appropriate metrics and visualize the classification results.
* Analyze the model's performance compared to logistic regression and discuss the benefits and limitations of using neural networks for this task.

### Model Evaluation and Interpretation:
* Compare the performance of logistic regression and neural networks.
* Assess the models' accuracy, precision, recall, and F1-score using the testing set.
* Interpret the model's coefficients in logistic regression to understand the impact of different attributes on the classification.
* Discuss the implications of the findings and potential applications of the models in classifying iris plants accurately.

### Conclusion:
This project aimed to classify iris plants into three classes based on their sepal and petal measurements using logistic regression and neural networks. By analyzing and training these models, I gained insights into the relationships between the attributes and the class labels. The results and analysis contribute to a better understanding of the patterns in iris classification and can potentially assist in the accurate classification of iris plants in real-world scenarios.










