# Question-Pair-Similarity

Millions of people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Canonical questions provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

## Objectives
1. The cost of a mis-classification can be very high.
2. You would want a probability of a pair of questions to be duplicates so that you can choose any threshold of choice.
3. No strict latency concerns.

## Dataset
Dataset Link: [Dataset](https://drive.google.com/drive/folders/1OUTvdopK9Ls72zoEZ-o7vuaRNTeMfcqI?usp=sharing) 
- Data will be in a file Train.csv
- Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate
- Size of Train.csv - 60MB
- Number of rows in Train.csv = 404,290 

## Approach
To identify duplicate questions, I had to tackle this natural language processing problem by applying advanced techniques to classify whether question pairs are duplicates or not. Doing so will make it easier to find high quality answers to questions resulting in an improved experience for writers, seekers, and readers.

In this notebook I have discussed various Data preprocessing steps with Advance NLP techniques to find if the questions are duplicate or not. Various Machine Learning Algorithms have been tested for best results.  
