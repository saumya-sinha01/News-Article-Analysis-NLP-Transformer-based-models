# News-article-analysation-using-NLP-Transformer-based-models
Analyzing and predicting text data in today's world is a crucial aspect of Artificial
Intelligence. Modern research has developed efficient and strong LLMs which can produce
impressive results for downstream tasks by fine-tuning them. This project provides a News
Analysis system which utilizes NLP and AI models to summarize, classify, search articles and
provide important named entities from news articles or any other text data.
The scope of this project is to fine tune the pre-trained models from Hugging Face
repository on the different NLP tasks such as summarization, classification, searching news
articles and performing NER. The dataset used for summarization : CNN_Dailymail( 1.29Gb ),
classification task dataset: AG News and BBC news( 30 MB ) and NER: NER_dataset.The
models used for fine tuning summarization task are Pegasus, T5 and Llama 2 and it was found
that Pegasus outperformed with ROUGE-1 value of 0.36. Bert, RoBerta and GPT-2 models are
used for classification. GPT-2 and Bert performed equally well with accuracy of 93%. The
Underlying ElasticSearch mechanism was proposed on Bert model outcomes. For NER task,
LLAMA -2 best performed with F1 score 0.79.
This project provides an in-depth analysis and comparison of multiple state-of-the-art and
powerful LLMs. Project deliverables include this final report, presentation, codes for model
fine-tuning, user-facing software application, and the fine-tuned models. The fine-tuned models
are also made available to the public on the Hugging Face and GitHub repository.
Users can interact with the application and get summaries, categories and important
entities from any text data. They can also search for news articles from a particular category.
Since we are surrounded by important text data everyday, this project is very helpful for
performing sentiment analysis, or analyzing legal documents that we use frequently but do not
have the time to read thoroughly, like job offer letters, leasing agreements or terms and
conditions. It can also be used to summarize research papers for scholarly works.
