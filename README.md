# Resume_Job_Gender_Bias

As the dataset is skewed (i.e., the classes are imbalanced), and we split the data while maintaining the same percentage for each class, then the class distribution in the test dataset will reflect the same skewness as in the original dataset.


Stratified Sampling: By using stratified sampling, we ensure that each class is proportionally represented in the training, validation, and test sets. This means that if a class constitutes 10% of the original dataset, it will also constitute approximately 10% of each subset created using stratified sampling.

Class Imbalance: If the original dataset has a class imbalance (e.g., 80% class A, 20% class B), the train, validation, and test sets will have a similar class imbalance if stratified sampling is used.

So, when we split your data using stratified sampling, the test set will indeed reflect the same percentage of class distribution as in the original dataset.
