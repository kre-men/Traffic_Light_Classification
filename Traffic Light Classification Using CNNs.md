Traffic Light Classification Using CNNs

Project Overview
This project demonstrates the use of a Convolutional Neural Network (CNN to classify traffic lights as either red or green.
The model was trained on an image dataset of traffic lights and uses data augmentation techniques to improve generalization. 
It achieves over 92.5% accuracy on the validation dataset.

The project includes:
- Data preprocessing and augmentation for training images.
- Building and training a CNN model using TensorFlow/Keras.
- Model optimization with regularization techniques such as Dropout and Early Stopping.
- Deployment-ready code to predict traffic light states from online image URLs.

Technologies Used
- Python: Programming language for model development and data handling.
- TensorFlow/Keras: Framework for building and training the CNN model.
- NumPy: For numerical computations.
- Pandas: For data analysis and preprocessing.
- Matplotlib: For visualizing training performance and results.
- ImageDataGenerator: For rescaling and augmenting images during preprocessing.
- Pillow (PIL: For image manipulation and loading external URLs.

Features
1. Data Augmentation:  
   - Rescaling pixel values.  
   - Random rotation, zoom, and horizontal flips to enhance model robustness.
   
2. CNN Architecture:  
   - Convolution Layers: Extract spatial features from images.  
   - Pooling Layers: Reduce dimensionality and prevent overfitting.  
   - Fully Connected Layers: Perform binary classification.  
   - Dropout Layers: Add regularization to prevent overfitting.

3. Training Enhancements:  
   - Adam Optimizer: Used for efficient training.  
   - EarlyStopping: Stops training when validation performance plateaus.  
   - ModelCheckpoint: Saves the best model based on validation accuracy.

4. Evaluation Metrics:  
   - Loss and accuracy visualizations for training and validation sets.  
   - Final model evaluation on unseen test data.

5. Prediction from URLs:  
   - The project includes functionality to classify traffic lights from image URLs, demonstrating real-world usability.

Project Results 
- Training Accuracy Over 92.5%  
- Validation Loss 0.1738  
- Key Takeaway Data augmentation and regularization significantly improved model performance.


Future Improvements
- Add multi-class classification for other traffic light states (e.g., yellow).  
- Optimize the model for mobile and edge devices.  
- Use transfer learning for faster training and better accuracy.
