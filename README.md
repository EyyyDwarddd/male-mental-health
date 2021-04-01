# Topic Modeling via Latent Dirichlet Allocation with Male Mental Health Issues


 ## Contents:

- [Background](#Background)  
- [Problem Statement](#Problem-Statement)  
- [Data](#Data)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Latent Dirichlet Allocation](#Latent-Dirichlet-Allocation)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)
- [Notes](#Notes)
- [Footnotes](#Footnotes)
---

## Background:

Male Mental Health is a term that was coined as of recently, and has been picking up in popularity ever since. In short, mental health (specifically with men) is a state of well-being in which an individual realizes his abilities, can cope with the normal stresses of life, can work productivily and is able to make a contribution to his community.<sup>1</sup>  

It is mainly true in American society that there is a stigma between being a person who identifies themselves as male, and discussing issues about their mental health. But throughout the decades, we have seen the consequences of holding this belief where men are to "bottle up" their emotions and display a semblance of stoicism. This has lead to dire consequences on a man's mental health, such as thoughts of suicide, depression, feeling flat or having trouble with positive emotions, and abuse of alcohol and/or drugs.<sup>2</sup> 

But all is not lost for men. Social networking sites such as Reddit have developed internet communities (known as subreddits) that deal with male mental health. This, in my opinion, is a positive step towards the right direction, and that no man is too "manly" to discuss mental health. 

---

## Problem-Statement:

This executive summary will display my methodology and results of the topics that I interpreted from the the Latent Dirichlet Technique. I will hopefully also share these results to Talkspace, an online therapy company, to take advantage of the results from my project.

---

## Data:

The data that I gathered was comprised from four subreddits:

1. r/askmen
2. r/malementalhealth
3. r/bropill
4. 4/MensLib

The total number of posts I was able to collect was roughly north of 27,000 posts.

---

## Exploratory Data Analysis:

I explored the following within the corpus.

1. Most common words found within the Corpus
2. Sentiment Analysis and analyzed the most common words between two dataframes I created-- one where the posts ranked a high positivity score and the other where posts ranked a high negativity score. 
3. Bi-Gram/Tri-Gram Analysis

---

## Latent Dirichlet Allocation:

Discovered the following topics to be the main themes within the corpus:

|Number|Topic|
| --- | --- |
|Topic 1| Sexual Trauma|
|Topic 2| Gender Identity/Roles|
|Topic 3| Familial Issues|
|Topic 4| Dating Advice/Relationships|
|Topic 5| Body Issues/Positivity|

---

## Conclusions and Recommendations:

1. Hire talented behavioral therapists who specialize and have a deep understanding with the topics found
2. Provide training to already employed behavioral therapists who can assist with the aforementioned topics
3. Ensure male clients that we have staff that can help with any mental health issues - no matter how frivolous they may be

---

## Notes

As an aside, there are two notebooks for topic modeling-- one where the models were initially run, and the other where one can run all the cells and the output would be the same. I duplicated this notebook in order to reflect that the models did run accordingly, as well as to have the same output regardless of the amount of times one chooses to run the cells within the notebook. More about this rationale can be found within the notebooks. 

---

## Footnotes
[1] https://www.who.int/news-room/fact-sheets/detail/mental-health-strengthening-our-response<br/>
[2] https://www.nimh.nih.gov/health/topics/men-and-mental-health/index.shtml
