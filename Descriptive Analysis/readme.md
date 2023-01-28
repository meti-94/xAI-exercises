### **Descriptive Analysis on Fake news dataset**

In this exercise:
- A number of well-known steps in textual data preprocessing are given
- A number of data characteristics are generated/extracted and visualized
- The difference in the distribution of features in different classes is depicted.
- The data are mapped to the meaning space using trainable BERT embedding
- Visualization using T-SNA dimension reduction.

**Descriptive analysis results:** At first, I expected the distribution of some statistical characteristics to be different between fake and original news, such as the number of unique words, or the average length of the title, but the most unexpected thing for me was that the author has a very important in the time of classifying the news. For example, of about 600 writers who wrote more than 5 news, only 3 used a combination of two classes.


**In the EDA.ipynb:**
1. Downloading the dataset 
2. Discarding unusable samples (selecting only 1000 for the time-consuming steps)
3. Preprocessing
4. EDA (I planned to use zero-shot learning from hugging face to add emotion tags but it was really slow)
5. Plotting some features
6. Training of a sentence embedder using BERT
7. Visualization 