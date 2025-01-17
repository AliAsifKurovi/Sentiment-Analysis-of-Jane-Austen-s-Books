# Sentiment Analysis of Jane Austen's Books

## Overview
This project focuses on performing sentiment analysis on Jane Austen's novels using the R programming language. By leveraging the tidytext package and the Bing sentiment lexicon, we analyze the sentiment of the text, visualize it through various plots, and create word clouds to depict the most frequent positive and negative words.
The book Emma was chosen for deeper sentiment analysis and visualization.

## Features
1. Text Wrangling: Tokenized text data from Jane Austen's novels into tidy format for analysis.
2. Sentiment Analysis: Utilized the Bing lexicon to classify words into positive and negative sentiments.
3. Visualization:
    - Sentiment trajectory over the text chunks.
    - Top 10 positive and negative words displayed as a bar chart.
    - Word clouds for positive and negative words.

## Dataset
We used the janeaustenr R package, which provides Jane Austen's complete works in plain text format, including the following books:
- Sense and Sensibility
- Pride and Prejudice
- Mansfield Park
- Emma
- Northanger Abbey
- Persuasion

## Installation and Requirements
### Prerequisites
Make sure you have R installed on your system. You can download R from The Comprehensive R Archive Network (CRAN).

### Required R Libraries
The following R libraries are required to run the project:
- janeaustenr
- dplyr
- tidytext
- stringr
- tidyr
- ggplot2
- wordcloud

Install them with the following command in R:
```
install.packages(c("janeaustenr", "dplyr", "tidytext", "stringr", "tidyr", "ggplot2", "wordcloud"))
```

## How to Run the Project
1. Clone the repository:

```
git clone https://github.com/AliAsifKurovi/sentiment-analysis-jane-austen.git
cd sentiment-analysis-jane-austen
```

2. Open the sentiment_analysis.R file in your R IDE or editor of choice.

3. Run the script to perform sentiment analysis and generate the following outputs:
    - Line plot of sentiment trajectory.
    - Bar chart of the top positive and negative words.
    - Word clouds of positive and negative words.

## Code Structure
* `sentiment_analysis_using_R.R`: The main R script that performs all the steps, from text wrangling to visualization.
* `README.md`: Documentation file for the project.

## Outputs
### Sentiment Bar Chart
The sentiment bar chart shows how the sentiment changes over the text chunks (80 lines each) in the book "Sense and Sensibility".

### Top Positive and Negative Words
A bar chart visualizes the top 20 positive and negative words from Sense and Sensibility, based on their frequency.

### Word Clouds
Two word clouds display the most frequent positive and negative words, emphasizing their relative importance.

## Example Visualizations
#### Sentiment Trajectory
![Sentiment Trajectory](https://github.com/AliAsifKurovi/Sentiment-Analysis-of-Jane-Austen-s-Books/blob/main/Output%202.png)
#### Top Positive and Negative Words
![Positive and Nagative Words](https://github.com/AliAsifKurovi/Sentiment-Analysis-of-Jane-Austen-s-Books/blob/main/Output%201.png)
#### Positive and Negative Word Clouds
![Word Cloud Positive](https://github.com/AliAsifKurovi/Sentiment-Analysis-of-Jane-Austen-s-Books/blob/main/Output%204.png)
![Word Cloud Negative](https://github.com/AliAsifKurovi/Sentiment-Analysis-of-Jane-Austen-s-Books/blob/main/Output%203.png)

## Contributing
Contributions are welcome! Please open an issue or submit a pull request if you want to add features or improve the project.

## Acknowledgments
- The `janeaustenr` package for providing Jane Austen’s novels.
- The `tidytext` package for its powerful tools for text mining in R.
- The `Bing lexicon` for sentiment classification.

## Contact
- **Name**: Mohammad Ali Asif
- **GitHub**: [AliAsifKurovi](https://github.com/AliAsifKurovi)  
- **Email**: aliasif.kurovi@gmail.com
