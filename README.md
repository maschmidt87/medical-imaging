 Executive Summary
This project applies a Convolutional Neural Network (CNN) to classify chest X-ray 
images into three categories: Covid-19, Viral Pneumonia, and Normal (Healthy). 
The goal is to build an accurate diagnostic model using image recognition techniques 
on a small but labeled medical dataset of 251 X-rays.

Results: A model was trained and tested that delivered 99%+ accuracy on both the training 
and test set, with 91% on the validation set.

✅ Key Results:
Training Accuracy: 99.1%
Validation Accuracy: 91.3%
Test Accuracy: 100%
Test Loss: 0.0579
Confusion Matrix: All test samples were correctly classified (100% classification accuracy)
🧠 Model Details:
CNN with two convolutional layers and one dense layer of 200 neurons
Trained over 19 epochs on resized 64×64 color X-ray images
Used softmax activation for multi-class classification
⚠️ Limitations:
While model performance is exceptional on this dataset, the small sample size (251 images) 
limits generalizability. Additional data and external validation are recommended to assess 
robustness in real-world clinical scenarios.
