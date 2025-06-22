# MNIST--Classification
Not a project... but a study of MNIST dataset using python libraries.
This project demonstrates how to classify handwritten digits from the MNIST dataset using machine learning techniques. The MNIST dataset contains 70,000 grayscale images of handwritten digits (0–9), each of size 28x28 pixels.

📁 Project Structure
bash
Copy
Edit
mnist-digit-classifier/
│
├── mnist_classifier.ipynb      # Jupyter notebook with training and evaluation
├── mnist_model.pkl             # Saved model (optional)
├── requirements.txt            # Python dependencies
└── README.md                   # Project overview
📌 What I Learned
How to load and visualize the MNIST dataset

Preprocessing images for better model performance

Training a classification model using:

SGD Classifier / Logistic Regression / Neural Networks (choose what you used)

Evaluating model performance with accuracy, confusion matrix, etc.

(Optional) Saving and loading the trained model

📊 Results
Final accuracy: 97.64%

Model: SGDClassifier / LogisticRegression / MLPClassifier

Achieved good performance with basic preprocessing

📚 Dataset Info
Source: MNIST Database

60,000 training images, 10,000 testing images

🧠 Future Improvements
Implement CNN using TensorFlow/Keras

Improve accuracy with hyperparameter tuning

Build a web app to draw and classify digits live

💡 Credits
scikit-learn

MNIST Dataset
