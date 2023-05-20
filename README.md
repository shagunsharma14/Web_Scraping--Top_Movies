
```markdown
# Web Scraping - Top Movies

## 100 Movies that You Must Watch

# Objective

Scrape the top 100 movies of all time from a website. Generate a text file called `movies.txt` that lists the movie titles in ascending order (starting from 1). 
The result should look something like this:

```
1) The Godfather
2) The Empire Strikes Back
3) The Dark Knight
4) The Shawshank Redemption
... and so on
```
The central idea behind this project is to be able to use BeautifulSoup to obtain some data - like movie titles - from a website like Empire's (or from, say Timeout or Stacker that have curated similar lists). 

### ⚠️ Important: Use the Internet Archive's URL

Since websites change very frequently, **use this link** 
```
URL = "https://web.archive.org/web/20200518073855/https://www.empireonline.com/movies/features/best-movies-2/"
```
from the Internet Archive's Wayback machine. That way your work will match the solution video.

## Getting Started

To run the code, you need to have Python and the following libraries installed:

- requests
- BeautifulSoup

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required libraries:

```bash
pip install requests beautifulsoup4
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/BloodShoT14/Web_Scraping--Top_Movies
```

2. Navigate to the project directory:

```bash
cd your-repository
```

3. Run the Python script:

```bash
python main.py
```

4. After running the script, a file called `movies.txt` will be generated in the project directory. Open the file to see the list of top 100 movies.

## License

This project is licensed under the [MIT License](LICENSE).
```

Feel free to make any further modifications or additions as needed.