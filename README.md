Overview

While my initial project deals with rule based chatbot, in this project I developed retrieval based chatbot. As the retrieval based chatbot needs more data to process, hereby scraped the data using beautiful soup from the wikipedia anout the Human Organs.

Technical Aspect

Machine Learning :

Created the sentence list with the scraped data.
Once the user feeds the Input, appends that to the existing sentence list.
Hereby I have used Tf-Idf Vecorizer for the vector representation of list.
With the generated vectors, found the similarities based on cosine similarity approach.
Fetch the top 1 similar response and return it back to the UI
Website: Build a website using a Flask. Deployed the website in Heroku with all the necessary packages mentioned in the required files.

Demo: https://organos-retrieval.herokuapp.com/
