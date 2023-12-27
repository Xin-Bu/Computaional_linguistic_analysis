# Political Speech Analysis with Natural Language Processing (NLP)

### Datasets
This is my Master of Science in Business Analytics (MSBA) capstone project in spring 2023. Minor modification has been made recently. The primary dataset includes large-scale textual data transcribed from 194 hours' Democratic and Republican convention speeches from 2004 to 2020. The textual data were transformed to a SQLite database with 3470 rows and 9 columns including `year`, `party`, `day`, `speaker`, `speaker count`, `time`, `text`, `text length`, and `the source of text`. The table below gave us an overview of descritpive statistics in convention speeches. 

| year | party | distinct speakers | distinct speeches | tokens | unique tokens |avg token length |lexical diversity |
| :---:  | :---: | :---: | :---: | :---: | :---: | :---: | :---: | 
| 2020 | Democratic | 334 | 1258| 42047 | 9416  | 6.02 | 0.22 |
| 2020 | Republican | 133 | 732 | 47228  | 10683| 6.28 | 0.23 |
| 2016 | Democratic | 200 | 221 | 61064 | 11758 | 6.15 | 0.19 |
| 2016 | Republican | 68  | 76  | 33613 | 8560  |  6.2 | 0.25 |
| 2012 | Democratic | 110 | 115 | 44434 | 9071  | 6.2  | 0.2  |
| 2012 | Republican | 82  | 91  | 34822 | 8501  | 6.2  | 0.24 |
| 2008 | Democratic | 110 | 113 | 43720 | 8868  | 6.16 | 0.2  |
| 2008 | Republican | 55  | 61  | 26019 | 7056  | 6.22 | 0.27 |
| 2004 | Democratic | 180 | 184 | 63505 | 11206 | 6.2  | 0.18 |
| 2004 | Republican | 61  | 68  | 23508 | 6842  | 6.28 | 0.29 |

An extended dataset that we used for this project was 1038 presidential speeches from 1789 to 2021, from George Washington to Joe Biden, for permutation testing. These speeches were delivered by 45 U.S. Presidents, 445 of which were from 19 Republican Presidents and 513 of which were from 16 Democratic Presidents. 

### Methods
We used two research approaches, topic modeling and permuation testing, in this project. The Python code for topic modeling was written in Jupyter Notebook. The R code for permutation testing was written in R Markdown and knitted to html. 
* Topic modeling: We used topic modeling to track the evolution of topics from 2004 to 2020.
* Permutation testing: We used permutation testing to compare speech features at the subtle linguistic granularity level. 
### Results
Our topic modeling identified topics that gained or lost favor over time and topics that consistently reflected core values of the two parties. Our permutation test analysis showed statistically significant differences in past tense usage between the two parties in two corpora and in first-person singular and plural pronoun usage in convention speeches. 
### Data sources
* [Covention speech 1](rev.com)  and [Covention speech 2](C-SPAN.org)
* [Presidential speech](https://millercenter.org/the-presidency/presidential-speeches) 
