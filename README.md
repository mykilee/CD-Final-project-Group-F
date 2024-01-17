## Information instructions！

Due to the large size of our documents, we are unable to upload them all to GitHub. Therefore, we have linked the documents on OSF for your review: https://osf.io/x8mpc/      Thank you. 


# CD-Final-project-GroupF

When we talk about humanities, literature and literary theories are always the first to be mentioned as an important carrier of humanistic ideas. And in the current period of rapid development of the Internet, what topics are generally being studied in academic journals about literature? In order to explore this question, we decided to conduct a textual analysis of academic journals on literature for the whole year just past 2023. Due to the more stringent copyright restrictions on journals, we chose to download open-source journals based on the Scopus database. Also, since English is the most widely spoken language and has the largest number of journal articles written in English, we chose to limit the language used in the journals to English in order to find a more generalised answer.

Therefore, in this final project, we focus on journal articles within the scope of Literature and Literary theory from the Scopus database. There is our research question: Analyze the trends and preferences in topic selection of English literature journals on Scopus in the year 2023.

## 1.Introduction and Background

Our final group project looks into the preferences and trends in journal topic selection, specifically targeting English-language literary journal articles in the Literature category on Scopus for the year 2023. We downloaded all the open-source English-language literary journal articles from the official Scopus website and scraped the articles into txt documents. This document cleaning provides accurate and convenient text data for further subsequent data processing and analysis.
To help viewers better understand and learn the whole process of our project, our final group project is divided into three parts: 1:introduction and background；2:tutorials, 3:active learning exercises.

## 2.Research Question

The goal of our project is to clarify a research question:What are the preferences of diverse English-language literature journals in Scopus for the year 2023?

## 3.Dataset

We chose to download the open access English journals published in 2023 from the Scopus database: Scopus. https://www.scopus.com/home.uri 

## 4.Tutorials

### (1) Collecting Data

According to RQ, we chose to download all open access English journals published in 2023 from the Scopus database and classified under the Literature and literary theory category, a total of 1072 papers.It's worth noting that these papers are in pdf format now.

### (2) Scrape all the pdf journal articles into txt files
### (3) Managing data

After converting the open acess English papers downloaded from Scopus into txt format, we put the txt texts of articles with cited scores of 0-0.1, 01-0.3 and 0.3 or above all together to clean the text and achieve tokenization of the text.
During this part spaCy is used for tokenization, or the segmentation of strings into individual words and punctuation markers. Tokenization enables spaCy to parse the grammatical structures of a text and identify characteristics of each word-like part-of-speech.

### (4) Language processing
### (5) Analyze data 

## 5. Active Learning Exercises

Apart from the above exercises, we could also use these texts to practice Sentiment Analysis, so that find out what kind of emotional bias do literature and literary theory journals in English generally possess in 2023.


