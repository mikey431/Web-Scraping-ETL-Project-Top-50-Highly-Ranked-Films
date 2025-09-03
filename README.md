# Web-Scraping-ETL-Project-Top-50-Highly-Ranked-Films
This project demonstrates how to scrape film ranking data from a Wikipedia-style page, transform it into a structured DataFrame, and load it into both a CSV file and an SQLite database.

---
## Project Structure

- `script.py`          # Main Python script
- `top_50_films.csv`   # Output CSV file (generated)
- `Movies.db`          # SQLite database (generated)

## Features

**1. Web Scraping**
Extracts the first 50 films from the table in the source page.

**2. DataFrame Creation**
Stores data with columns:

- `Average Rank`
- `Film`
- `Year`

**3.Load to CSV**
- Saves results into `top_50_films.csv`.

**4.Load to SQLite Database**
- Saves the same data into an SQLite database (`Movies.db`) under the table `Top_50`.

## Project Structure

- Python 3.x

- `requests` – for fetching HTML content

- `BeautifulSoup` – for parsing the HTML page

- `pandas` – for data manipulation and CSV export

- `sqlite3` – for storing data into an SQLite database

## How to Run

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/top50_films_project.git
cd top50_films_project
```

### 2.Install dependencies:
```bash
pip install requests beautifulsoup4 pandas
```

### 3.Run the ETL script
```bash
python webscraping_movies_project.py
```
