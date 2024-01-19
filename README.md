# tAIylor's Version

This project involves analysis of a Taylor Swift corpus using structural topic modeling, Biber MDA and PCA, and sentiment analysis. After language analysis of Taylor Swift lyrics, a BERT model was fine-tuned to predict the album from 3 lines of lyrics. Next, a GPT-2 model was fine-tuned in attempt to create a "Taylor Swift AI"-- _tAIylor's version_. This AI generates song lyrics in Taylor Swift's style given a textual prompt. We generated an AI album then analyzed this album using the same language analysis techniques.

## Data
The data directory contains the data files used in the analysis, from [Kaggle](https://www.kaggle.com/datasets/thespacefreak/taylor-swift-song-lyrics-all-albums). It also containes the _tAIylor's version_ album.

The taylor_lyrics_df.Rmd file contains data preparation code for fine-tuning of LLMs.

## Model Notebooks
Two Jupyter notebooks are included in the model_notebooks directory. These contain the Python code used to fine-tune BERT for classification and GPT-2 for generation tasks. Google Colab was used to provide GPU computing.

## Structural Topic Modeling
The structural-topic-modeling.Rmd file contains the code for structural topic modeling on the Taylor Swift corpus. It outputs insights into the topics present in the lyrics.

## Sentiment Analysis
The sentiment_analysis.Rmd file focuses on sentiment analysis. It calculates mean sentiment scores for each album, providing an emotional perspective on Taylor Swift's discography as well as a time series analysis.

## Biber MDA
The biber_mda.Rmd file calculates similarity between albums based on Biber's MDA principles and uses PCA analysis.


