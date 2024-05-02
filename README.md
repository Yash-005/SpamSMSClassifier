# SMS Spam Detection App

## Introduction
The SMS Spam Detection App is a machine learning-powered application designed to classify SMS messages as either spam or legitimate. Utilizing a Support Vector Machine (SVM) model trained on numerous examples, this app provides real-time predictions and is accessible through a user-friendly web interface built with Streamlit.

## Key Features
- **Real-Time Spam Detection**: Classify SMS messages as spam or legitimate.
- **Interactive User Interface**: Easy to use web interface for entering SMS text and receiving immediate predictions.
- **Accessible Online**: Hosted on Streamlit Cloud, allowing access from anywhere.

## Model and Accuracy

- **Model Used**: The core of the application is built around a Support Vector Machine (SVM) model.
- **Accuracy**: The SVM model has achieved an impressive accuracy of 96.7% on the test dataset.
- **Feature Extraction**: TF-IDF (Term Frequency-Inverse Document Frequency) is utilized for text feature extraction, which helps in converting text data into a format that is more suitable for the SVM to process.

## Setup Instructions

### Prerequisites
- Python 3.6 or higher
- pip (Python package installer)

### Installation
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/SMS_Classifier.git
   cd SMS_Classifier
   
2.**Download all the dependencies**
  ```bash
  pip install -r requirements.txt
```
## Live Application

Visit the deployed application at [SMS Spam Detection App](https://spamsmsclassifier-cs5y957kjj8yulqj6glabs.streamlit.app/).

## Contribution

We welcome contributions to enhance the capabilities and efficiency of PhishGuard. To contribute, please follow these steps:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request


### Additional Notes:
- Make sure to replace the placeholder GitHub repository URL `https://github.com/yourusername/SMS_Classifier.git` with the actual URL of your GitHub repository.
- If you have a LICENSE file in your repository, the link `[LICENSE](LICENSE)` will correctly link to it. If not, consider adding one or adjusting the README accordingly.

This README should be comprehensive enough for both users who wish to use the app and developers who might want to contribute to the project.

