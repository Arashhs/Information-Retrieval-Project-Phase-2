# Information Retrieval: 
During this project, I built an Information Retrieval System for a collection of 50,000 Persian news articles in three phases. I will make the source code public on my GitHub profile in a few days. Here is a summary of the major functionalities that I have implemented in each phase:
## Phase 1:
During this phase, I built an inverted index matrix for the news collection.
1.	I tokenized the news articles, implemented functions to normalize Arabic and Persian characters, function to find the stem of nouns by removing the prefix and postfix characters in nouns and finding the stem of regular and irregular nouns plurals, function to find the stem of the Persian verbs.
2.	I built an inverted index matrix consisting of a dictionary of the result’s unique terms (excluding the common and stop words) and their postings lists, as well as the tf-idf weight of each posting.
3.	I implemented a function to process queries in Boolean form.
## Phase 2:
During this phase, I added the functionality to process free-text queries using a ranked-based method. I also implemented several techniques to reduce the query processing time.
1.	I implemented a function to retrieve the top-K relevant documents by calculating the tf-idf query-document weights.
2.	I implemented Index Elimination and Champions Lists techniques to reduce the query processing time.
## Phase 3:
During this phase, I implemented clustering and classification functions. The main challenge in this phase was to deal with the size and speed in processing this massive collection using these instance-based algorithms.
1.	I represented the documents in the vector-space representation form. Using a few tricks, I was able to reduce the size of the result vectors and the cosine-similarity computation time between these vectors dramatically.
2.	I implemented the K-means clustering algorithm on the given 50K document collection so as to speed up the information retrieval speed. 
3.	I classified a test-set using the KNN algorithm and the 50K document collection with labels as the train-set and added functionality to process queries in the specified topic.
