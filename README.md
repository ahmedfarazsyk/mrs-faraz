# Movie Recommender System

This project is a GUI-based movie recommender system that helps users find relevant movies based on their search queries. It uses data from The Movie Database (TMDB) API and applies similarity-based recommendation techniques to suggest movies. The app is built using **Python** and **Streamlit** and can be easily run through `app.py`.

## Features

- Provides movie recommendations based on user search input.
- Fetches movie details using the TMDB API.
- Simple and intuitive user interface built using Streamlit.
- Recommends movies similar to the one searched for, based on data in `movies_dict.pkl` and `similarity.pkl`.

## Project Structure

- **app.py**: The main file to run the application.
- **movies_dict.pkl**: Contains the pre-processed movie dataset.
- **similarity.pkl**: Stores the similarity matrix for movie recommendations.
- **requirements.txt**: Contains the list of required Python libraries.

## Tools and Technologies

- **Python**: Core programming language for the project.
- **Streamlit**: Used to build the web-based user interface.
- **TMDB API**: Used to fetch movie data like titles, posters, and descriptions.
- **Pickle**: For loading pre-processed movie data and similarity matrix.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ahmedfarazsyk/mrs-faraz.git
   cd movie-recommender-system
