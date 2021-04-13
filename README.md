# NLP-Group-Project

This group project was conducted as part of the MSc Business Analytics programme at UCL for the NLP module.

An increase in digitalisation has led to an explosive growth of emails in our inbox. This is becoming particularly troubling as an average worker spends approximately 
28% of their working hours reading and replying to emails (McKinsey Global Institute, 2012). For this project scope, we will be analysing emails from Enron Corporation to 
classify the sentiment in an email and then summarise it through the use of natural language processing.

We use Snorkel to apply sentiment labels to the unlabelled data. 

Sentiment Analysis

We use two methods to calculate the sentiment classification. First, we build an RNN model architecture with LSTM cells from scratch. For our second model, 
we will use a pre-trained model from the HuggingFace Transformers library. 

Text Summarisation

Text summarisation can be extractive or abstractive. We identify essential excerpts from thetext in extractive summarisation, which are used as part of our 
summary. Abstractive text summarisation employs more complex and powerful NLP methods to interpret a text andcreate summaries of it. As this method is difficult and 
computationally expensive, we opted to use extractive. We will use BERT, GPT-2 and XLNet transformer models from the Hugginface library to compare with hand-annotated labels.
