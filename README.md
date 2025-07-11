# My Book Recommendation System

This is a Flask-based book recommender app using  collaborative filtering. It helps users discover books similar to their favorite reads by leveraging collaborative filtering techniques.
**How it works:**
->A user enters the name of a book they like.

->The system uses a precomputed similarity matrix (based on user behavior) to find and recommend similar books.

->It also displays a list of the most popular books on home page based on average ratings and number of reviews.
A user enters the name of a book they like in the recommendations page.

->The system uses a precomputed similarity matrix to find and recommend similar books.

## Features
- Popular book display(Popularity based rexommendations)
- User-based book recommendation(Collaborative recommendations)
- Clean UI

## Files
- `app.py`: Flask backend
- `.csv` files: Data files, you can download it from(https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset?)
- `Notebook.ipynb`: Model(you can download the pkl file from here too...) and data prep
- `*.pkl`:pkl files(Extract the books.pkl from books.zip file)

## To Run
```bash
pip install -r requirements.txt
python app.py
