# CMPE_255_Assignment_6

This assignment basically aimed at implementation of various clustering algorithms in colabs. I used gpt4 as suggested by professor. 
We were instructed to submit one colab per assignment.

Types of clustering that were expected in this assignment: 
A. K-Means clustering from scratch
B. Hierarchical clustering (not from scratch)
C. Gaussian mixture models clustering (not from scratch)
D. DB Scan clustering (not from scratch) using pycaret library 
E. Demonstrate anomaly detection using pyOD using any usecase
F. Illustrate clustering of timeseries data using pretrained models 
G. Write a colab to illustrate clustering  of documents. use state of art embeddings (LLM Embeddings).
H. Write a colab for clustering with images using imagebind llm embeddings 
I. Write a colab for audio embeddings using imagebind llms

My strategy:

A. K-Means clustering from scratch : I performed KMeans clustering on a beverage dataset, involving data preprocessing, custom functions for centroid initialization, cluster assignment, and updating, followed by visualizing the results with PCA and evaluating performance using inertia and silhouette score.

B. Hierarchical clustering (not from scratch): This code demonstrates Agglomerative Hierarchical Clustering on synthetic datasets, visualized through dendrograms and scatter plots, with performance evaluated using silhouette and Calinski-Harabasz scores to determine the optimal number of clusters.

C. Gaussian mixture models clustering (not from scratch): This code demonstrates the application of KMeans and Gaussian Mixture Models (GMM) for clustering on synthetic datasets, evaluating the results with silhouette scores and visualizing the clusters to compare the performance of both methods on simple and transformed data distributions

D. DB Scan clustering (not from scratch) using pycaret library : This code demonstrates the use of DBSCAN clustering with varying parameters on a synthetic dataset using PyCaret, visualizing the results and evaluating the clustering performance with silhouette scores to analyze the impact of different density thresholds and minimum sample sizes

E. Demonstrate anomaly detection using pyOD using any usecase : This code uses PyOD's KNN algorithm for anomaly detection in a time series dataset, integrating the model's predictions into the dataset for visualization and evaluation, and quantitatively assessing its performance with a classification report.

F. Illustrate clustering of timeseries data using pretrained models : This code applies K-Means and DBSCAN clustering algorithms to a synthetic time series dataset, evaluating their effectiveness using the silhouette score and visualizing the results, with an initial analysis including outlier detection and feature distribution.

G. Write a colab to illustrate clustering  of documents. use state of art embeddings (LLM Embeddings) : This code employs NLTK for text preprocessing and BERT embeddings to transform a synthetic book dataset, followed by applying K-Means clustering and visualizing the results using PCA, to effectively group and visualize thematic similarities in the dataset's descriptions.

H. Write a colab for clustering with images using imagebind llm embeddings : GPT4 was not able to generate the code due to it did not contain updated information. So I created the code for clustering with images The code uses K-Means clustering to group images of various dog breeds into ten clusters, followed by visualizing these clusters with and without breed labels to showcase the algorithm's effectiveness in categorizing images based on visual similarities.

I. Write a colab for audio embeddings using imagebind llms : GPT4 was not able to generate the code due to it did not have any information of imagebind llms. So I created the for audio embeddings. The code uses K-Means clustering to categorize audio data of cat and dog sounds into two clusters, visualizing the results with t-SNE and evaluating the clustering effectiveness using the silhouette score.

Detailed description of each colab is here : https://docs.google.com/document/d/1R6yg3nY-brR0mvN9766lLXBApVvpswqMCAEVYiTvmp0/edit?usp=sharing

Some of the datasets used in the colab were synthetically created, some datapoints created using make_blobs and Part H,I were taken from Kaggle. Link for the datasets is : https://drive.google.com/drive/folders/1xeWcavAmdCnl9Z2rYKdkvcpK9ezsGwP0?usp=sharing

All the colab files are in this repository and can be also found at : https://drive.google.com/drive/folders/1UtZBRlDqSHfSqrw-nhnxJ5oSq3ENz9nM?usp=sharing.
