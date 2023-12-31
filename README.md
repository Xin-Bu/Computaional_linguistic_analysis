# Political Speech Analysis with Natural Language Processing (NLP)

### Datasets
This is my Master of Science in Business Analytics (MSBA) capstone project in spring 2023. Minor modification has been made recently. The primary dataset includes large-scale textual data transcribed from 194 hours' Democratic National Convention (DNC) and Republican National Convention (RNC) speeches from 2004 to 2020. The text data were transformed to a SQLite database with 3470 rows and 9 columns including `year`, `party`, `day`, `speaker`, `speaker count`, `time`, `text`, `text length`, and `the source of text`. 

An extended dataset that we used for this project was 1038 presidential speeches from 1789 to 2021, from George Washington to Joe Biden, for permutation testing. These speeches were delivered by 45 U.S. Presidents, 445 of which were from 19 Republican Presidents and 513 of which were from 16 Democratic Presidents. 
### Methods
We used two research approaches, topic modeling and permuation tests, in this project. The Python code for topic modeling was written in Jupyter Notebook. The R code for permutation tests was written in R Markdown and knitted to html. 
* Topic modeling: to track the evolution of topics from 2004 to 2020.
* Permutation tests: to compare speech features at the subtle linguistic granularity level. 
### Results
Our topic modeling identified topics that gained or lost favor over time and topics that consistently reflected core values of the two parties. Our permutation test analysis showed statistically significant differences in past tense usage between the two parties in two corpora and in first-person singular and plural pronoun usage in convention speeches. 
### Selected visuals
#### Topic Modeling with Python
![image](https://github.com/Xin-Bu/Computaional_linguistic_analysis/assets/69817896/2129637a-49c8-495a-9ba9-2ff95ec52cbe)

![image](https://github.com/Xin-Bu/Computaional_linguistic_analysis/assets/69817896/3f9309d1-84a3-4d4c-be37-7eb4eaa28e60)

#### Permutation tests with R

![image](https://github.com/Xin-Bu/Computaional_linguistic_analysis/assets/69817896/ef43ec5e-cabd-456b-a315-7151a72f9386)  
![image](https://github.com/Xin-Bu/Computaional_linguistic_analysis/assets/69817896/6dbc619d-7a80-44c9-a369-9f27a79ca587)


### Data sources
* [Covention speech 1](rev.com)  and [Covention speech 2](C-SPAN.org)
* [Presidential speech](https://millercenter.org/the-presidency/presidential-speeches) 
