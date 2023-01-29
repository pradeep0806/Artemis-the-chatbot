# Artemis the Chatbot

This is a chatbot using pytorch

* The implementation is straightforward with a Feed Forward Neural net with 2 hidden layers.
* The approach is inspired from this [video](https://youtu.be/RpWeNzfSUHw)
* you need to install `nltk.tokenize.punkt`
* packages used: torch,numpy,nltk 

## Installation
* `pip install numpy`
* `pip install torch`
* `pip install nltk`

## Downloading punkt

for downloading **punkt** you need to do the following steps in IDLE or in your interpretor

1. `>> import nltk`
2. `>>nltk.download('punkt')`

## Customization

This chatbot can be customized with changing the tags, patterns and possible responses in intents.json

## Functions

* `tokenize`function
	this function converts the words in sentence to tokens
* `stem` function
	this function do stemming of the tokens and convert all the tokens to lowercase
* `bag_of_words` function converts the stemmed words to 0's and 1's to feed into network
