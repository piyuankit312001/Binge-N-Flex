# Binge n Flex

![Python](https://img.shields.io/badge/Python-3.9-blueviolet)
![Framework](https://img.shields.io/badge/Framework-Flask-red)
![Frontend](https://img.shields.io/badge/Frontend-HTML/CSS/JS-green)
![API](https://img.shields.io/badge/API-TMDB-fcba03)

Binge n Flex recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details are fetched by -
- An API by [TMDB](https://www.themoviedb.org/documentation/api) for the movies (title, genre, runtime, rating, poster, etc)
- IMDB id is used to get the movie information from the api.
- Web Scraping is done to get the reviews given by the user in the IMDB site 
- `beautifulsoup4` is used to get reviews and then sentiment analysis is performed on those reviews.

## Note

If the movie you are looking for is not auto-suggested. Just type its name and click on "Enter". You will be good to go even if you made some typo.

Source Code: https://github.com/Complexity-Hackathon/Reva-Hack-2020

## How to get the API key?

- Create an account in https://www.themoviedb.org/, 
- Click on the `API` link from the left hand sidebar in your account settings 
- Fill all the details to apply for API key. 
- If you are asked for the website URL, just give "NA" if you don't have one. 
- You will see the API key in your `API` sidebar once your request is approved.

## How to run the project?

1. Install all the libraries mentioned in the [requirements.txt](https://github.com/Complexity-Hackathon/Reva-Hack-2020/blob/main/Movie%20recommender/requirements.txt) file.
2. Clone this repository in your local system.
3. Replace API_KEY_HERE in the `static/recommend.js` file.
4. Open the command prompt from your project directory and run the command `python main.py`.
5. Go to your browser and type `http://127.0.0.1:5000/` in the address bar.
6. Remember your port-number can be different for this and it is also displayed on the prompt if successfully done. 
7. Hurray! That's it.

To run requirements.txt go to the directory in CMD and run-
```sh
$ pip install -r requirements.txt
```

### Sources of the datasets 

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)

**By - Team Complexity**