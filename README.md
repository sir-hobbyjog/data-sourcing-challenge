# Movie Review Data Retrieval Project

## Overview
This Python project is designed to fetch movie reviews from the New York Times API and The Movie Database API. It specifically targets reviews with certain keywords in the headline and within a specified date range. The script manages API rate limits and paginates through results to compile a comprehensive list of reviews.

## Features
- **API Integration:** Seamlessly integrates with NYT and TMDB APIs.
- **Keyword Filtering:** Retrieves movie reviews based on specific keywords in headlines.
- **Date Range Selection:** Allows specifying a date range for the reviews to be fetched.
- **Rate Limit Management:** Includes a delay between API calls to adhere to rate limits.
- **Pagination Handling:** Efficiently navigates through multiple pages of API results.

## Requirements
- Python 3.x
- `requests` library for API calls
- `pandas` for data handling
- `python-dotenv` for managing environment variables
- An API key from both the New York Times and The Movie Database

## Installation
1. Clone the repository to your local machine.
2. Install the required Python packages:  
`pip install requests pandas python-dotenv`  
3. Set up a `.env` file with your `NYT_API_KEY` and `TMDB_API_KEY`.

## Usage
Run the script using Python:  
`python retrieve_movie_data.ipynb`

