•	The dataset is converted into an array
•	x and y are taken (x – independent variables, y – dependent variable).
•	The dependent variable is encoded as 1 (malignant) or 0 (benign).
•	Data set is split in the ratio 0.75:0.25.
•	X_train and X_test is standardized to the same scale.
•	Seven classification models are applied and their accuracies are calculated in the same order:
1.	Logistic Regression: 95.8%
2.	k Nearest Neighbor: 95.1%
3.	SVM: 97.2%
4.	RBF Kernel: 96.5%
5.	Naïve-Bayes: 91.6%
6.	Decision Tree: 95.8%
7.	Random Forest: 98.6%
•	Clearly, Random Forest is more accurate than the rest and can be better used for this case of Breast cancer severity classification.

