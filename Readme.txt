How to handle OOVs in toxic comment classification

Sources used:
Pooled GRU + FastText: https://www.kaggle.com/yekenot/pooled-gru-fasttext

Bi GRU + attention: https://www.kaggle.com/yshubham/bi-gru-and-attention-fork

Exploring Multi-label text classification: https://www.kaggle.com/rhodiumbeng/classifying-multi-label-comments-0-9741-lb

Bi-LSTM + Conv Layer: https://www.kaggle.com/fizzbuzz/bi-lstm-conv-layer-lb-score-0-9840

text cleaning: https://towardsdatascience.com/multi-label-text-classification-with-scikit-learn-30714b7819c5

Software requirement:
tensorflow : 1.15
python: 3.6
CUDA: V10.0.130

Changes:
Built FastText word embeddings using Gensim
Built a lookup function to replace oov words in the sentences
Built an ensemble model 
Made adequate changes to the models avaible to fit our requirements