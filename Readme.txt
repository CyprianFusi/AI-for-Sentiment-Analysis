Natural Language Processing (NLP) involves the steps in the preparation of languages spoken by humans (such as English) for use by machines 
(or computers). In the context of machine and deep learning these are the steps in the preparation of text (or audio) data for training 
a machine learning algorithm.
Text data must be converted into vectors of numbers for use by machine learning algorithms during training and inferences. 
The steps can be many and tidius when working with a huge amount of text data. But fortunetely, when working with deep learning and a large
number of examples, the steps are reduced to only basic transformations: normalization, cleaning, and tokenization. 
Tensorflow's Keras offers a function, keras.preprocessing.text.Tokenizer, that normalizes, cleans and tokenizes.
The deep learning layers can do the heavy lifting of determining what information to extract (feature engineering) and process. The main layer 
that is responsible for feature engineering in deep learning network is the Embedding layer. It maps the words in the input text into vectors 
of numeric sequences. Embeddings are trained using large volumes of documents or corpus and can be emploit in the training of a model to map 
words in input text into vectors as required by machine learning algorithms. Unlike other methods of feature engineering that lead to sparse 
matrices, embeddings transform a sparse matrix into a dense one, with no zero values inside the matrix. Word embeddings can reduce the
number of columns in the matrix from hundreds of thousands to a few hundred - a kind of dimensionality reduction!


I made use of knowledge from the following sources:

Learn TensorFlow 2.0 by Pramod Singh and Avinash Manure
Deep Learning for Dummies by by John Paul Mueller and Luca Massaron



PS: I am doing data science and machine learning as a hobby but I wish to make it my life career!
cyprofusi@hotmail.com

