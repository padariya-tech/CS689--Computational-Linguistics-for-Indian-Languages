## Overview
This project focuses on various aspects of natural language processing, including Unicode correction, character and syllable analysis, word group identification, and tokenizer comparison. The tasks are performed on a corpus available from 
#   link :- "https://bangla.iitk.ac.in/assignment_cs689/cs689_100mbs/"

## Tasks

## 1. Unicode Correction
Convert the corpus to ISO15919 or ITRANS format.
Correct Unicode characters, counting consonants with a halant character as 1 and without as 2.
## 2. Character and Syllable Analysis
Find all characters and syllables in the corpus.
Store them in descending order of their frequencies.
Find the top-20 frequent uni-gram and bi-gram frequencies of characters and syllables.
## 3. Word Group Identification
For a random set of 25 sentences, identify all word groups, including inflections, verb auxiliaries, and compounds.
Write them down in a comma-separated manner.
## 4. Tokenizer Comparison
Run Unigram, BPE (vocabulary sizes, V = 1k, 2k), mBERT (max length = 1k, 2k), IndicBERT (max length = 1k, 2k), and White-space tokenizers on the entire corpus.
Find the unigram frequencies of tokens and bi-gram frequencies of tokens, syllables, and characters for each tokenizer.
## 5. Evaluation
Assume the set of tokens from Task 3 as the ground truth set.
For each tokenizer, find the precision, recall, and F-score for the 25 sentences.
## 6. Conclusion
Summarize the findings from the tokenizer comparison.
Discuss the implications and potential improvements for natural language processing.

## Requirements
Python (3.6+)
Jupyter or account on google colab platform
Sentence Piece or similar libraries for tokenization
Access to gujarati language corpus and online platform for Task 3
replace file paths with your own paths if required 
for jupyter notebook 
pip install torch other than code file



## Contributor
Nij Padariya
