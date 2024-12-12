# Lung-Cancer-Detection-


The lung cancer prediction model is built using a **Convolutional Neural Network (CNN)**, which is a deep learning architecture well-suited for image classification tasks. 
The model classifies lung cancer images into three categories: **lung_aca** (adenocarcinoma), **lung_n** (normal tissue), and **lung_scc** (squamous cell carcinoma).

- **Convolutional Layers**: Extracts important features from images, such as edges and textures.
- **Pooling Layers**: Reduces image dimensions while preserving key features.
- **Fully Connected Layers**: Connects the extracted features to make the final classification.
- **Softmax Activation**: Used in the output layer to predict the probability of each class.

The model was developed using **PyCharm** and trained with the **Adam optimizer** and **categorical cross-entropy** loss function. 
It achieves an accuracy of **94%** on the test set, demonstrating its ability to classify lung cancer images accurately.
The model's performance was validated using key metrics such as accuracy, precision, recall, and F1-score.
