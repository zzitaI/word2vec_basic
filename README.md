# word2vec_basic
This is what i learned from [tensorflow's word2vec tutorial](https://www.tensorflow.org/versions/r0.8/tutorials/word2vec/index.html).
## Problems remained
This first version of word2vec has some problems:
1. i should not use a tf.InteractiveSession since it is not necessary, however, i need to close the session as a consequence.
2. i have not removed all the stop words before sending them into the word2vec model.
## Flow
# build a model
1. model=word2vec_basic()
# train it
2. model.train()
# visualize it
3. model.visualize()
# to see the word embeddings
model.final_embeddings
# to see the words dictionary
model.reversed_dictionary

