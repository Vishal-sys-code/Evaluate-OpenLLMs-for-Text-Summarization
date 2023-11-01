# Evaluate-OpenLLMs-for-Text-Summarization

## **INTRODUCTION**
This project aims to demonstrate text summarization using three OpenLLMs models (Facebook-BART, T5, DistilBERT), a variant of the BERT model, for generating concise and coherent summaries from longer textual content. Text summarization has applications in various fields, including news articles, research papers, and content curation.

## **DATASET**
We use the CNN/Daily Mail dataset for training, validation, and testing our text summarization models. This dataset consists of news articles paired with human-generated summaries, making it a suitable choice for this task.

Dataset Link: [CNN Daily Mail Dataset](https://www.kaggle.com/datasets/gowrishankarp/newspaper-text-summarization-cnn-dailymail)

## **Models**

I leverage the following models for text summarization:

* **Facebook's BART**: *A pre-trained model specifically designed for text generation and text summarization.*
* **T5 (Text-to-Text Transfer Transformer)**: *A versatile model that converts all NLP tasks into a text-to-text format, including text summarization.*
* **DistilBERT**: *A lightweight variant of BERT that offers efficient and effective text summarization capabilities.*

## **Getting Started (in LOCAL SYSTEM)**
To get started with this project, follow these steps:

* *Clone the repository to your local machine.*
* *Install the required dependencies using ```pip install -r requirements.txt```.*
* *Download and preprocess the CNN/Daily Mail dataset.*
* *Initialize the models for text summarization.*

## **Getting Started (in CLOUD BASED NOTEBOOK ENV)**
To get started with this project, follow these steps:

* **Kaggle Notebook Link**: [Evaluate-OpenLLMs-for-Text-Summarization](https://www.kaggle.com/code/tmleyncodes/evaluate-openllms-for-text-summarization?scriptVersionId=148825590)

* *See on the top right corner the ```Copy & Edit``` button is there click on it and enjoy the notebook*

* *You don't need to have to attach the Dataset it is previously being done.*


## **Evaluation**
We evaluate the text summarization models using the following metrics:

* **ROUGE Scores**: *Precision*, *Recall*, and *F1 Score* are computed for *ROUGE-1*, *ROUGE-2*, *ROUGE-L*, and *ROUGE-Lsum*.