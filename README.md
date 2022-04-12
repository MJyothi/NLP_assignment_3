# NLP Assignment 3

In this experiment, correlation between vector and lexical semantic is evaluated. word2vec and tf-idf models have been implemented and are trained on Brown corpus' news and romance categories. Word2vec is implemented in different settings by varying it's context window size and vector size. Context window is varied between 1, 2, 5, and 10, and vector size between 10, 50, 100, and 300. 

SimLex-999 is used as golden standard resource to evaluate the performance of both these models. The models are used to find top-10 similar words for each word in SimLex-999 corpus by calculating cosine similarity and results are evaluated using normalized discounted cumulative gain (nDCG) score.

 
