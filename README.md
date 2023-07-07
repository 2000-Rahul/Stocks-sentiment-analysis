## Stocks-sentiment-analysis
- **Sentiment analysis** (or opinion mining) is a natural language processing (NLP) technique used to determine whether data is positive, negative or neutral. Sentiment analysis is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback, and understand customer needs.

## Import necessary libraries
- **Requests** - Requests library is one of the integral part of Python for making HTTP requests to a specified URL. Whether it be REST APIs or Web Scraping, requests is must to be learned for proceeding further with these technologies. When one makes a request to a URI, it returns a response.
- **Beautifulsoup** - Beautiful Soup is a library that makes it easy to scrape information from web pages. It sits atop an HTML or XML parser, providing Pythonic idioms for iterating, searching, and modifying the parse tree.
- **Transformers** - Transformer is an architecture for transforming one sequence into another one with the help of two parts (Encoder and Decoder). The PegasusTokenizer class will convert our sentences into tokens. This is a numbered representation of our sentences. pegasus modole use for reading a document and producing a summary.
-  **SentencePiece** -  It's actually a method for selecting tokens from a precompiled list, optimizing the tokenization process based on a supplied corpus.
-  **RegularExpression(re)** - The term re stands for Regular expression.It is a sequence of different characters which describe the particular search pattern.It is mainly used for searching and manipulating text strings. In simple words, you can easily search the pattern and replace them with the matching pattern with the help of regular expression.

## Tickers
- A ticker is a type of stock symbol that describes information about the stock of a company. Tickers take the form of shapes, characters, numbers and colours, and are indicative of any kind of change that a security on the financial market shows.
- In this project we have taken tickers of 'gme','tsla','btc' and perform Sentiment Analysis on them.

## Strip Unwanted URLs
- URLs which have these unwanted words frequently are stripped ['maps','policies','preferences','accounts','support'].
## Summarize Articles
- Articles have summarized by defining a function, in which tokenizers are encoded, numbers of words are limited.
## Pipeline
- Pipelines are made of:

    A tokenizer in charge of mapping raw textual input to token. <br>
    A model to make predictions from the inputs. <br>
    Some (optional) post processing for enhancing model’s output.
- **Sentiment Analysis Pipeline** <br>
  from transformers import pipeline <br> 
  sentiment = pipeline("sentiment-analysis")
- ![image](https://github.com/2000-Rahul/Stocks-sentiment-analysis/assets/136818857/6aaa5c6d-db82-486e-abc4-f770aee76e25)
  

