# movie-recommendation-system
This project is a content-based movie recommendation system built with Python, utilizing pandas for data manipulation and scikit-learn for cosine similarity calculations. It features a user-friendly web interface created with Streamlit
# Features
- Content-based movie recommendations using cosine similarity
- Interactive web interface for easy movie selection
- Integration with TMDB API for fetching movie posters
- Display of top 10 recommended movies in an interactive grid layout
# Installation
To run this project, you need to have Python installed on your system. Then follow these steps
1. Clone the repository:
```bash
https://github.com/puppala3/movie-recommendation-system.git
```
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```
# Usage
To start the Streamlit app, run the following command in your terminal:
```bash
streamlit run app.py
```
# How it works
- Select a movie from the dropdown menu.
- Click the 'Recommend' button.
- The system will display the top 10 recommended movies based on content similarity.
- Each recommendation includes the movie poster and title.
# Data
The system uses the TMDB 5000 Movie Dataset, which includes information about movie titles, genres, keywords, cast, and crew.
# Dependencies
- pandas 
- Requests 
- streamlit 
- scikit-learn
