# Stanford-CS-129-Project

For Stanford's CS 129 course, Applied Machine Learning, worked on a final project with two other classmates. These are my coding contributions.

In our project, we predicted depression based on RNA expression. The algorithms used included a neural network, logistic regression, SVM, and an anomaly detection algorithm; PCA was also tested, but it did not improve the performance. I wrote the anomaly detection and SVM algorithms, and I will share those here.

The data set was a proprietary set provided by one of the group members. While it does not include identifying data, I will not share it just to be safe. I have also cleared out the cell outputs that showed the data.

The data had a 98 columns corresponding to a single gene, a column corresponding to the samples' indices, and a column with BDI scores. The 98 columns were the inputs and the BDI scores were the outputs. There were around only 120 samples, so the predictions are not accurate. The anomaly detection algorithm was the most successful, but only worked because of a shotgun approach.
