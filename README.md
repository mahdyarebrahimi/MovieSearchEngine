# Movie Search Engine

This project demonstrates a basic movie recommendation system using sentence embeddings and summarization. The system:

- Loads a dataset of movies (with titles, overviews, and genres).
- Creates embeddings for each movie’s combined text (title + overview) using a SentenceTransformer model.
- Summarizes movie overviews using a Hugging Face summarization pipeline.
- Uses fuzzy matching to interpret user queries (e.g., "best", "newest", "popular" movies, and various genres).
- Performs semantic searches to find similar movies based on user input.
- Displays results interactively using Jupyter Notebook widgets.



## Getting Started

1. **Install Dependencies:**  
   Run the following command:
   ```bash
   pip install -r requirements.txt
2. **Place your CSV file:**
   Ensure Movies.csv is in the project directory.
3. **Launch the Notebook:**
   Open movie_recommender.ipynb in Jupyter Notebook.
