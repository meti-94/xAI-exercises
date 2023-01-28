### **AI Explainability approaches**

In this part, I tried to illustrate the decisions made by the model using special tools for AI Explainability. Since I used to do error analysis with other approaches, I was not familiar enough with this task, so it made me struggle quite a bit :) . In this exercise, I first used a simple CNN network to classify the first label (humor) of the samples, then I showed the decision criteria of the model using the [SHAP](https://shap.readthedocs.io/ "SHAP") library. Next, I made a classifier using BERT, and after a training epoch, I showed its decision criteria on the text of each example. Unlike previous questions that used TensorFlow library in this exercise, I used PyTorch.

**In the SHAP.ipynb:**
1. Downloading the dataset 
2. Discarding unusable samples
3. Creating an image classifier
4. Running shap visualization on the classifier
5. Creating a text classifier
6. Running shap visualization on the text classifier