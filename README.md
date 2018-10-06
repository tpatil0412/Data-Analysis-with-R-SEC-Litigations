# Data Analysis with R SEC-Litigations
The motivation behind this project was to 
1)	Analyze the litigation releases and classify the litigations in one of the civil lawsuits category
2)	Perform monetary analysis of fraud and also check the severity of the penalty for the fraud
    For this I performed
    1)	Text Extraction from the web and to do this I used rvest library
    2)	Text cleaning and I have used grep library to clean the text. I took care of the stemming, removal of the stopwords, punctuation           marks, html tags and all the unwanted elements associated with the desired textual content
    3)	Mood scoring of the text, tried to find total number of positive and negative words in every textual content of the respective             litigation 
    4)	Topic analysis to find major topics in the civil lawsuits category and successfully classified the litigations in one of the               categories
    5)	Calculated total monetary fraud amount and total monetary penalty for every litigation
