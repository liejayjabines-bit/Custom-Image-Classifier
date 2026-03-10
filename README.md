# Custom-Image-Classifier
https://drive.google.com/drive/folders/19u3NhrxKh345FJ0kFQbw44qKxnEXNnLj?usp=drive_link

https://colab.research.google.com/drive/12aTar5LxH1coSIaLB-5bB36uYtUIOniT?usp=sharing


Guide Questions

Dataset Preparation:
1. Dataset Preparation

How did you organize your dataset in Google Drive?
I created separate folders for each plant class and placed the images inside their correct folder.

Why is folder structure important for TensorFlow image loading?
Because TensorFlow uses the folder names as labels to identify each class.

2. Model Training

What is the role of convolutional layers in image classification?
They detect patterns in images like edges, shapes, and textures.

Why do we split data into training and validation sets?
Training data teaches the model, while validation checks how well it performs.

3. Performance Analysis

What accuracy did your model achieve?
My model achieved about ___% accuracy.

How did the number of images affect the model’s performance?
More images helped improve the model’s accuracy.

4. Critical Thinking

What challenges did you encounter while using your own dataset?
It was hard to collect enough clear images and organize them properly.

How can data augmentation improve your model?
It creates more image variations, which helps the model learn better.

5. Application

Suggest a real-world application for your trained model.
It can be used to identify creeper plants automatically.

ACITVITY 3A:

Visualization & Overfitting

1. What signs indicated overfitting in your first model?
The training accuracy was high but the validation accuracy was low.

2. How did data augmentation affect validation accuracy?
It improved the validation accuracy and reduced overfitting.

Model Improvement

3. What is the purpose of dropout layers?
Dropout layers reduce overfitting by randomly turning off some neurons during training.

4. Why does data augmentation improve generalization?
It creates different versions of images so the model can learn more patterns.

Performance Comparison

5. Compare accuracy before and after improvements.
The accuracy increased after adding dropout and data augmentation.

6. Which technique contributed most to improvement?
Data augmentation contributed the most.

Deployment & Application

7. Why is saving the model important?
Saving the model allows it to be reused without retraining.

8. How can this model be deployed in a real-world system?
It can be integrated into a mobile or web app to classify images automatically.
