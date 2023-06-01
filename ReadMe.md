# MovieVista

## Overview:

- About: a movie plot generator (generates a movie plot description based on seed input) and content-based movie recommender

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

## Resources:

1. Seed input:
   - Context: plot summary descriptions scraped from Wikipedia
   - Download: [jrobischon](https://www.kaggle.com/jrobischon)'s [Wikipedia Movie Plots dataset](https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots) hosted on Kaggle
