# Artemis-the-chatbot

This is a pytorch based Chatbot  created for getting reviews of books

The implementation is straightforward with a Feed Forward Neural net with 2 hidden layers.

The approach is inspired by https://youtu.be/RpWeNzfSUHw

you need to install nltk.tokenize.punkt for tokenization

packages used: torch,numpy,nltk

installation
	pip install torch
	pip install numpy
	pip install nltk

for downloading punkt, in IDLE
	>>import nltk
	>>import nltk.download('punkt')

Customization
	this chatbot can be customized with changing the tags, patterns and possible responses in intents.json


'''tokenize''' function
	this function converts the words in sentence to tokens

'''stem''' function
	this function do stemming of the tokens and convert all the tokens to lowercase

'''bag_of_words'''
	this function converts the stemmed words to 0's and 1's to feed into network
