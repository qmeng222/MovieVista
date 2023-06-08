# MovieVista

## Overview:

- About: a movie plot generator (generates a movie plot description based on seed input) and content-based movie recommender
- Highlights:
  1. Utilized seed input from Kaggle, including movie plots scraped from Wikipedia.
  2. Conducted cost estimation prior to embedding and established a cache of embeddings to avoid recomputing.
  3. Transformed the movie plots into 1536-dimensional embeddings for accurate similarity analysis.
  4. Implemented the K Nearest Neighbor algorithm for personalized and accurate movie recommendations.

## Setup:

1. create a virtual environment: `python -m venv env`
2. activate the virtual environment: `source env/bin/activate` (all subsequent steps should be performed within the virtual environment)
3. upgrade the pip package manager to the latest version within the current Python environment: `python -m pip install --upgrade pip`
4. install the OpenAI package and the python-dotenv package:
   ```
   pip install openai
   pip install python_dotenv
   ```
   or simply `pip install openai python_dotenv` altogether!
5. recreate the same environment on a diffrent machine by running `pip install -r`
6. get started with Nomic:
   - install the Nomic client: `pip install nomic`
   - login my Nomic account: `nomic login`
   - follow the instructions to obtain my access token, and enter my access token with `nomic login [token]`

## Resources:

1. Seed input:
   - Context: plot summary descriptions scraped from Wikipedia
   - Download: [jrobischon](https://www.kaggle.com/jrobischon)'s [Wikipedia Movie Plots dataset](https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots) hosted on Kaggle
2. OpenAI documentation: [How can I retrieve K nearest embedding vectors quickly?](https://platform.openai.com/docs/guides/embeddings/how-can-i-retrieve-k-nearest-embedding-vectors-quickly)
3. OpenAI cookbook: [Using Vector Databases for Embeddings Search](https://github.com/openai/openai-cookbook/blob/main/examples/vector_databases/Using_vector_databases_for_embeddings_search.ipynb)
4. OpenAI [embeddings_utils.py](https://github.com/openai/openai-python/blob/main/openai/embeddings_utils.py)
