# Automatic-detection-of-COVID-19-from-chest-X-rays
This notebook presents an automated method for efficient and accurate Covid-19 diagnosis from chest X-rays.

### **STEPS**
- Image contrast enhancement using histogram equalization.
- Data augmentation, resizing, and rescaling images.
- Building and training a CNN on top of the pre-trained model Xception to reduce computation time (we freeze the early convolutional layers of the Xception network and only train the classification layers).
- Evaluation of the performance of the model on new unseen test data through roc score, accuracy, and log-loss score.
- Saving the model

### **PERFORMANCE**

The model achieved an accuracy of 98.49% and AUROC score of 98.76% for diagnosing the disease.

