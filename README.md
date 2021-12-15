## Lab #1

* **Colab link**: https://colab.research.google.com/drive/13Ynzj8e7pWwJY9oi2_uU5_0STRJvfYRs?usp=sharing 

  *(File can`t be uploaded to the repository due to large size> 25 mb)*

* **Dataset**: IMDB Movie reviews https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

  *Can be also downloaded from github releases: https://github.com/bogatovam/nlp-labs/releases/tag/dataset* 

* **Results**:

| Algorithm/Model     | Data Type | Accuracy | Test loss | 
| ------              | --------- | ------   | ------    |
| KNN                 | tfidf     | 0.79     | 0.176     |
| Logistic Regression | tfidf     | 0.90     | 0.016     |
| Random Forest       | tfidf     | 0.84     | 0.15      |
| Deep Neural Network | w2vec     | 0.79     | 0.46      |
| GRU  Neural Network | w2vec     | 0.82     | 0.39      |

* **TensorBoard**: https://drive.google.com/drive/folders/1V_0A8a-YDusames3YJy9QwOBZxSVcDmP?usp=sharing

## Lab #2: Translation task

* **Link**: https://github.com/bogatovam/nlp-labs/blob/main/NLP2.ipynb 

* **Dataset**: TED dataset from tensorflow(ted_hrlr_translate)

* **Results**: The statistical model is not good for translating phrases. Attempts were made to train models EncDec+Attention and Transformer (Tensorflow tutorials were used), but due to the limited amount of resources and time, meaningful translation was not achieved. 
