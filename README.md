Setup Instructions :

First download the Notebook from the github link. Now login to Kaggle . Create notebook.
Import the downloaded notebook.Now in settings , Turn on Internet and In Accelerator select GPU T4 *2. 

#Install Dependencies
bash
pip install -r requirements.txt

#Set env variables
bash
export
WANDB_API_KEY=your_wandb_api_key
HF_TOKEN=your_huggingface_token

Results Table:

Epoch	Training Loss	Validation Loss	Accuracy	F1
1	2.644037	2.426180	0.580000	0.573711
2	2.133430	2.231644	0.603750	0.597966
3	1.671861	2.222764	0.609375	0.603855

Final Metrics:

| Metric    | Score               |
|-----------|---------------------|
| Accuracy  | 0.6094              |
| F1 Score  | 0.6039              |
| Eval Loss | 2.2228              |


Kaggle notebook link: https://www.kaggle.com/code/invincibleak/mlops-best
Hugging Face link: https://huggingface.co/Archie14/distilbert-goodreads-genres
W&B Dashboard : https://wandb.ai/g25ait2020-iit-jodhpur/mlops-assignment2

