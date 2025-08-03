
# Decision Trees 

**1.What is entropy and information gain?**
- Entropy is a measure of impurity or randomness in the dataset. In decision trees, it quantifies how mixed the class labels are in a subset.

- Information Gain is the reduction in entropy after a dataset is split on an attribute. It measures how well a feature separates the classes — higher gain means a better split.


**2.Explain the difference between Gini Index and Entropy.**
- Gini Index measures impurity like entropy but is simpler and faster to compute; it reaches its minimum (0) when all elements belong to one class.

- Entropy uses logarithms and considers information theory; it tends to be more sensitive to class distribution. Both are used in decision tree algorithms to choose the best split.


**3. How can a decision tree overfit? How can this be avoided?**
- A decision tree can overfit by learning noise and specific patterns in the training data, especially if it's very deep or uses many small splits.
- To avoid overfitting, we can use pruning, set a maximum tree depth, minimum samples per leaf, or switch to ensemble methods like Random Forests which reduce variance.