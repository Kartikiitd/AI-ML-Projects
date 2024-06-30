## Movie-Recommendor System

## Project Overview
This project finds the similar movies using the given input. This is a content based recommendor system .

## Dataset
The dataset is sourced from kaggle and various features of movies and related parameters.

## Data Preprocessing
- clean the data
- remove the english words, punctuations etc.
- change the words to its root words
- Vectorise the data 

## Model Building
- We convert every movie feature into a vector 
- Further we find the similarity matrix of every movie with other movie
- for every movie we find the most similar movies & fetch the required no. of top movies

## Model working
- Once we run all the cells we get a dropdown at the bottom where we can find the list of movies
- Here we can select for the required movie and the next moment we get a list of 5 movies.
- The movie names in itself is a link where one can click to google search for info. 

## Tools and Technologies
- **Language:** Python
- **Libraries:** Pandas, NumPy,nltk , porterStemmer, Scikit-learn, CountVectorizer , Cosine_Similarity ,ipywidgets , IPython.display
- **IDE:** Jupyter Notebook

## Acknowledgments
Online resources and educators for providing guidance and insights.
