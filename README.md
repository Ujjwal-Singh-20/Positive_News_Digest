# Positive News Digest

## Project Overview

Positive News Digest is a web application designed to curate and display news articles with positive sentiment. The aim is to provide users with a source of uplifting and encouraging news, making their browsing experience more pleasant. This project includes features such as bookmarking favorite articles and generating a word cloud from the collected news.

## Features

- **Positive News Curation**: Collect and display news articles with positive sentiment.
- **Sentiment Analysis**: Analyze the sentiment of news articles to filter out non-positive content.
- **Bookmarking**: Allow users to bookmark their favorite articles for later viewing.
- **Word Cloud Generation**: Visualize frequently used words in the positive news articles.

## Technologies Used

- **Python**: Main programming language for backend processing.
- **Flask**: Web framework for building the application.
- **BeautifulSoup**: For web scraping news articles.
- **TextBlob**: For sentiment analysis of news articles.
- **WordCloud**: For generating word cloud visualizations.
- **HTML/CSS**: For frontend design and presentation.

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/Ujjwal-Singh-20/Positive_News_Digest.git
    cd positive-news-digest
    ```

2. **Create and activate a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required dependencies**:
    ```sh
    pip install -r requirements.txt
    ```
    
## Running the Program

1. **Run the application**:
    ```sh
    python app_flask.py
    ```

2. **Initial Data Collection and Processing**:
    After running `app_flask.py`, the application will start by scraping news articles, performing sentiment analysis, and generating a word cloud. This process may take a few minutes. Please wait until the process completes before accessing the web application.

3. **Access the application**:
    Once the initial processing is complete, open your web browser and go to `http://127.0.0.1:5000/`.

## Usage

- **Home Page**: Displays a list of curated positive news articles and a word cloud visualization.
- **Bookmarking**: Click the bookmark icon next to an article to save it for later.
- **View Bookmarks**: Navigate to the bookmarks page to see all your saved articles.

## Project Structure

positive-news-digest/ <br/>
│ <br/>
├── data_collection.py # Script for scraping news articles <br/>
├── sentiment_analysis.py # Script for analyzing sentiment <br/>
├── visualization.py # Script for generating word cloud <br/>
├── app_flask.py # Main application script <br/>
├── templates/ <br/>
│ ├── index.html # Home page template  <br/>
│ └── bookmarks.html # Bookmarks page template <br/>


## Acknowledgments

This project was developed with the help of various resources and guidance. I would like to thank:

- **OpenAI's ChatGPT** for providing valuable insights and code snippets.
- [Flask Documentation](https://flask.palletsprojects.com/en/2.0.x/) for comprehensive guidance on building web applications.

All external code and resources were studied, adapted, and integrated to fit the specific needs of this project. This process has been a great learning experience and has significantly contributed to my understanding of web development and data science.



