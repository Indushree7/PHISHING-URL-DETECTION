# PHISHING-URL-DETECTION

Phishing URL Detection with Machine Learning

This project implements a robust phishing URL detection system using a Decision Tree Classifier. It analyzes 30 different features of a URL to predict whether it is a legitimate or a phishing website with **91% accuracy**. The system is deployed as a web application using Flask, providing a simple and intuitive user interface for real-time URL classification.

 Key Features

  * High Accuracy: Achieves a 91% accuracy in detecting phishing URLs on the test dataset.
  * Comprehensive Feature Analysis: Utilizes a rich dataset with 30 distinct features for robust prediction.
  * Machine Learning Powered: Employs a Decision Tree Classifier from the scikit-learn library.
  * Web-Based Interface: A user-friendly web interface built with Flask, HTML, and CSS allows for easy interaction.
  * Real-time Predictions: Instantly classifies any given URL as either safe or a potential phishing threat.

Technology Stack

  * Backend: Python, Flask
  * Machine Learning: Scikit-learn, Pandas
  * Frontend: HTML, CSS

Machine Learning Model

The core of the detection system is a **Decision Tree Classifier** with the following configuration:

  * Criterion: Gini Impurity (`gini`)
  * Max Depth: 3
  * Dataset: The model is trained on the `PhishingData.csv` dataset, which contains 11,055 samples and 30 features.
  * Performance:The model achieves a **91% accuracyand a detailed classification report is generated to evaluate its performance on precision, recall, and f1-score for both classes (phishing and legitimate).

Project Structure

```
├── main.py               # Main Flask application and ML model logic
├── PhishingData.csv      # Dataset for training and testing
├── templates/
│   ├── index.html        # Home page with the URL input form
│   └── pass.html         # Page to display the prediction result
└── static/
    └── styles.css        # CSS for styling the web pages
```
