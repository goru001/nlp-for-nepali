# NLP for Nepali

This repository contains State of the Art Tokenizer, Language model
 and Classifier for Nepali, which is official language of Nepal and
  one of the official status gained language of India.

## Dataset

* Download [Nepali Wikipedia Articles Dataset](https://drive.google.com/open?id=1Yh8BlJ5bydbvZaOQEmRPlTEDZjIIoAYN) (38,757 articles) which I scraped, cleaned and
used to train the language model

* Download [Nepali News classification Dataset](https://drive.google.com/open?id=1Vm0UJ3FfWP-3guSan3FZsOV4q7rYuJIG) which I scraped and used to train 
the classifier

## Results

#### Language Model

`on 30% validation set`

* Perplexity of language model: ~32

#### Classifier

* Accuracy of classification model: ~97%
* Kappa score of classification model: ~96

## Pretrained Language Model

Download pretrained Language Model from [here](https://drive.google.com/open?id=1-OhdbDd7ZDqUPihN703SvPeJQTn3JRFE)


## Classifier

Download classifier from [here](https://drive.google.com/open?id=1_u5t2hH70jbS0rMtEXhjrJ388WpOkpC8)


## Tokenizer

Trained tokenizer using Google's [sentencepiece](https://github.com/google/sentencepiece)

Download the trained model and vocabulary from [here](https://drive.google.com/open?id=1AS0Yk17rTcvdWVlwB0F7MyNu70iwRsLk)