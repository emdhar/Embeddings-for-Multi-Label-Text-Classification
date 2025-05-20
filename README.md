# Embeddings-for-Multi-Label-Text-Classification
The objective for this project is to compare two embedding alternatives on a text classification task. A simple text classification model based on word counts is to be included in the comparison as a base-line. The dataset to be used for this assignment is in the file 'BBC_news.csv'.
# Key Results
|Word Embedding Technique|Conclusions|
|-----|----------|
|**CountVec**| ~94% accuracy using CountVectorizer + Logistic Regression; adding bigrams further improves performance; extremely fast and easy to interpret. |
|**Doc2Vec**| ~97% accuracy with Doc2Vec (PV-DBOW, 128-dim embeddings, 60 epochs); captures the context in which the word is present, at the cost of longer training time. |
|**BERT**| ~99% accuracy by fine-tuning BERT to best parameters: learning rate 3 ×10⁻⁵, batch size 4, 4 epochs; offers best accuracy given its capability to predict masked tokens in a sentence and to predict sentence sequences but requires high compute resources. |

