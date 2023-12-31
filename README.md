# Tamil-Sentiment-Analysis

# Primary Goal:  
The primary goal of the project is to predict whether the sentence (where the sentence is in the Tamil language) either is positive or negative Sentiment analysis has become important in social media research (Yang and Eisenstein, 2017). Until recently these applications were created for high-resourced languages which analyzed monolingual utterances. But social media in multilingual communities contains more code-mixed text. Code-mixing is common among speakers in a bilingual speech community. As English is seen as the language of prestige and education, the influence of lexicon, connectives, and phrases from the English language is common in spoken Tamil. 


# Dataset:
Tamil-English code-switched, sentiment-annotated corpus  comment posts from YouTube.The dataset contains all three types of code-mixed sentences - Inter-Sentential switch, Intra-Sentential switch, and Tag switching. Most comments were written in Roman script with either Tamil grammar with the English lexicon or English grammar with the Tamil lexicon. Some comments were written in Tamil script with English expressions in between.

You can download the dataset from the link below:
https://huggingface.co/datasets/tamilmixsentiment

# Output: 
'mokka ya tha iruku trailer antha level ku perusa onnum illa ', 1.0(negative) <br />
'thala epo vum masss tha ', 0.0(positive) <br />
'i am simbu fans like dhanush acting ', 0.0(positive) <br />
'thala vera level . . luv u so much ', 0.0(positive) <br />
'25 k dislikes ethuku da intha trailerku poi apdi ungalukku entha trailer tha pidikum',1(negative) <br />
"mokka ya tha iruku trailer antha level ku perusa onnum illa",1(negative) <br />
"Haiyooo.. hero roll ku indhe munji sariye waradhu.",1(negative) <br />
"Marana mass karthi broo ninga vera level", 0.0 (positive) <br />
Haiyooo.. hero roll ku indhe munji sariye waradhu., 1.0 (negative) <br />
Padu mokkai, ean thalayai kooni kondu nikkuthu thalai, 1.0 (negative) <br />
mokka ya tha iruku trailer antha level ku perusa onnum illa, 1.0 (negative) <br />
Vadachennai ku aprom oru come back pa, 0.0 (positive) <br />

# Usage
The model can be used to analyze statements in a variety of ways. For example, it can be used to:
Classify the youtube Tamil comment statements as positive, negatives
Analyze the sentiment of a document or collection of statements

This repository contains code for a deep-learning model that can be used to analyze statements. The model is trained on a dataset of statements that have been labeled with their sentiment (positive, negative, or neutral). The model can then be used to predict the sentiment of new statements.
