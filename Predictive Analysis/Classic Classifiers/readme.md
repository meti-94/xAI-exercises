### **SVM and XGBoost**
In this part, the image-text multimodal model is used as an embedding. First, the model is trained using the training set. Then the part related to the model classifier is cut. After that, the samples are once again fed to the trained model to create a 2560-dimensional vector for each image and text (rows of data). In the last step, SVM and gradient classifiers are used to classify vectors with humor labels.

**In the XGboost-SVM.ipynb:**
1. Downloading the dataset 
2. Discarding unusable samples
3. Creating a multimodal model
4. Training the model
5. Cutting the classifier's tails from the model
6. Embedding each row of data
7. Performing classification on new vectors 
