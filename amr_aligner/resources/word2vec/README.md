Word2vec for our aligner
========================

We use the [glove.840B.300d](http://nlp.stanford.edu/data/glove.840B.300d.zip).
We suggest to filter the embeddings by the words and concepts 
(trimming the tail in word sense) in the data.

To use GloVe embeddings with Gensim, you will need to convert them to the Word2vec format. You can do it using the Gensim built-in [tool](https://radimrehurek.com/gensim/scripts/glove2word2vec.html).