# Advanced Data Analysis in Python — Part 1

## What is this project ?
This project is part of the Advanced Data Analysis course in Python. The goal is to get data from IMDB, clean it, and add missing information by scraping Wikipedia.

## Where does the data come from ?
- **IMDB** : gives us the main data : tconst (id's movies),movie titles, years, genres, runtime, Avgratings, Numvotes, nconst (id's actors) and actors
- **Wikipedia** : gives us extra info : language, country, plot, budget, and box office

## Project Files
| File | Description |
|------|-------------|
| `project part1 final (5) (1).ipynb` | The Jupyter Notebook with all the code |
| `df_final.csv` | CSV file with all the data including what we scraped from Wikipedia |
| `report` | Explains the choices we made during the project |
| `README.md` | This file explains what the project is about |

## Steps
1. **Import** — Download and load the IMDB datasets
2. **Clean & Filter** — Remove duplicates and filter the data
3. **Scraping Functions** — Create functions to search and get data from Wikipedia
4. **Run on Data** — Run the scraping on the full dataset and save the results

## Libraries Used
```python
import requests
from bs4 import BeautifulSoup
import json
import time
import pandas as pd
from pathlib import Path
import re
import io
from tqdm import tqdm
```

## How to Run
Open `project part1 final (5) (1).ipynb` and run all the cells from top to bottom in order.