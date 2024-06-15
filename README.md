# Resume_Job_Gender_Bias

As the dataset is skewed (i.e., the classes are imbalanced), and we split the data while maintaining the same percentage for each class, then the class distribution in the test dataset will reflect the same skewness as in the original dataset.


Stratified Sampling: By using stratified sampling, we ensure that each class is proportionally represented in the training, validation, and test sets. This means that if a class constitutes 10% of the original dataset, it will also constitute approximately 10% of each subset created using stratified sampling.

Class Imbalance: If the original dataset has a class imbalance (e.g., 80% class A, 20% class B), the train, validation, and test sets will have a similar class imbalance if stratified sampling is used.

So, when we split your data using stratified sampling, the test set will indeed reflect the same percentage of class distribution as in the original dataset.
\\\\\\\



\\\\\


## README

This project implements an LSTM-based neural network model for multi-class classification of job occupations based on resumes. The dataset includes text data describing skills and job descriptions, which are combined into a single 'CV' column for analysis. The project involves several key steps: data preprocessing (including tokenization and padding of text sequences), encoding of categorical labels, and the use of pre-trained GloVe embeddings to enhance the text representations. The data is split into training, validation, and test sets using stratified sampling to maintain class distribution. A gender-weighted sampling approach is employed to handle class imbalance, ensuring fair representation of genders in each occupation. The LSTM model is then trained and evaluated, with performance metrics such as accuracy, precision, and recall calculated separately for males and females to assess gender bias. The results, including TPR and precision gaps between genders, are documented to provide insights into the model's fairness and effectiveness.
