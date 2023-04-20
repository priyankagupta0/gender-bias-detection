# gender-bias-detection
Recently, there has been a lot of talk regarding the presence of bias in word embeddings, as shown in this https://proceedings.neurips.cc/paper_files/paper/2016/file/a486cd07e4ac3d270571622f4f316ec5-Paper.pdf NIPS paper. The paper https://arxiv.org/pdf/1607.06520.pdf which is authored by Bolukbasi and colleagues has identified certain occupations that have extreme gender biases, either towards males or females, which are listed below. 

Word2Vec and GloVe are pre-trained embeddings.the vectors that these authors used were trained using word2vec rather than GloVe. While Word2Vec is trained on 3 million word corpus of Google News, pre-trained GloVe embeddings are trained on the Wikipedia 2014 + Gigaword 5th Edition corpora.

Some extreme 'she' occupations would be: librarian, socialite, hairdresser, nanny, bookkeeper, stylist, housekeeper etc.
Some extreme 'he' occupations would be: architect, financier, warrior, broadcaster, magician, fighter pilot, boss etc.

Considering the dissimilarities between the two embedding sets of extreme 'he' job and 'she' jobs, is it valid to assume that the correlations between the words "he" and "she" and the listed occupations still hold?


FOLLOWING IS THE LINK TO THE DATASET: https://www.kaggle.com/datasets/watts2/glove6b50dtxt
