# Crowdsourced Beer Recommendation System

The aim of this project is to create the building blocks of a crowdsourced recommendation system. This recommendation system should accept user inputs about desired beer attributes of and come up with best recommendations leveraging publicly available data on web. This project scrapes publicly available Beer reviews from Beeradvocate.com.

This project followed the following approach:

  1. Scraped ~6k reviews using Selenium to fetch reviews of beers from Beeradvocate.com.
  2. Clean the data using NLTK.
  3. Use spacy similarity to find most relevant reviews related to user selected beer attributes.
  4. Find sentiment score for all the relevant reviews using ![VADER(Valence Aware Dictionary and sEntiment Reasoner)](https://github.com/cjhutto/vaderSentiment)
  5. Recommend the most relevant beers based on user aspired beer attributes
