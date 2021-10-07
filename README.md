# NLP_Project_Topic_modeling
Project on Comparison of topic modeling techniques for NLP course.

Modules:
data_process.py - data preprocessing for topic modeling:
	 - Converting texts to lowercase
	 - Removing of stop words
	 - Removing of special characters
	 - Lemmatization
	 - Tokenization 

lda_topic_modeling.py - LDA modeling and model assessment, including the folowing functions:
	 - Creation of dictionary and corpus for LDA model
	 - Creation of the LDA model
	 - Performance measure calculation
	 - Topics representation with the top n words
	 - Topics vizualization as a wordcloud
	 - Search for the LDA model with the higest value of performance measure based on list of possible numbers of topics
	 

topic_modeling.ipynb - project on topic modeling:
	- LDA topic modeling and hyperparametes tuning
	- BERTopic modeling ("distilbert-base-nli-mean-tokens", "all-MiniLM-L6-v2" embeddings):
		-creation and vizualization of BERTopic model
		-dimentionality reduction with UMAP
		-clustering with HDBSCAN
		-model performance assessment
		-topic representation
	- Top2Vec modeling:
		-creation  of Top2Vec model
		-dimentionality reduction with UMAP
		-clustering with HDBSCAN
		-model performance assessment
		-topic representation
	- Comparison of topic models based on  performance measure
	