# Poetry Generation in Roman Urdu using spaCy

## Introduction
This project aims to generate poetry in Roman Urdu using a dataset of poems by famous Urdu poets such as Allam Iqbal and Ghalib. The text processing will be done using the spaCy pipeline, a popular library for natural language processing in Python. The poetry generation problem will be solved using n-gram models, which are statistical models used to predict the next word in a sequence based on the previous n words.

## Requirements
To run this project, the following software and packages are required:
* Python 3.x
* spaCy
* Numpy
* Pandas

## Usage
The steps to generate poetry in Roman Urdu using spaCy and n-gram models can be summarized as follows:
1. Clone the repository containing the code and data.
2. Install the required packages such as spaCy, Numpy and Pandas.
3. Load the poetry corpus, which is a large collection of poems by famous Urdu poets, into the program.
4. Tokenize the corpus, which means splitting it into a list of words.
5. Generate n-gram models using the tokenized corpus. This involves counting the frequency of occurrence of each word after a specific context, represented by the previous n words.
6. Use the generated n-gram models to generate poetry by predicting the next word in a sequence based on the previous n words.

## Conclusion
This project provides a general overview of how to generate poetry in Roman Urdu using spaCy and n-gram models. The generated poems will have a similar style and structure as the original poems by famous Urdu poets, but the content will be generated algorithmically. The code and data for this project can be easily adapted and modified to generate poetry in other languages or to use different text processing and poetry generation techniques.
