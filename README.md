# Intel Products Sentiment Analysis from Online Reviews

This repository is part of the Intel Unnati Industrial Training Program 2024. It aims to analyze sentiments from online reviews of Intel products using various natural language processing techniques.

## Table of Contents
- [Introduction](#introduction)
- [Workflow](#workflow)
- [Wordcloud](#wordcloud)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project involves the extraction, cleaning, and analysis of online reviews for Intel products. We utilize sentiment analysis tools such as VADER and RoBERTa to classify the sentiments of these reviews into positive, negative, or neutral categories.

## Workflow
The overall workflow of the project is as follows:

1. **Data Collection:** Scraping Amazon product reviews for Intel processors.
2. **Data Preprocessing:** Cleaning and preparing the data for analysis.
3. **Feature Engineering:** Creating features such as review length and sentiment scores.
4. **Sentiment Analysis:** Using VADER and RoBERTa for sentiment classification.
5. **Visualization:** Generating visualizations such as word clouds and performance comparisons.

![Workflow](https://github.com/Moses-Mk/Intel-Products-Sentiment-Analysis-from-Online-Reviews/blob/main/images/Workflow.png)

## Wordcloud
Word clouds are generated to visualize the most common words used in positive, neutral, and negative reviews.

### Positive Reviews
![Positive Wordcloud](https://github.com/Moses-Mk/Intel-Products-Sentiment-Analysis-from-Online-Reviews/blob/main/images/Positive%20Reviews.png)

### Neutral Reviews
![Neutral Wordcloud](https://github.com/Moses-Mk/Intel-Products-Sentiment-Analysis-from-Online-Reviews/blob/main/images/Neutral%20Reviews.png)

### Negative Reviews
![Negative Wordcloud](https://github.com/Moses-Mk/Intel-Products-Sentiment-Analysis-from-Online-Reviews/blob/main/images/Negative%20Reviews.png)


## Results
The results section includes a comparison of the performance of different sentiment analysis models. We evaluate metrics such as accuracy, precision, recall, and F1-score.

![Results](https://github.com/Moses-Mk/Intel-Products-Sentiment-Analysis-from-Online-Reviews/blob/main/images/Training%20Results.png)

## Installation
To run this project locally, please follow these steps:

1. Clone the repository:
    ```bash
    git clone https:// https://github.com/Moses-Mk/Intel-Products-Sentiment-Analysis-from-Online-Reviews.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Intel-Products-Sentiment-Analysis-from-Online-Reviews
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To perform sentiment analysis on the dataset, run the following command:
```bash
python main.py
```
Make sure to update the configuration file (`config.json`) with the appropriate paths and settings.

## Contributing
Contributions are welcome! Please fork the repository and submit pull requests for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
