# Music Recommendation System

A content-based music recommendation system that suggests similar songs using semantic embeddings and vector similarity search.

## Features
- Select a song and get top 5 similar recommendations
- Natural language search (e.g. "suggest relaxing songs for studying")
- Filter by Genre, Mood, Language
- Filter by Release Year
- Gradio web interface

## How to Run
1. Open `music_recommendation.ipynb` in Google Colab
2. Run all cells in order (Runtime → Run all)
3. When prompted, upload `music_dataset.json`
4. Wait for the Gradio interface to load (may take 1-2 mins to download the embedding model)
5. Use the public URL printed at the bottom, or the embedded interface, to interact with the app

## Requirements
Installed automatically via pip in the notebook:
- langchain-community
- langchain-huggingface
- langchain-chroma
- gradio

## Dataset
`music_dataset.json` — 50 songs with fields: Song Name, Artist, Genre, Mood, Tempo, Language, Release Year, Description