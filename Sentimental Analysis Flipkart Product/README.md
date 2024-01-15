# Flipkart Reviews Analysis

## Introduction

This Python script is designed for scraping and analyzing product reviews from a Flipkart URL. It performs sentiment analysis on the reviews and visualizes the distribution of sentiments using a pie chart.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/h1manshuuu/personal_projects.git  
   cd personal_projects/Sentimental Analysis Flipkart Product

3. Install dependencies:
   ```bash
   pip install pandas requests beautifulsoup4 matplotlib

## Usage

1. Run the script:  
   ```bash
   python sentimental_analysis_Flipkart.py

2. Enter the Flipkart product URL when prompted.

3. The script will scrape reviews, analyze sentiments, and display a pie chart of sentiment distribution.

## File Descriptions

- sentimental_analysis_Flipkart.py : This is the main script responsible for scraping, sentiment analysis, and visualization.
- sentimental_analysis_Flipkart.ipynb : Jupyter Notebook version of the script, providing an interactive environment for code execution and analysis.
- positiveword.txt : A file containing a list of positive words used for sentiment analysis.
- negativeword.txt : A file containing a list of negative words used for sentiment analysis.

## Features

- Scraping : The script utilizes web scraping techniques to extract reviews from the specified Flipkart product URL.
- Sentiment Analysis : Positive and negative sentiment words are used to determine the sentiment of each review.
- Visualization : The distribution of sentiments is visualized using a pie chart for easy interpretation.

## Contributing

If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- The script uses Beautiful Soup for web scraping.
- Sentiment analysis is based on positive and negative word lists.
- Visualization is done using Matplotlib.

Feel free to reach out for any questions or suggestions!
