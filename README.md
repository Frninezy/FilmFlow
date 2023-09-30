# FilmFlow

This Telegram bot offers movie recommendations by analyzing the similarity between movie descriptions using a content-based recommender system.

## How it Works

The bot operates in two main modes:

1. **Interest-Based Recommendations:** 
   - Initiated by clicking the "Write film themes you are interested in" button.
   - User messages are broken down into tags.
   - Films with tags most similar to the user's interests are recommended.

2. **Favorites-Based Recommendations:** 
   - Initiated by clicking the "Write a few of your favorite films, separated by semicolons" button.
   - User-specified movies are located in the dataset, and their tags are combined for searching.
   - If multiple movies with the same name are found, the user is prompted to choose from them, with additional film data provided for clarity.

This bot simplifies the process of discovering new movies that align with your interests or favorite films.

## Installation 

```bash
   cd FilmFlow
   pip install -r requerments.txt
