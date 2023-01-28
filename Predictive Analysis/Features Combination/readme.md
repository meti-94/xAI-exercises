### **Use images, the extracted text, and any other feature you think could be useful for the classification task.**

Each of the memes in the dataset is embedded using a BERT model for texts and two pre-trained networks **ResNet50** and **VGG16** for images (with data augmentation). After performing these steps, separate classifiers are used for labeling. It's worth mentioning that hyper-parameter tuning can be done using third-party libraries but due to some limitations, I didn't use them. 

**In the Text-Image Classification.ipynb:**
1. Downloading the dataset 
2. Discarding unusable samples
3. Creating a multimodal model
4. Training the model
5. Performing simple hyper-parameter tuning (changing optimizer, lr, ....)