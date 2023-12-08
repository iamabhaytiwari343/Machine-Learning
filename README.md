# Machine-Learning


Machine Learning Algorithms

### Support Vector Machine (SVM)

- A Support Vector Machine (SVM) is a supervised machine learning algorithm that can be used for classification or regression tasks.
- The primary goal of an SVM is to find the optimal hyperplane that separates different classes in the feature space.
- The "support vectors" are the data points that lie closest to the decision boundary (hyperplane).
- In the case of a linearly separable dataset, the hyperplane is a straight line.
- The equation of a hyperplane is represented as w⋅x+b=0, where w is the weight vector, x is the input vector, and b is the bias.
- SVM can also handle non-linearly separable data by using the kernel trick.
- Common kernel functions include the radial basis function (RBF) kernel, polynomial kernel, and sigmoid kernel.
- The margin is the distance between the decision boundary and the nearest data point from each class (support vectors).
- SVM aims to maximize this margin, as it generally leads to better generalization to unseen data.
- SVM introduces a regularization parameter (
C) that controls the trade-off between achieving a low training error and a low testing error.
- Small C values lead to a larger margin but may misclassify some training points, while large C values prioritize correct classification of training points at the expense of a narrower margin.
