
# Naive Bayes Classifier

**1. What is the core assumption of Naive Bayes?**
    The core assumption of Naive Bayes is that all features (input variables) are conditionally independent of each other given the class label. This means the presence or value of one feature does not influence another, which simplifies the computation of probabilities.

**2. Differentiate between GaussianNB, MultinomialNB, and BernoulliNB.**
    GaussianNB assumes that the features follow a normal (Gaussian) distribution and is commonly used for continuous data.

    MultinomialNB is suitable for count-based data like word frequencies in text classification.

    BernoulliNB works with binary/boolean features, where features are either present (1) or absent (0), often used in document classification with binary word indicators.

**3. Why is Naive Bayes considered suitable for high-dimensional data?**
    Naive Bayes performs well with high-dimensional data because its independence assumption reduces computational complexity. It doesn’t require feature selection or complex correlations, making it fast and efficient even when the number of features is very large, like in text classification tasks.

