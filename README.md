🐱🐶 Cats vs Dogs Classifier using SVM
A simple machine learning project using Support Vector Machine (SVM) to classify images of cats and dogs from the Kaggle Dogs vs Cats dataset.
📂 Dataset
Source: Kaggle - Dogs vs Cats
Files Used: train.zip (~25,000 labeled images)
Labels are inferred from filenames: dog.123.jpg, cat.456.jpg
Note: This project does not use the test1.zip file, which is unlabeled.
🚀 Features
Preprocesses images (resizes, grayscales, flattens)
Trains a linear SVM classifier
Splits dataset (80% train / 20% test)
Displays prediction results with matplotlib
Option to limit training set for speed
🛠️ Technologies Used
Python
OpenCV (cv2)
NumPy
scikit-learn
Matplotlib
Jupyter Notebook
