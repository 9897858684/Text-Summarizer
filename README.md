# Text-Summarizer

This project demonstrates a simple implementation of extractive text summarization using **Python** and the **Natural Language Toolkit (NLTK)** library. The approach is unsupervised, meaning it doesn't require pre-training a model. Instead, it scores sentences based on word frequencies and selects the most important ones.

## Features

- Extractive summarization using word frequency
- Tokenization of text into words and sentences
- Removal of common English stopwords
- Scoring of sentences based on term frequency
- Generation of a concise summary from the input text


## Installation

1.Install required libraries:
<pre> pip install nltk </pre>

 2.Download necessary NLTK data:  
<pre> import nltk  
nltk.download('punkt')  
nltk.download('stopwords') </pre>
