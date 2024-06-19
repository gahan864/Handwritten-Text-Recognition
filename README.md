# Handwritten-Text-Recognition
Train your model using K-Nearest Neighbor Algorithm with having values of K as {2,4,5,6,7,10}, over data.csv file provided. The Train and Test split of the data should be in the ratio of 60:40, 70:30, 75:25, 80:20, 90:10, 95:5. Evaluate the performance of the model over test data for all these scenarios (36 cases), and submit the single jupyter notebook, having one of the scenario implemented (and rest in comments), and a single pdf file containing the results of all these scenarios (Accuracy, and Confusion Matrix), also your analysis regarding the dependency of the performance of model over training-testing split and k value.

##Data Set
https://drive.google.com/file/d/1-hp4S4Dmv-6sGDCnXSZF4v5zYp3-hFWl/view?usp=sharing

##Train Set
https://drive.google.com/file/d/1TXZARX3CMnHrMgO_KAEfRjrs8BECeFLk/view?usp=sharing




#K-NN algorithm
The k-NN algorithm is a simple, instance-based learning algorithm where predictions for new
data points are made based on the majority class of the k-nearest training examples. The
value of k determines how many neighbours influence the prediction.
Analysis regarding K:
 Small k: The model may become too sensitive to noise in the training data, leading to high
variance and overfitting.
 Large k: The model may become too smooth, leading to high bias and underfitting.
 Optimal k: There is often an optimal k that balances bias and variance, providing the best
performance.
Effect of train test split ratio:
 Large Training Set (e.g., 90-10): The model has more data to learn from, potentially
improving accuracy but at the cost of having less data to validate the model.
 Small Training Set (e.g., 60-40): The model has less data to learn from, which may lead to
overfitting on the small training set and poor generalization
