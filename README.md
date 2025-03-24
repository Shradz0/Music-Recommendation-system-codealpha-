# Music_Recommendation_System
A Music Recommendation System project using Natural Language Processing (NLP) for song recommendations based on song lyrics and textual data.

# Table of Content

* [Brief](#Brief)
* [DataSet](#DataSet)
* [How It Works](#HowItWorks)
* [Tools](#Tools)
* [Remarks](#Remarks)
* [Usage](#Usage)
* [Sample Run](#SampleRun)


# Brief

With the growing popularity of music streaming platforms, providing personalized song recommendations based on user preferences is essential. This project implements a song recommendation system that predicts similar songs based on the lyrics of a given song using Natural Language Processing (NLP) and cosine similarity. The system uses a TF-IDF vectorizer to convert song lyrics into a numerical format and computes the cosine similarity to recommend the most similar songs to the user.


# DataSet

The dataset used in this project is a collection of song lyrics from various songs in the [Spotify Million Song Dataset](https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset). This dataset contains various features such as song names, lyrics, and metadata associated with each song. The song lyrics are used for calculating the similarity between songs.


# How It Works

- The dataset is loaded from a CSV file.
- The text data (song lyrics) is preprocessed by converting it to lowercase and removing unwanted characters such as newlines.
- Tokenization and stemming are performed to process the text and reduce words to their root form.
- The TF-IDF vectorizer is applied to convert the preprocessed song lyrics into numerical vectors.
- Cosine similarity is calculated between song vectors to determine the most similar songs.
- The system returns a list of recommended songs based on the similarity score.



# Tools & Libraries

I. Jupyter Notebook & VS Code

II. Python 3.x

III. pandas

IV. nltk

V. pickle

VI. scikit-learn

VII. spotipy

VIII. Streamlit



# Remarks
* This Python program was run and tested in Jupyter Notebook.
* Ensure the required libraries are installed by running:

  ```bash
  pip install pandas nltk scikit-learn streamlit spotipy

# Usage

To begin utilizing this application, follow these steps:

1. Clone this repository:
   
   ```bash
   git clone https://github.com/GOAT-AK/Music_Recommendation_System

2. Navigate to the cloned repository:

   ```bash
   cd Music_Recommendation_System

3. Run the Jupyter Notebook:

   ```bash
   Music_Reco_NLP.ipynb

4. Launch the Streamlit app:
   
   ```bash
   streamlit run M_app.py


# Sample Run


* Type or Select a song from the dropdown

![Image 22-11-2024 at 5 06 pm](https://github.com/user-attachments/assets/c8294a1a-6b18-49db-96d3-b7947bb7ad12)


<hr>


* Recommendations

![Image 22-11-2024 at 5 05 pm](https://github.com/user-attachments/assets/73ea8688-74d9-46e3-9b86-08acca71e296)





  
