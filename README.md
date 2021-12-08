# Content Based Book Recommendation System

- **To find which books are similar to others based on the content**

1. Diagnosed text of all books in the dataset using **NLTK** and curated a distance matrix, a matrix showing pairwise distances between all books using **Pandas** and **Gensim**.

2. Build a **tf-idf** model and Summarized data of how similar each book is to a particular book through a bar chart developed using **Matplotlib**.

3. Compute the clusters from the similarity matrix, using the **Scipy-Ward variance minimization algorithm** and Visualized which groups of books have similar topics using **Dendrogram**.