# Name Entity Recognition Hackathon from Super AI Engineer season 5

This is the code for the hackathon of super ai engineer season 5 in the problem of Name Entity Recognition from modified lst20 dataset with the a little help (actually its also everything) of LLM (Chatgpt)

Hi, This is Natchapol Lebkrut. Despite the fact that I submitted the result 33 mins late, I acheive the best as as 0.79084 which passes the baseline.

The approach that I use is converting the raw dataset into the form of sentence_id and tokens where it will be train grouped_by the sentence_id and trained in batch.


## The official leaderboard

<img width="834" alt="image" src="https://github.com/user-attachments/assets/5d649fc5-c30a-44ef-98a9-0954450666f9" />

## The score if I could submit it in time

<img width="812" alt="image" src="https://github.com/user-attachments/assets/ce77587d-e2e5-4d97-9f56-a4ed87ec55da" />

## Lesson learn from this hackathon

### Overall
1. Don't be too rush, carefully checking the flow of the data in the pipeline, checking the format of the submission file so that it will not be changed much during the prediction.
2. Sometimes, everything will not go in the way that you might think. Don't panic and log the outputs and errors to see what is the problem and identify how to fix it.

### Kaggle
1. Kaggle is your enemy when you are in hurry, the session will not continue after exceeding 9 hours.
2. The save and run all (commit) function is the most strongest function to store the output especially your model weight

### NLP
1. Get familiar with the most famous topics in AI now, the model need a lot more time to train than other field in AI.
2. Learn how to finetune the existing small language model using simpletransformer package
3. Learn how to do clause segmentation and based on the clause tag.

