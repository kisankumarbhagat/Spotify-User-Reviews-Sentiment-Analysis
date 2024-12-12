# Spotify User Reviews Sentiment Analysis

This project performs sentiment analysis on user reviews from the Spotify app, classifying feedback as positive, negative, or neutral. By leveraging machine learning and natural language processing (NLP) techniques, it analyzes and provides insights into the overall sentiment of user feedback.

## Features

- **Data Collection**: Collects user reviews from the Spotify app.
- **Sentiment Classification**: Classifies reviews into positive, negative, or neutral categories.
- **Machine Learning Model**: Utilizes NLP techniques and machine learning models for sentiment analysis.
- **Data Visualization**: Visualizes sentiment distribution through charts for better insights.

## Dataset

The dataset used in this project contains Spotify user reviews for 2022. You can download the dataset from Kaggle:

- [Spotify App Reviews - 2022 Dataset](https://www.kaggle.com/datasets/mfaaris/spotify-app-reviews-2022?resource=download)

### Dataset Information:
- Contains user feedback/reviews on the Spotify app.
- Each review includes a text review and its corresponding rating.

## Requirements

- Python 3.10.16
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `nltk`
- Jupyter Notebook or Google Colab for execution

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/kisankumarbhagat/Spotify-User-Reviews-Sentiment-Analysis.git
    ```

2. Install the necessary libraries:

    ```bash
    pip install -r requirements.txt
    ```

3. Download the dataset from Kaggle:

    [Download Spotify App Reviews Dataset](https://www.kaggle.com/datasets/mfaaris/spotify-app-reviews-2022?resource=download)

4. Upload the dataset to your local directory or environment.

## Usage

1. Open the project in Jupyter Notebook or Google Colab.
2. Load the dataset containing Spotify user reviews.
3. Preprocess the data (cleaning and tokenization).
4. Train the machine learning model for sentiment analysis.
5. Evaluate the model and visualize the results.

## Project Structure

- `notebooks/`: Jupyter/Colab notebooks for code implementation.
- `data/`: Dataset containing Spotify user reviews.
- `requirements.txt`: Python dependencies for the project.
- `README.md`: Project documentation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Data used in this project is publicly available from Kaggle.
- Libraries: `pandas`, `scikit-learn`, `nltk`, and `matplotlib` were used for data analysis and visualization.
- Thanks to the open-source community for their invaluable resources.

