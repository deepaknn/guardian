# Guardian - Fake News Detection System

## Overview
Guardian project is aimed at identifying and evaluating the credibility of news articles using machine learning and content matching techniques.

## Features
- **Fake News Detection:** Utilizes a machine learning model to predict the likelihood of a news article being fake.
- **Content Matching:** Compares the content of news articles with a database of known headlines to determine similarities and assess credibility.
- **Web Interface:** Provides a user-friendly web interface for users to input news articles and receive real-time credibility analysis.

## Installation
1. Clone the repository from [GitHub](https://github.com/deepaknn/guardian).
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Download the machine learning model and CSV file for content matching and place them in the appropriate directories.

## Usage
1. Run the Flask server by executing `python app.py`.
2. Access the web interface by navigating to `http://localhost:8080` in your web browser.
3. Enter the text of the news article you want to verify and submit the form.
4. View the result, which indicates whether the news is likely true, possibly true, or likely false.

## Dependencies
- Python 3.x
- Flask
- NLTK
- scikit-learn
- NewsAPI

## Directory Structure
- **Machine Learning Model:** Contains the trained model for predicting fake news (`final_model.sav`).
- **Content Matching:** Stores the CSV file (`newstitles.csv`) used for content matching.
- **Templates:** Includes HTML templates for the web interface.
- **Static:** Contains static files such as CSS and JavaScript for the web interface.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
