# Movie-Recommendation🎥

## Welcome to my GitHub repository on Using Predictive Analytics model for Movie Recommendation.

### Objective:

The repository is  learning exercise to:
* Apply the fundamental concepts of feature extraction from an available dataset
* Evaluate and interpret my results and justify my interpretation based on observed data set
* Create notebooks that serve as computational records and document my thought process. 

### steps for building recommendation engine:

* Exploratory Data Analysis
* Pre-Processing the Data
* model builing

### TF-IDF Feature-extraction  Technique
* TF-IDF (Term Frequency-Inverse Document Frequency) algorithm is a feature extraction technique used in natural language processing (NLP) and information retrieval.
* It is not a machine learning algorithm itself but is often used as a preprocessing step for machine learning tasks, particularly in text analysis.
* TfidfVectorizer is used to convert the documents into a TF-IDF matrix.

### how Cosine-Similarity works:
* cosine_similarity is used to compute the cosine similarity matrix based on the TF-IDF matrix.


* cosine_similarity is a measure of similarity between two non-zero vectors of an inner product space. It is widely used in various applications, including information retrieval, text mining, and recommendation systems. In the context of natural language processing (NLP) and document similarity, cosine similarity is often used to compare the similarity of documents based on the content of the words.

* Cosine_Similarity(A,B) = A.B/|A|.|B|

* A.B is dot product of vectors A and B
* 
* |A| and |B| are Euclidean norms of vectors A and B
  

![image](https://user-images.githubusercontent.com/36665975/70401457-a7530680-1a55-11ea-9158-97d4e8515ca4.png)


### Similarity_Score


How does it decide which item is most similar to the item user likes? Here come the similarity scores.

It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.


