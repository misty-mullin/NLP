# NLP 
This project utilized downloaded data in excel file format. In the beginning stages of the project, cleaning data was of the upmost importance. This removed special characters, numbers, abbreviations, and stop words. Tokenization and lemmatazing also occured at this stage. Then exploratory analysis was conducted that included creation of a word cloud, frequency histogram, LDA, tf-idf, and RAKE algorithm. 

After presenting the findings, the implementation of word embeddings was decided. The embedding models included the USE model, BERT Model, and BertSentence Transformer. Out of the box, the USE model performed the best, but had a lot of out of dictionary words. Due to parameter tuning, the BertSentenceTransformer was decided upon moving forward. Next, the implementation of keyBert was utilized to compare with the RAKE results. keyBert performed better, so this will be used for kewyword extraction. 

Upon presentation, administration decided they wanted to shift the result from key word extraciton to summarization. Currently, the implementation of Bert Extractive Summarizer (SBert), which takes thee embeddings and runs a clustering alogorithm, finding the sentences tatha re closest to the cluster's centroid. 

Next steps included an analysis of the SBert results and comparing against another model, which is yet to be decided. Finally, deployment via PowerBI and monitoring model performance. 

The end product is to use NLP methods to make predictions of future issues. Python libraries that were used included numpy, pandas, sci-kit learn, PyTorch (hugging face library), TensorFlow, matplotlib, gensim,pickle, pyLDAvis, nltk, amongst others. 
