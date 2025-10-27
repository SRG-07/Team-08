# Team-08
Reel Recommendation System

Task 03:
Explaination of the Steps i did while solving this
1) First i imported all the libraries like numpy torch transformers and also i imported Scikit Learn library and tried solving using it
2) I also used sentance-transformer library and used the pretrained model MiniLM which is the mini version or BERT(Bidirectional Encoder Representations from Transformers)
3)In this the captions is split into tokens and then the token ID is mapped to a vector (this is the word embedding)
4)The using the sentance embedding all th token embeddings are combined into one single vector which represents the entire caption
5)I created captions and checked some 10 values of the embedding vector
6)Then i used the cosine similarity from the scikit learn library. This cosine similarity is used to find how close the words/tokens to each other
6) Next using pandas i generated the matrix(Caption Matrix) where each captions compares to each other captions
7)I also printed the best similar caption for each captions
