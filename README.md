# VUUЯ DSM
In this repository we keep track of literature and work on using word embeddings on Dutch NLP tasks such as POS tagging and parsing. This initiative came to life during one of the meeting of the CLTL (VU Amsterdam) and LaMa (Radboud University Nijmegen). We talked about the popularity of distributed (semantic) models, how we use them, and how we want to use them. It became apparent that there was unified way of using them. For example because the models are not shared, but also because for Dutch, at that time at least, there were no models ready to be downloaded and used.

Things have changed a bit, and in this repository we want to keep track of D(S)Ms on Dutch NLP tasks.

# By Task

## Relation evaluation
[1] *Evaluating Unsupervised Dutch Word Embeddings as a Linguistic Resource*, Stephan Tulkens, Chris Emmery, Walter Daelemans
+ gensim w2v SGNS, n5, 160&320 dimensies op Roularta, Wikipedia, Sonar500, COW (for COW: Given this, we chose to remove all tokens that only consisted of one character,  except the token u)
+ available on https://github.com/clips/dutchembeddings

## Dialect identification
[1] *Evaluating Unsupervised Dutch Word Embeddings as a Linguistic Resource*, Stephan Tulkens, Chris Emmery, Walter Daelemans
+ gensim w2v SGNS, n5, 160&320 dimensies op Roularta, Wikipedia, Sonar500, COW (for COW: Given this, we chose to remove all tokens that only consisted of one character,  except the token u)
+ available on https://github.com/clips/dutchembeddings

## POS tagging
[2] *Polyglot: Distributed Word Representations for Multilingual NLP*, Rami Al-Rfou', Bryan Perozzi, Steven Skiena
+ Theano, 64 dimensions, n5, Wikipedia, 100k vocab, 197M tokens

## Author clustering
[3] *Exploring Word Embeddings and Character N-Grams for Author Clustering*, Yunita Sari, Mark Stevenson
+ gensim w2v CBOW, n5, 300 dimensions, 3.7B, bron onduidelijk

## No task
[4] *N-gram Frequencies for Dutch Twitter Data*, Gosse Bouma
+ google w2v, n5, 200 dimensions, 2.6B dutch Tweets

## Animacy Detection
[5] *Animacy Detection in Stories*, Folgert Karsdorp, Marten van der Meulen, Theo Meder, Antal van den Bosch
+   google w2v, COW'14, 6B, 300 dimensies

## Semantic priming
[6] *Explaining human performance in psycholinguistic tasks with models of semantic similarity based on prediction and counting: A review and empirical validation*, Paweł Mandera, Emmanuel Keuleers, Marc Brysbaert
+ gensim word2vec CBOW&SG, Sonar500 + Subtlex 530M tokens, n1,2,3,5,10, 200 & 300 dimensions

## Named entity recognition
[7] *Neural Architectures for Named Entity Recognition*, Guillaume Lample, Miguel Ballesteros, Sandeep Subramanian, Kazuya Kawakami Chris Dyer
+ Skip-n-gram, Leipzig corpus collection, 64 dimensions, 1M tokens, n8

# All works referenced
[1] *Evaluating Unsupervised Dutch Word Embeddings as a Linguistic Resource*, Stephan Tulkens, Chris Emmery, Walter Daelemans (https://arxiv.org/pdf/1607.00225v1.pdf)

[2] *Polyglot: Distributed Word Representations for Multilingual NLP*, Rami Al-Rfou', Bryan Perozzi, Steven Skiena (http://www.aclweb.org/anthology/W13-3520)

[3] *Exploring Word Embeddings and Character N-Grams for Author Clustering*, Yunita Sari, Mark Stevenson (http://ceur-ws.org/Vol-1609/16090984.pdf)

[4] *N-gram Frequencies for Dutch Twitter Data*, Gosse Bouma (http://www.clinjournal.org/sites/clinjournal.org/files/bouma2015_0.pdf)

[5] *Animacy Detection in Stories*, Folgert Karsdorp, Marten van der Meulen, Theo Meder, Antal van den Bosch (http://narrative.csail.mit.edu/cmn15/paper2.pdf)

[6] *Explaining human performance in psycholinguistic tasks with models of semantic similarity based on prediction and counting: A review and empirical validation*, Paweł Mandera, Emmanuel Keuleers, Marc Brysbaert (http://crr.ugent.be/papers/Mandera_et_al_JML_2016.pdf)

[7] *Neural Architectures for Named Entity Recognition*, Guillaume Lample, Miguel Ballesteros, Sandeep Subramanian, Kazuya Kawakami Chris Dyer (https://arxiv.org/pdf/1603.01360.pdf)
