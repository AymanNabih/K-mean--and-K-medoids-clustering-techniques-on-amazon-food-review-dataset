# K-means-and-K-medoids-clustering-techniques-on-amazon-food-review-dataset
Apply k-means++ and k-medoids method of clustering on amazon food review dataset

### About the dataset
Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.<br>

Number of reviews: 568,454<br>
Number of users: 256,059<br>
Number of products: 74,258<br>
Timespan: Oct 1999 - Oct 2012<br>
Number of Attributes/Columns in data: 10<br>

### Attribute Information:<br>
1. Id ProductId - unique identifier for the product<br><br>
2. UserId - unqiue identifier for the user ProfileName<br>
3. HelpfulnessNumerator - number of users who found the review helpful<br>
4. HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not<br>
5. Score - rating between 1 and 5<br>
6. Time - timestamp for the review<br>
7. Summary - brief summary of the review<br>
8. Text - text of the review<br>

### Codes for-
* Use k-means++ and k-medoids clustering techniques to cluster the reviews for bag of words, tfidf, avg word2vec and tfidf word2vec featurization.

* Use elbow method to plot loss vs k graph , where k is number of clusters.

* Get some reviews from the clusters and read it manually to find the semantic meaning of the cluster.
