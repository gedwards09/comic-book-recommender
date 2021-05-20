# comic-book-recommender

This file uses data from the UCSD Book Graph project containing user data 
collected from Goodreads.com in 2017 to produce collaborative filtering 
recommendations for books in the comics and graphic novels genre.

Three models were produced and evaluated by accuracy on validation data.

1) Popularity Model: Ranks and recommends books by total number of user interactions
and serves a control

2) Matrix Factorization: Generates embeddings for users and books in Keras to approximate
to the singular value decomposition of the interaction matrix

3) Deep Neural Collaborative Filtering: Generates embeddings for users and books and 
feed them into a sequence of densely connected linear layers with ReLU activation.
