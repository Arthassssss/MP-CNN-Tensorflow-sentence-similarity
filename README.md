# MP-CNN-Tensorflow-sentence-similarity
This code belongs to the "[Implementing a MPCNN for Sentence Similarity in Tensorflow](http://blog.csdn.net/irving_zhang/article/details/70036708)" blog post.

[paper](https://pdfs.semanticscholar.org/0f69/24633c56832b91836b69aedfd024681e427c.pdf)
# Requirements：
 - Python 2.7
 - Tensorflow 1.0
 - numpy
 
# Notes:
 Because the glove file is too big, there is no way to upload. Please go to the official website to download [glove.6B.50d.txt](https://nlp.stanford.edu/projects/glove/). 
 
# Attention:
You should add 
 ```
 400000 50
 ```
at the first row in the glove.6B.300d.txt file, after that we could read the glove with word2vec tools.

or you will meet the error ---- ValueError: invalid literal for int() with base 10: 'the'
 
 Hava a good time!
