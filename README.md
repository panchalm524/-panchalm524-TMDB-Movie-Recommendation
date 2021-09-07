# TMDB-Movie-Recommendation
Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.


Check out the live demo: https://mrswsa.herokuapp.com/

## How to get the API key?
Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.

## How to run the project?
* Clone or download this repository to your local machine.
* Install all the libraries mentioned in the requirements.txt file with the command pip install -r requirements.txt
* Get your API key from https://www.themoviedb.org/. (Refer the above section on how to get the API key)
* Replace YOUR_API_KEY in both the places (line no. 15 and 29) of static/recommend.js file and hit save.
* Open your terminal/command prompt from your project directory and run the file main.py by executing the command python main.py.
* Go to your browser and type http://127.0.0.1:5000/ in the address bar.
* Hurray! That's it.

## Sources of the datasets
IMDB 5000 Movie Dataset
The Movies Dataset
[List of movies in 2018](https://www.kaggle.com/rounakbanik/the-movies-dataset)
List of movies in 2019
List of movies in 2020
