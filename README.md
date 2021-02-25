# jobs_prediction_algorithm
## Task overview: 
The task is straightforward: assign the correct job category to a job description. This is thus a multi-class classification task with 28 classes to choose from.  

## Data origin:
The data has been retrieved from CommonCrawl. The latter has been famously used to train OpenAI's GPT-3 model.
We can download it : kaggle competitions download -c defi-ia-insa-toulouse
## Work:
For this task, after thorough literature review, I explored the use of state-of-the-art transformers such as BERT and XLNet. I achieved 79.7\% of accuracy, the baseline achieving 77\%. 
