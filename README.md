**Overview**

This work is structured into three parts, each focusing on different aspects of data analysis and visualization. The file is named mlp.ipynb.

Part 1:
Implement perceptron learning algorithm for classifying a linearly separable dataset in 2D. Note that you have to create such a dataset with at least 1000 data points. Plot the dataset before and after training (with the classifier). Discuss your observations with respect to number of iterations required for perfect classification (k) by varying the level of separability (γ from the class discussions) in the dataset. (Hint: compute the average value of k for each level of γ, and do this for about 5 values of γ. Observe if you can relate to the result discussed in class)

Part 2:
Consider solving the above problem (training a line for classifying a linearly separable 2D dataset) using Gradient Descent algorithm. Think of a loss function (beyond simple MSE) based on our classroom discussion on the desirable properties of a loss function. You may implement the an- alytical way of finding gradient for it. You may implement the basic version of gradient descent update equation. Plot the dataset before and after training (with the classifier).

Part 3:
Consider a binary classification dataset that is not linearly separable in 2D (e.g. data lying on the circumference two concentric circles). Train a Multi layer perceptron (MLP) with a single hidden layer for classifying the same. You may use the loss function used in problem 2. You have to implement the backpropagation algorithm yourself.

**Requirements**
Before running the notebook, ensure that you have the following libraries installed:

Pandas: For data manipulation and analysis.
Matplotlib: For creating static, animated, and interactive visualizations.
You can install these libraries using pip if they are not already installed:

bash
    pip install pandas matplotlib
    
**Running the Notebook**
To execute the notebook, open mlp.ipynb in Jupyter Notebook or Jupyter Lab and run the cells sequentially. Ensure that all dependencies are installed and the required datasets are available.
