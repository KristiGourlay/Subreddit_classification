# Executive Summary


For this project, I successfully scrape two sub-reddits and than used NLP and a Bayes Classifier to predict from which sub-reddit the post came. The two sub-reddits that I chose to compare are:
              
              -TalesFromYourServer
              -TalesFromTheCustomer

Mainly all of the posts located in 'TalesFromYourServer' have to do with stories being shared by servers and bartenders about their experiences in the industry. The 'TalesFromTheCustomer' are primarily about customers sharing their experiences in restaurants, but also features stories about other service areas. My objective in this project was to train a model to predict from which sub-reddit each comment, labeled 'selftext', belonged. The scraping of the reddit site was performed in the  notebook, labeled "scraping". I successfully scraped 40 pages from each sub-reddit and concatenated the two data frames together. 'TalesFromYourServer' was labeled 0 and 'TalesFromTheCustomer' was labeled 1 for classification purposes. The subsequent modeling takes place in the notebook, labeled "modeling". 
