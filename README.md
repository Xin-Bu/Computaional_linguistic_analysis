# Politica Speech Analysis with Natural Language Processing (NLP)

### Introduction
This is my MSBA capstone project that I made in spring 2023. Minor modification has been made recently. The primary dataset includes textual data from 194 hours' convention speeches from both Democratic and Republican parties from 2004 to 2020. The textual data was transformed to a SQLite database with 3470 rows and 9 columns including `year`, `party`, `day`, `speaker`, `speaker count`, `time`, `text`, `text length`, and `the source of text`.

An extended dataset that we used for this project was 1038 presidential speeches from 1789 to 2021, from George Washington to Joe Biden, for permutation testing. These speeches were delivered by 45 U.S. Presidents, 445 of which were from 19 Republican Presidents and 513 of which were from 16 Democratic Presidents.
### Methods
We used two research approaches, topic modeling and permuation testing, in this project. The Python code for topic modeling was written in Jupyter Notebook. The R code for permutation testing was written in R Markdown and knitted to html. 
* Topic modeling: We used topic modeling to track the evolution of topics from 2004 to 2020.
* Permutation testing: We used permutation testing to compare speech feature differences at the subtle linguistic granularity level. 
### Results
Our topic modeling identified topics that gained or lost favor over time and topics that consistently reflected core values of the two parties. Our permutation test analysis showed statistically significant differences in past tense usage between the two parties in two corpora and in first-person singular and plural pronoun usage in convention speeches. 
### Dataset source
* Covention speeches: rev.com and C-SPAN.org.
* Presidential speeches: https://millercenter.org/the-presidency/presidential-speeches. 
### Acknowledgment
Special thanks to my MSBA professor, Dr. John Chandler, for his support throughout this project. 
