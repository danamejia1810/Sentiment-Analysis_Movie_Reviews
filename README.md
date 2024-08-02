<img src="Banner.png" alt="Banner" width="1000" height="400"/>

This project showcase the different techniques using NLP where the movie reviews is categorize sentiments as positive, negative, or neutral.

## 🔔 Details

The movie is from Marvel Studios: **Avengers: EndGame** which the premiere was from 22 de abril de 2019 April 22th (LA) and 2019 April 26th (United States). According to [Box Office Mojo](https://www.boxofficemojo.com/chart/ww_top_lifetime_gross/?ref_=bo_lnav_hm_shrt), this movie is the second most-watched movie in the world. with $2,799,439,100 dollars.

### 💻 Data Processing 

This project uses Python and libraries such as `nltk`, `sklearn`, and `NRCLex` to analyze the sentiments expressed in movie reviews. Text cleaning techniques, emotion classification, and data visualization are applied to gain valuable insights into user opinions.

## 📊 Analysis

### Data Acquisition

Data is obtained from the [IMDB - Avengers Reviews](https://www.imdb.com/title/tt4154796/reviews?ref_=tt_ql_2) page.

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

We evaluated the sentiment analysis models by comparing the predicted sentiments with the actual ratings given in the reviews. The evaluation metrics included accuracy, precision, recall, and F1-score.

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

Navigate to the `analysis` directory to explore Jupyter notebooks with detailed analysis.


