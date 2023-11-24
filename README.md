# Natural Language Processing (NLP) Analysis
<img width="282" alt="image" src="https://user-images.githubusercontent.com/69817896/224577138-f0009ee0-47f8-48b7-8194-465b1976616b.png"> 

### Introduction
This is my MSBA capstone project. The primary dataset includes textual data from 194 hours' convention speech from both Democratic and Republican parties from 2004 to 2020. Our data sources are rev.com 
      and C-SPAN.org. The textual data was transformed to a SQLite database with 3470 rows and 9 columns including `year`, `party`, `day`, `speaker`, `speaker count`, `time`, `text`, `text length`, and `the source of text`.
An extended dataset that we use for this project is 1038 presidential speeches from 1789 to 2021, from George Washington to Joe Biden, for permutation testing. These speeches were delivered by 45 U.S. Presidents, 445 of which were from 19 Republican Presidents and 513 of which were from 16 Democratic Presidents.

### The research approaches
We use two research approaches, topic modeling and permuation testing, in this project. The Python code for topic modeling was written in jupter notebook. The R code for permutation testing was written in Rmarkdown and knitted to html. 

#### Topic modeling
We use topic modeling to track the evolution of topics from 2004 to 2020.

#### Permutation testing
We use permutation testing to compare speech feature differences at the subtle linguistic granularity level. 
Research questions: 
- How does the first person pronoun usage vary by party? 
- How does the verb tense usage vary by party?

The null hypotheses: 
- Party is independent of the first person pronoun usage. 
- Party is independent of verb tense usage.  
      
Three *a* priori hypotheses:
- Republicans are more likely to use past tense than Democrats in political speech.
- Democrats are more likely to use future tense than Republicans in political speech.
- Republicans are more likely than Democrats to use “I” rather than “we” in political speech. 

### Results
Our topic modeling identifies topics that gain or lose favor over time and topics that consistently reflect core values of the two parties. Our permutation test analysis shows statistically significant differences in past tense usage between the two parties in two corpora and in first-person singular and plural pronoun usage in convention speeches. 

### Acknowledgment
Special thanks to my MSBA professor, Dr. John Chandler, for his support throughout this project. 
