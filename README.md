# Stack Overflow Data - 2017 Survey

--------------------------------------
1. [Motivation](#motivation)
2. [Library](#library)
3. [Files](#files)
4. [Summary](#summary)
5. [Acknowledgment](#acknowledgment)
6. [Licensing](#licensing)

## Motivation <a name="motivation"></a>
IT develops more an more different programming languages for a lot of different use cases. Using my data analytics skills, I want to know more about that topic. There for, I will use the data of Stack Overflow's developer survey data from 2017, to answer some questions.

## Library: <a name="library"></a>

pandas - data wrangling
numpy - data wrangling
matplotlib - data visualization
sklearn - data analytics

## Files <a name="files"></a>

```
├── README.md						-- this readme file
└── Survey_Analytics.ipynb				-- jupter nootbook file for data wrangling and data visualization

```

## Summary <a name="summary"></a>
Q1. Having a lot of IT developed in the US, what are the most commonly known languages used by professionals?

It looks like JavaScript and SQL ist most commony known by US based professional developers. In addition, it looks like very basic languages close to HW programming like C & C++ are not that commonly knwon. Furthermore, R - an data analytics language, looks like it is really only known by experts.

Q2. Are there any correlations of the knowlede of programming languages, e.g. do most people, who knows C, know JavaScript as well?

The correlation matrix already gives the answer, if and yes where developers have clusters of skills. The basic results are:
- In general, there are no big correlations. This means, that there are no big cluster of "if a developfer knows language 1, then he knows language 2".
- There are only 2 meaningful correlations between
- C and C++, having around 50 % of the people knowing both of the languages and
- in terms of the often in web development used languages JavaScript, PHP and SQL. Anyway, they just overlap by about 30 %. 

Q3. How the correlation distribution of programming languages differ in Germany in contrast to the overall survey results?

One the first look, the correlation of developing languages know-how differs not much in Germany to the rest of the world. But, having a deeper, more specific look into the differences

# Acknowledgment <a name="acknowledgment"></a>
I would also like to thank StackOverflow to share the survey data set (https://www.kaggle.com/stackoverflow/so-survey-2017) and Udacity for their greate Data Scientist class.

## 5. Licensing <a name="licensing"></a>
Must give credit to Stack Overflow for the data.  You can find the Licensing for the data and other descriptive information at the following link available [here](https://insights.stackoverflow.com/survey).  Otherwise, feel free to use the code here as you would like! 

