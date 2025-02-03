# Animetion

## Overview

Animetion is a Flask-based web application that allows users to search and stream anime episodes. The application integrates Google Drive API for video streaming and uses web scraping techniques to fetch episode details. Additionally, it automates ad-skipping using Selenium.

## Features

- **Flask Web Application**: A simple UI for searching and streaming anime episodes.
- **Google Drive API Integration**: Downloads and streams episodes from Google Drive.
- **Web Scraping**: Fetches anime episode details.
- **Automated Ad Skipping**: Uses Selenium to bypass ads during streaming.

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.8+
- Flask
- Selenium
- Google API Client
- ChromeDriver

### Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/animetion.git
   cd animetion
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Set up Google Drive API:
   - Enable Drive API from Google Cloud Console.
   - Download `credentials.json` and place it in the project root.
4. Set up Selenium:
   - Download ChromeDriver and update the `executable_path` in `scrap.py`.

## Usage

1. Run the Flask application:
   ```sh
   python app.py
   ```
2. Open `http://127.0.0.1:5000/` in your browser.
3. Enter the episode number and start streaming.

## Project Structure

```
Animetion/
│── static/
│── templates/
│── app.py
│── scrap.py
│── episode.py
│── automation.py
│── requirements.txt
│── credentials.json
│── README.md
```

## License

MIT License.

## Author

Your Name - Aditya Naidu

