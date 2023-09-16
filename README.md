# NLP-POSPair-Refined
The NLP-POSPair-Refined is an improved and more user-friendly representation for Natural Language Processing. The POSPair model in this repository exemplifies data representation based on part-of-speech and relations between different part-of-speeches. Rather than just focusing on closeness, frequency, or syntactic relatedness, the POSPair model takes into account the actual form of relationship between words, which words are related, and how they are related. Particular focus is placed on the word pairs as unit values generated considering the context.

## How It Works:
Words are categorized into several types of part-of-speech based on use and functions. This model also clearly defines how words of specific part-of-speech are interrelated providing some meaningful relation. The one-sided relations between the part-of-speech are properly represented through word pairs which are generated in context of the whole text.

## GETTING STARTED:
This section provides information on prerequisites, installation, and various functions of POSPair.

### PREREQUISITES:
Ensure to have Python 3.0 or higher and Stanford Core NLP (3.9.2) installed.

### INSTALLING:
Use pip install command as shown below to install POSPair.
```
1. pip install POSPair
```
Follow the instruction on [how to install and run Stanford CoreNLP server](http://stanfordnlp.github.io/CoreNLP/corenlp-server.html#getting-started)

[**Note**: The Stanford CoreNLP Server port should be: 9000]

### BUILT WITH:
The project has been built using Python, Stanford Core NLP, Pycorenlp, and Gensim (Word2Vec).

### CONTRIBUTING:
Read [CONTRIBUTING.md](https://github.com/nodeshake/NLP-POSPair-Refined/blob/master/CON