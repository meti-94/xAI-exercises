### **Multi-label Classification: detect Humor, Sarcasm, Motivation, and Offense.**

**In the BiLSTM.ipynb:**
1. Downloading the data
2. Discarding unusable samples
3. Building a vectorizer using TensorFlow's built-in capabilities
4. Creating a simple model
	- 	16D trainable embedder layer
	- 	Most simplest BiLSTM possible
	- 	Classifiers
5. Training without any hyperparameter tuning or special work 

**In the BERT.ipynb:**
1. Downloading the dataset 
2. Discarding unusable samples
3. Using BERT tokenizer
4. Building a simple model
	- 	Bert as a sentence embedder
	- 	classifier layer
5. Simple model training