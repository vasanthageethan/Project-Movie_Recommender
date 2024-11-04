# 🎬 Movie Recommendation System

The Movie Recommendation System is a sophisticated, personalized GPT-based application that provides tailored movie and series suggestions based on user preferences, search criteria, and past viewing history. Built with Flask and powered by LangChain for working with GPT models, this application leverages prompt engineering and a Retrieval-Augmented Generation (RAG) approach for enhanced personalization.

## 📋 Project Overview

The purpose of this project is to help users discover movies and series that match their tastes. It enables users to search by title, genre, artist, release date, or major plot points. The system not only provides recommendations but also offers details on where to watch the content on OTT platforms.

Key features include:
- **Personalized Recommendations**: Tailored movie and series recommendations based on user history and genre preferences.
- **Detailed Search Options**: Search by title, genre, artist, release date, or plot.
- **Movie Identification from Plot Descriptions**: Capable of guessing movies based on user-provided plot summaries.
- **OTT Platform Availability**: Information on where to stream or watch recommended content.
- **Guest Access**: Recommendations for guest users without requiring login.

## 🛠️ Features

1. **Personalized GPT Model Recommendations**:
   - Utilizes a Retrieval-Augmented Generation (RAG) approach for providing recommendations based on user history and preferred genres.
   - Promotes personalization through prompt engineering.

2. **Comprehensive Search Capabilities**:
   - Search by specific criteria like title, genre, artist, and release date.
   - Input plot descriptions for the model to guess the movie.

3. **Guest User Access**:
   - Allows guest users to receive recommendations and movie details without creating an account.

4. **OTT Availability Information**:
   - Fetches data on where the recommended movie or series is available to watch on OTT platforms.

## 📂 Project Structure

```plaintext
├── app.py                  # Main Flask application file
├── templates/              # HTML templates for the Flask frontend
├── static/                 # Static files (CSS, JS)
├── keys.py                 # API keys (excluded from GitHub repository)
├── sbert.py                # Functions for loading model and data, getting plot embeddings
├── README.md               # Project documentation
├── csv_plot_rec.py         # OpenAI model functionalities
└── requirements.txt        # Python dependencies
