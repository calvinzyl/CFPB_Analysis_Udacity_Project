# Write a Data Science blog post - CFPB Text Analysis

## Data

This project utilizes the CFPB complaints data. The data is downloaded from the Consumer Financial Protection Bureau's Consumer Complaint Database, which, "is a collection of complaints about consumer financial products and services that we sent to companies for response". <br>
(https://cfpb.github.io/api/ccdb/index.html)

## Library

The project leverages several standard go-to libraries that most data scientists would use. The general-level data cleaning, preprocessing, and visualization use *pandas*, *os*, *numpy*, *re*, *seaborn*, *matplotlib*; libraries specifically for processing text include *textblob*, *nltk*, and *wordcloud*; *sklearn* is for ML modeling, and relevant modules include *model_selection*, *feature_extraction*, *preprocessing*, and *linear_model*.

## Project Roadmap

This project is part of the "Write A Data Science Blog Post" of the Udacity Data Scientist nano degrees program. In this project, I will be exploring three things around consumer complaints:
1) The financial products consumers complaint about most frequently
2) The vocabulary of the complaint narrative and how it evolved over time
3) What particular types of narrative determine a timely response from the company

## Blogpost

Refer to the Medium blogpost for the project findings: <br>
(https://medium.com/@calvin.yanlin.zhang/financial-project-consumer-complaint-analysis-udacity-ds-project-1-7e2c03dc7981)

## Acknowledgement

Thanks again to the Consumer Complaint Database which is readily available on the Consumer Financial Protection Bureau's official website. The detailed description and licensing could be found here: <br>
(https://cfpb.github.io/api/ccdb/index.html)
