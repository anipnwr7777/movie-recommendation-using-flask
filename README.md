
# Movie recommendation engine using flask and AJAX.

## Features

- Web development on top of a machine learning model
- Responsive webpage
- Web Scraping
- Asynchronous requests
- Autocomplete during movie searching.

## Demo

### this project has been deployed on heroku.

https://movie-recommend-using-flask.herokuapp.com/

## Tech used
***Framework:*** Flask

***API:*** TMDB

***Frontend:*** HTML, CSS, JavaScript

***Others:*** AJAX, Web Scraping

## Note
The source code contains proper comments for understanding

## Machine learning model
cosine similarity and similarity scores are calculated to check the similarity between movies.
Refer <a href="https://www.machinelearningplus.com/nlp/cosine-similarity/"> this </a> link 

## Description


This is a content based movie recommendation engine that is built using flask in the backend. 

Movie recommender systems are of various types. You can read about them <a href = "https://www.bluepiit.com/blog/classifying-recommender-systems/"> on this link</a>.

A content-based recommender learns a profile of the new user’s interests based on the features present, in objects the user has rated. It’s basically a keyword specific recommender system here keywords are used to describe the items. Thus, in a content-based recommender system the algorithms used are such that it recommends users similar items that the user has liked in the past or is examining currently.

### The dataset has been picked from Kaggle. 

<a href="https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset">IMDB 5000 movie dataset </a>

This only contains data till year 2016. 

For 2017 data has been picked from <a href="https://www.kaggle.com/rounakbanik/the-movies-dataset"> here </a> and <a href="https://kaggle.com/rounakbanik/the-movies-dataset?select=movies_metadata.csv "> here </a>



For data of year 2018-19-20, I have done webscraping from Wikipedia.


https://en.wikipedia.org/wiki/List_of_American_films_of_2018

https://en.wikipedia.org/wiki/List_of_American_films_of_2019

https://en.wikipedia.org/wiki/List_of_American_films_of_2020

### For fetching all the details of a given movie I have used an API by TMDB 

details include images, genre, title , release date, director, rating
https://www.themoviedb.org/documentation/api.

## How to get the API Key?
Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved

## Steps to run the project:
1. Clone this repository locally.
```bash
  git clone https://github.com/anipnwr7777/movie-recommendation-using-flask
```
2. Install requirements using the command 
```bash
  pip install -r requirements.txt
```
3. Get your API Key.
4. Replace 'YOUR_API_KEY' in /static/recommend.js with your API key.
5. Open the terminal in your IDE and enter
```bash
  python main.py
```
6. Open your browser and enter this addres as URL
```bash
  http://127.0.0.1:5000/
```
7. That's it your recommendation system is up and running.

  
## Contributing

Contributions are always welcome!
  


  
