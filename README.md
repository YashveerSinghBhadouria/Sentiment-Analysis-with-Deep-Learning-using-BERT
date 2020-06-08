# Sentiment-Analysis-with-Deep-Learning-using-BERT
BERT, which stands for Bidirectional Encoder Representations from Transformers, is a neural network-based technique for natural language processing pre-training. 
In plain English, it can be used to help Google better discern the context of words in search queries.

For example, in the phrases “nine to five” and “a quarter to five,” the word “to” has two different meanings, which may be obvious to humans 
but less so to search engines. BERT is designed to distinguish between such nuances to facilitate more relevant results.

## Working
The breakthrough of BERT is in its ability to train language models based on the entire set of words in a sentence or query (bidirectional training)
rather than the traditional way of training on the ordered sequence of words (left-to-right or combined left-to-right and right-to-left). 
BERT allows the language model to learn word context based on surrounding words rather than just the word that immediately precedes or follows it.

Google calls BERT “deeply bidirectional” because the contextual representations of words start “from the very bottom of a deep neural network.”

## Project 
In this project I analyze a dataset for sentiment analysis, learned how to read in a PyTorch BERT model, 
and adjusted the architecture for multi-class classification.
I also learn how to adjust an optimizer and scheduler for ideal training and performance. 
In fine-tuning this model, I learned how to design a train and evaluate loop to monitor model performance as it trains, including saving and loading models. 
Finally, I build a Sentiment Analysis model that leverages BERT's large-scale language knowledge.

## Resource
Project is entirely perormed on Google Colab. The repo contains a gist of it also the original code and Data for refences.
