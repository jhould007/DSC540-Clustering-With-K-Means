# DSC540-Clustering-With-K-Means
An assignment for DSC540 (Machine Learning for Data Science) at GCU that focused on applying a k-means clustering model to a chosen dataset. I analyzed a dataset of online shopping sessions to see if sessions could be separated into meaningful clusters for the purpose of customer segmentation, which could then be used for targeted marketing strategies.

Check out the full report [here.](https://github.com/jhould007/DSC540-Clustering-With-K-Means/blob/master/Clustering%20with%20k-Means.ipynb)

# Assignment Instructions
# Part 1

To perform a k-means analysis using the k-means algorithm, complete the following:
1. Access the "UCI Machine Learning Repository," located in the topic Resources. Note: There are about 120 data sets that are suitable for use in a clustering task. For this part of the exercise, you must choose two of these datasets, provided they include at least 10 attributes and 10,000 instances.
2. Ensure that the datasets are suitable for clustering using these methods.
3. You may search for data in other repositories, such as Data.gov or Kaggle.

# Part 2

For your selected datasets, build a K-means clustering model.
1. Start by choosing the number of clusters. Discuss how you would find the optimal number of clusters that best fits the dataset.
2. Randomly pick k centroids "not necessarily from your dataset" (or points that will be the center of your clusters) in d-space. Try to make them near the data but different from one another.
3. Assign each data point to the closest centroid. This will form your k clusters. Apply the Euclidian distance to form your clusters.
4. Move the centroids to the average location of the data points assigned to it.
5. Repeat the preceding two steps until the assignments do not change or change very little.

<b>Note:</b> A key objective is to minimize the variation within the clusters defined as <b>the sum of squared Euclidean distances between items and the corresponding centroid.</b>

# Part 3

1. Explain the dataset and the type of information you wish to gain by applying a clustering method.
2. Explain the k-means algorithm and how you will be using it in your analysis (list the steps, the intuition behind the mathematical representation, and address its assumptions).
3. Import the necessary libraries, then read the dataset into a data frame and perform initial statistical exploration.
4. Clean the data and address unusual phenomena (e.g., outliers); use illustrative diagrams and plots and explain them.
5. Formulate two questions that can be answered by performing a clustering analysis using the k-means.
6. Use the elbow method to find the optimal number of clusters for your chosen dataset. Justify your chosen (final) value of k.
7. Perform k-means analysis. Explain the intuition behind each mathematical step.
8. Interpret the results in the context of the questions you asked.
9. Discuss how you minimized the variation within the clusters.
10. Validate your model. Then, explain the results.
11. Include all mathematical formulas used and graphs representing the final outcomes.

Prepare a comprehensive technical report as a markdown document or Jupyter notebook, including all code, code comments, all outputs, plots, and analysis. Make sure the project documentation contains a) problem statement, b) algorithm of the solution, c) analysis of the findings, and d) references.

While APA style is not required for the body of this assignment, solid academic writing is expected, and documentation of sources should be presented using APA formatting guidelines, which can be found in the APA Style Guide, located in the Student Success Center.   

This assignment uses a rubric. Review the rubric prior to beginning the assignment to become familiar with the expectations for successful completion.

You are not required to submit this assignment to LopesWrite.
