# Applied Machine Learning

### Assignment 1: Getting Started with Machine Learning

#### Overview:
Implement and compare K-Nearest Neighbors (KNN) and Decision Trees (DT) on two health-related datasets.

#### Tasks:
1. **Data Acquisition and Preprocessing**:
   - Load and clean the NHANES age prediction and Breast Cancer Wisconsin datasets.
   - Compute basic statistics and understand the data.

2. **Implementing KNN and DT**:
   - Implement KNN and DT from scratch using Python.
   - Define `fit` and `predict` functions for each model.
   - Implement an `evaluate_acc` function to evaluate model accuracy.

3. **Running Experiments**:
   - Compare KNN and DT on accuracy and AUROC.
   - Experiment with different K values for KNN and tree depths for DT.
   - Test different distance/cost functions.
   - Plot ROC curves and compute AUROC.
   - Identify key features for both models and analyze feature importance.

#### Deliverables:
- `assignment1_group-k.ipynb`: Jupyter Notebook with data processing, classification, and evaluation code.
- `assignment1_group-k.pdf`: Aassignment write-up.

---

### Assignment 2: Classification of Textual Data

#### Overview:
Implement logistic regression and multiclass regression and compare them with Decision Trees on textual datasets.

#### Tasks:
1. **Data Preprocessing**:
   - Process IMDB Reviews and 20 news groups datasets.
   - Filter and select features using Simple Linear Regression and Mutual Information.

2. **Implementing Logistic and Multiclass Classifiers**:
   - Implement logistic regression and multiclass regression from scratch.
   - Define `fit` and `predict` functions for each model.
   - Use ROC curves and AUROC for evaluation.

3. **Running Experiments**:
   - Report top features using simple linear regression.
   - Conduct binary and multiclass classification.
   - Plot ROC curves and compare logistic regression and DT.
   - Compare model accuracy as a function of training size.
   - Explore different learning rates, stopping criteria, and text embedding methods.

#### Deliverables:
- `assignment2_group-k.ipynb`: Jupyter Notebook with data processing, classification, and evaluation code.
- `assignment2_group-k.pdf`: Project write-up.

---

### Assignment 3: Classification of Image Data

#### Overview:
Implement a multilayer perceptron (MLP) from scratch and experiment with convolutional neural networks (ConvNets) for image classification.

#### Tasks:
1. **Data Acquisition**:
   - Use Sign Language MNIST dataset for experiments.

2. **Implementing MLP**:
   - Implement MLP with backpropagation and mini-batch gradient descent.
   - Define `fit` and `predict` functions for MLP.
   - Verify gradients using small perturbation analysis.

3. **Running Experiments**:
   - Compare MLP with no hidden layer, one hidden layer, and two hidden layers.
   - Experiment with different activation functions and L2 regularization.
   - Implement and experiment with ConvNets using existing libraries.
   - Compare MLP and ConvNet performance.
   - Explore different hyperparameters and their impacts on accuracy.

#### Deliverables:
- `assignment3_group-k.ipynb`: Jupyter Notebook with data processing, classification, and evaluation code.
- `assignment3_group-k.pdf`: Assignment write-up.
