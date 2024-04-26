## Overview

This project focuses on various aspects of natural language processing, including Named Entity Recognition (NER), tokenization, and language modeling and Fine-tuning. It is based on the Naamapadam corpus.

#   link :- Naamapadam Dataset

"https://huggingface.co/datasets/ai4bharat/naamapadam/tree/main/data"

## Tasks

## Download the Corpus:

Choose the corpus file corresponding to your mother tongue from the provided link.

## Manual Annotation in BIO Format:

For a set of 25 sentences, identify the named entities (PER, LOC, ORG, MISC, and O) and mark them in BIO format. Submit the annotated sentences on the provided online portal.

## Fine-tuning IndicBERT and IndicNER:

Use the Naamapadam corpus for fine-tuning both models with a train/validation/test split of 70%/10%/20%.
Train each model for at least 20,000 sentences and for at least 3 epochs.

Compare the models using macro-F1 score on the 20% test set and report the training and validation macro-F1 scores.

## Use ChatGPT for NER: 

Pass the 25 sentences from question 1 to ChatGPT and query the NERs. Submit the output.

## Evaluation: 

Test the outputs of both models (IndicBERT and IndicNER) and ChatGPT against the manually annotated sentences from question 1. Calculate precision, recall, and macro-F1 score.

## Learning and Optimization: 

Write a detailed report on the hyperparameters you have tuned, their significance, and the optimal values chosen. Mention the outputs of both models in the report.

## Requirements

Python (3.6+)
Jupyter or account on google colab platform or mobile verified account on keggle platform
import all libraries mentioned in code
Access to gujarati language corpus and online platform for Question 1
replace file paths with your own paths if required 

## Contributor

Nij Padariya
231110032