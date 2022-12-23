# YouTube, the news, politics: Can we see the divide?

## Data story

Please take a look at our [data story](https://marcplustwo.github.io/ada_political_youtube/).

All the analysis can be found in the [repository](https://github.com/epfl-ada/ada-2022-project-f71db320a845a41a5455c68ae6df5a15).

### Abstract

The divide between Republicans and Democrats has long been a source of political tension in the United States. But in the age of modern media, platforms like YouTube have the power to shape and influence public opinion. With its big and diverse audience, YouTube has become a popular outlet for political soapboxing.

We set out to examine the political landscape of YouTube using the [YouNiverse](https://github.com/epfl-dlab/YouNiverse) dataset, which includes metadata on **136,470** channels, **72,924,794** videos, and around **8.6 billion** comments. Our goal was to understand how users are distributed among <span style="color:red">right-</span> and <span style="color:Blue">left-winged</span> major news channels on YouTube, whether the platform creates filter bubbles for users with specific political biases [1] [2] [3], and how certain YouTube trends relate to real-world events.

### Research questions

* Can we find evidence for the filter bubble phenomenon on the political YouTube?
* Does the political YouTube mirror real life politics?

### Additional Datasets

- US news channels labelled with political bias from [AllSides](https://www.allsides.com/media-bias)
- A collection of Donald Trump's approval rating polls gathered by [FiveThirtyEight](https://projects.fivethirtyeight.com/polls/favorability/donald-trump/)

### Notebook Outline

1. Data Preparation
2. General Data Exploration
3. Network Analysis
4. Lexical categories
5. Title sentiment for different keywords in video
6. Filter bubbles (aggregate scores)
7. First order connections
8. LDA video titles
9. Sentiment analysis pipeline

#### External libraries
- scipy, sklearn
- huggingface transformers (https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment)
- spacy
- pyLDAvis
- gensim
- bokeh
- googleapi (youtube) 


### Team f71db320a845a41a5455c68ae6df5a15's member contribution

- Andrei:
    - Filter Bubbles, Comment Data
    - Data story
- Angelo
    - LDA
    - Data Story
- Juhani
    - Sentiment Pipeline
    - Time series
- Marc
    - Read in Data & Pre-processing & Exploration
    - Graph analysis and Visualization
    - Sentiment Analysis Video Titles

