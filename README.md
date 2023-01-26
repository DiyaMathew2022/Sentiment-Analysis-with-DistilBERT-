# Sentiment-Analysis-with-DistilBERT-
Sentiments analyzing App implemented with transformers and Streamlit

# What is Sentiment Analysis ? 

Sentiment analysis is a technique in  Natural Language Processing (NLP).  It identifies the polarity of a given text. One of the most widely used sentiment analysis techniques labels data into positive, negative, and neutral categories.  

 

# Why Sentiment Analysis is Important? 

Sentiment analysis automatically enables you to understand how people are talking about a specific topic, get insights for data-driven decisions, and automate business processes instead of manually sorting data. 

## Main applications of Sentiment analysis are: 

Get insights into what your customers like and dislike about your product by analyzing feedback from surveys and product reviews. 

Understand how your brand is being talked about compared to your competitors by analyzing social media mentions. 

Real-time analysis of support tickets to identify angry customers and prevent churn. 

 

# How to create a Sentiment Analyzing model ? 

The best way to create a model for sentiment analysis is with transformer based models. This project uses DistilBERT model for sentiment analysis. DistilBERT  is a faster, lighter, cheaper and smaller version of BERT (Bidirectional Encoder Representations from Transformers). While preserving over 95% of BERT's performance, it is 40% smaller and 60% faster than BERT. 

# DATASET 

The dataset used for fine tuning DistilBERT for this project is IMBD dataset. This dataset is directly loaded from the HuggingFace Hub using load-dataset(). 

IMBD is a large Movie Review Dataset. It contains 25,000 movie reviews labeled by sentiment for training a model and 25,000 movie reviews for testing it.  
