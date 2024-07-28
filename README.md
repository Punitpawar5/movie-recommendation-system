# movie-recommendation-system
Built a movie recommendation system using machine learning. When the user searches for a movie, it will recommend the top similar movies. This repository contains an end-to-end movie recommendation system built using a dataset of 5000 TMDB movies. The system is built using Python and the Streamlit library. The core functionality relies on the TMDB API to access movie data. The project aims to provide users with a user-friendly interface to get movie recommendations based on their input. It takes into account movie names, genres, cast, and crew to provide accurate recommendations.

Key Features: User-Friendly Interface: The interface is built using Streamlit, making it easy to use even for non-technical users.

Movie Recommendations: Users can input a movie title, and the system will provide a list of recommended movies based on similarity.

API Integration: The project uses the TMDB API to fetch data about movies and uses that data to provide recommendations.

Code Reusability: The code is modular and can be reused for other recommendation systems with minor modifications.

Styling and Customization: The app can be further customized with CSS for styling and a variety of widgets for user inputs.

Deployment: The project can be deployed on various platforms like Streamlit Sharing, Heroku, or Docker.

Dependencies: Streamlit: To build the user interface. Pandas: For data manipulation. Requests: For making HTTP requests to the TMDB API.

## Project Structure

```plaintext
movie-recommendation-system/
│
├── data/
│   ├── tmdb_movies.csv
│
├── notebooks/
│   ├── data_preparation.ipynb
│   ├── feature_engineering.ipynb
│   ├── model_training.ipynb
│   ├── api_deployment.ipynb
│
├── src/
│   ├── __init__.py
│   ├── data_preparation.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   ├── api.py
│
├── Dockerfile
├── requirements.txt
├── README.md
