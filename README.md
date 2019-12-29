## Dataset Outlook
The following dataset retrieved from petitions submitted to the Presidential Office of Korea from 2017 to 2018. Each row of the dataset represents a single petition, there are total 377,756 petitions. The dataset is composed of 8 columns; 2 being datetime, 3 being numeric and 3 being categorical. The response column is “answered”, which indicates whether each petition was answered by the Presidential Office or not in binary (yes or no) term. Only handful petitions are selected to be attended. The ground rule to be nominated for answer is garnering more than 200,000 votes. 

## Objective 
Title and Content columns describe petition, written in Korean. These are the columns that this NLP analysis set its objective on. In the following analysis, I will perform preprocessing techniques such as tokenization, word embedding and removal of stopwords so that the text content is ready to be served for prediction analysis using machine learning algorithms in future. Given that the dataset has a binary response column, it can be used to predict which form of petition is probable to be answered by the Presidential Office. 

## Workflow 
1.Locating and Understanding Data
2.Grouping sample data based on common theme and key words
3.Tokenization
-	Text Preprocessing
-	Word Tokenization
-	Sentence Tokenization
4.Word Embedding (Word2Vec)
-	Word Similarity 
5. Stopwords

