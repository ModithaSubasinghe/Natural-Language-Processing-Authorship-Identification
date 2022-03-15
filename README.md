[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# Natural Language Processing : Authorship Identification

This challenge is to encourage you to learn the most popular natural language processing algorithms.  

## Objectives

To study a wide variety of natural language processing techniques

## Branch
This only has the main branch.
Please watch this page to receive updates and corrections.

## License
This code is hosted in a private repository to regulate access. 
You can share your data & code under MIT license.
 
## Datasets:
Download the unicode text versions of the novels from [https://www.gutenberg.org/](https://www.gutenberg.org/).
Further instructions are given below.

## Instructions
Use the following steps to complete the challenge.
  
 1. Download the text (Plain Text UTF-8) of at least 5 books from each author in the following table

	| Author | URL |
	|--------|-----|
	| Charles Dickens |  https://www.gutenberg.org/ebooks/author/37  |
	| Jane Austen |  https://www.gutenberg.org/ebooks/author/68  |
	| Sir Arthur Conan Doyle | https://www.gutenberg.org/ebooks/author/69  |
	| George Eliot |  https://www.gutenberg.org/ebooks/author/90  |
	| Mary Shelley (replace this author) |  https://www.gutenberg.org/ebooks/author/61  |

1. Extract mutually exclusive fragments, each having L number of words, where L is a tunabe parameter, from the text of each book to prepare a dataset for classification. The extractions should be from the novel content not from the topics or table of contents. Prepare at least 5000 records, 1000 records from each author at minimum.
2. Use suitable train, test and validation splits, the results are to be averaged over atleast 20 random states
3. Write a reusuable Jupyter note book to test the following technologies for the data set prepared. Include your references if the models are copied.
	1. Logistic Regression, Support Vector Machines, Random Forest, Naive Bays and XGBoost Classifiers based on the Bag of Word and TF-IDF. Achieve atleast 70% accuracy.
	2. GRU, LSTM, Bidirectional LSTM with Glove and Word2vec embedings. Achieve atleast 80% accuracy.
	3. Transformers and BERT. Achieve atleast 80% accuracy.
4. Tune any model to reach 90% accuracy to complete the challenge. The results are to be averaged over atleast 20 random train, test, validation splits.
5. Inform DataDisca for evaluation 

## General Conditions

1. Code should follow PEP8 Standard
1. Host your code on your GitHub in a public or private repository as you prefer. 
- If it is a public repository, send the link for us to evaluate.
- If it is a private repository, share (view only) with our GitHub usernames [DataDisca](https://github.com/DataDisca) and/or [mbtl-datadisca](https://github.com/mbtl-datadisca).

	Send us a notification to start the evaluation.
	We evaluate your code for your technical progress.

## Sponsor
DataDisca Pty Ltd, Melbourne, Australia

[https://www.datadisca.com](https://www.datadisca.com)
