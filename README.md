# NLP for Nepali

This repository contains State of the Art Language models
 and Classifier for Nepali, which is official language of Nepal and
  one of the official status gained language of India.

The models trained here have been used in [Natural Language Toolkit for Indic Languages
 (iNLTK)](https://github.com/goru001/inltk)

## Dataset

#### Created as part of this project
1. [Nepali Wikipedia Articles](https://www.kaggle.com/disisbig/nepali-wikipedia-articles)

2. [Nepali News Dataset](https://www.kaggle.com/disisbig/nepali-news-dataset)

## Results

#### Language Model Perplexity

| Architecture/Dataset | Nepali Wikipedia Articles |
|:--------:|:----:|
|   ULMFiT  |  31.5  |
|  TransformerXL |  29.3  |


#### Classification Metrics

##### ULMFiT

| Dataset | Accuracy | Kappa Score |
|:--------:|:----:|:----:|
| Nepali News Dataset |  98.5  |  97.7  |

 
#### Visualizations
 
##### Embedding Space

| Architecture | Visualization |
|:--------:|:----:|
| ULMFiT | [Embeddings projection](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/goru001/nlp-for-nepali/master/language-model/embedding_projector_config.json) |
| TransformerXL | [Embeddings projection](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/goru001/nlp-for-nepali/master/language-model/embedding_projector_transformer_config.json)  |


## Pretrained Language Model

Download pretrained Language Models from [here](https://drive.google.com/open?id=1-OhdbDd7ZDqUPihN703SvPeJQTn3JRFE)


## Classifier

Download classifier from [here](https://drive.google.com/open?id=1_u5t2hH70jbS0rMtEXhjrJ388WpOkpC8)


## Tokenizer

Trained tokenizer using Google's [sentencepiece](https://github.com/google/sentencepiece)

Download the trained model and vocabulary from [here](https://drive.google.com/open?id=1AS0Yk17rTcvdWVlwB0F7MyNu70iwRsLk)