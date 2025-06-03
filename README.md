**Sentiment Analysis of Hotel Reviews**

This repository, **Vishnukummetha2932/Sentiment-Analysis-of-Hotel-Reviews**, contains a Jupyter Notebook (Hotel_Reviews.ipynb) that performs sentiment analysis on hotel reviews. The notebook utilizes numpy for basic array operations and pandas for data manipulation, with TextBlob for sentiment classification. A pie chart visualizes the sentiment distribution of the reviews.

**Table of Contents**

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Output](#output)
- [Dependencies](#dependencies)

**Project Overview**

This Jupyter Notebook provides a simple yet effective way to analyze the sentiment of hotel reviews. It demonstrates:

- Basic data loading and inspection using pandas.
- Application of TextBlob for sentiment polarity calculation.
- Classification of reviews into 'Positive', 'Negative', or 'Neutral' sentiment.
- Visualization of sentiment distribution using a pie chart.

**Features**

- **Data Loading**: Reads hotel review data from a CSV file.
- **Data Exploration**: Displays basic information about the dataset (head, tail, shape, dtypes, describe, null counts).
- **Sentiment Analysis**: Classifies text reviews into positive, negative, or neutral categories using TextBlob.
- **Sentiment Distribution**: Calculates and displays the count of each sentiment category.
- **Visualization**: Generates a pie chart to visually represent the sentiment distribution.

**Installation**

To run this notebook, you'll need to have Python installed, along with pip for package management.

1. **Clone the repository:**
2. git clone <https://github.com/Vishnukummetha2932/Sentiment-Analysis-of-Hotel-Reviews.git>
3. cd Sentiment-Analysis-of-Hotel-Reviews
4. **Install the required Python packages:**

Open your terminal or command prompt and navigate to the directory where you saved the notebook. Then, run the following commands:

pip install numpy

pip install pandas

pip install textblob

pip install matplotlib

**Usage**

1. **Place the data file:** Ensure you have a CSV file named Hotel_Reviews.csv in the same directory as the Hotel_Reviews.ipynb notebook. This file is crucial for the notebook to run correctly.
2. **Open the Jupyter Notebook:** Launch Jupyter Notebook (or JupyterLab) from your terminal:
3. jupyter notebook

Your web browser will open, displaying the Jupyter interface.

1. **Run the notebook:** Navigate to Hotel_Reviews.ipynb and open it. You can run each cell sequentially by clicking the "Run" button or by pressing Shift + Enter.

The notebook will:

- Install numpy and pandas (if not already satisfied).
- Load the Hotel_Reviews.csv dataset.
- Perform various data inspections.
- Apply the sentiment analysis function to the 'reviews.text' column.
- Print the sentiment counts.
- Display a pie chart showing the sentiment distribution.

**Data**

The notebook expects a CSV file named Hotel_Reviews.csv. This file should contain a column named reviews.text which holds the textual reviews to be analyzed for sentiment.

**Note:** The provided notebook assumes the presence of this specific CSV file. If your data is in a different format or has a different column name, you will need to modify the df = pd.read_csv('Hotel_Reviews.csv') and df\['Sentiment'\] = df\['reviews.text'\].apply(get_sentiment) lines accordingly.

**Output**

The notebook will output:

- The first and last few rows of the DataFrame (df.head(), df.tail()).
- The shape and data types of the DataFrame (df.shape, df.dtypes).
- Descriptive statistics of numerical columns (df.describe()).
- The count of null values per column (df.isnull().sum()).
- The mean of reviews.rating.
- A breakdown of 'Positive', 'Negative', and 'Neutral' sentiment counts.
- A pie chart visualizing the sentiment distribution.

**Dependencies**

- numpy
- pandas
- textblob
- matplotlib
