<img src="Banner.png" alt="Banner" width="1000" height="400"/>

This project showcase the different techniques using NLP where the movie reviews is categorize sentiments as positive, negative, or neutral.

## 🔔 Details

The datasets are the movies that integrate the Avengers saga. 

### 💻 Data Processing 

This project uses Python and libraries such as `nltk`, `sklearn`, and `NRCLex` to analyze the sentiments expressed in movie reviews. Text cleaning techniques, emotion classification, and data visualization are applied to gain valuable insights into user opinions.

## 📊 Analysis

### Data Acquisition

Data is obtained from:

[IMDB - Avengers(2012)](https://www.imdb.com/title/tt0848228/reviews/?ref_=tt_ql_2)

[IMDB - Avengers: Age of Ultron (2015)](https://www.imdb.com/title/tt2395427/reviews/?ref_=tt_ql_2)

[IMDB - Avengers: Infinity War (2018)](https://www.imdb.com/title/tt4154756/reviews/?ref_=tt_ql_2)

[IMDB - Avengers: Endgame (2019)](https://www.imdb.com/title/tt4154796/reviews/?ref_=tt_ql_2)



### Data Cleaning

Techniques are applied to clean the data for analysis:
- **Lowercasing**: Convert all text to lowercase to ensure uniformity.
- **HTML Unescaping**: Remove HTML entities.
- **Punctuation Removal**: Remove punctuation to simplify the text.
- **Removing NAs**: Handle missing values.

### 📝 Natural Language Processing (NLP)

Explore the NLP techniques used:
- **Text Cleaning**: Lowercasing, HTML unescaping, punctuation removal, and removing stopwords.
- **Sentiment Analysis**: Using the Vader Sentiment library and TextBlob.
- **Emotion Classification**: Using NRCLex to classify emotions in reviews.

### 📢 Model Evaluation

We evaluated the sentiment analysis models results from Vader and TextBlob. To predict we use Logistic regression. The evaluation metrics included accuracy, precision, recall, and F1-score.

## 📈 Results and Visualization

### Sentiment Distribution

- Positive, negative, and neutral sentiments are visualized using bar charts and word clouds for better understanding.

### Emotion Analysis

- The distribution of emotions (such as fear, anger, anticipation, etc.) is visualized using bar charts.

### Top Words

- Top 10 words for each sentiment category and each emotion category are identified and visualized.

### Word Clouds

- Word clouds are created for positive, negative, and neutral sentiments to highlight the most frequently used words.

## 📌 Analysis Notebooks and dataset 

For the notebooks and the csv files go to  `analysis` directory.

The order is:
1. [Webscraping)](https://github.com/danamejia1810/Sentiment-Analysis_Movie_Reviews/blob/main/Analysis/Notebooks/Webscraping.ipynb)
2. [Data Cleaning and EDA)](https://github.com/danamejia1810/Sentiment-Analysis_Movie_Reviews/blob/main/Analysis/Notebooks/Data%20Cleaning.ipynb)
3. [Sentimient Analysis)](https://github.com/danamejia1810/Sentiment-Analysis_Movie_Reviews/blob/main/Analysis/Notebooks/Sentiment%20Analysis.%20.ipynb)
4. [Logistic Regression)](https://github.com/danamejia1810/Sentiment-Analysis_Movie_Reviews/blob/main/Analysis/Notebooks/Logistic%20regression.ipynb)
5. [Keyword Analysis)](https://github.com/danamejia1810/Sentiment-Analysis_Movie_Reviews/blob/main/Analysis/Notebooks/Key%20words%20analysis.ipynb)
