# Fake News Detection System

## 1. Introduction
The Fake News Detection System is a machine learning-based web application designed to classify news articles as either "Fake" or "Real". The project uses a dataset containing news headlines and the associated labels to train a model that can predict the legitimacy of news articles.

## 2. Objectives
- Develop a model to classify news articles as fake or real.
- Deploy the model using a web-based interface.
- Provide an easy-to-use platform for users to check the authenticity of news.

## 3. Methodology

### 3.1 Data Collection
- **Dataset**: The project uses a dataset named `fake_or_real_news.csv`, which contains news headlines along with labels (fake or real).

### 3.2 Data Preprocessing
- The data is preprocessed to remove any null values and perform text cleaning, including removing special characters, stopwords, and stemming.

### 3.3 Model Selection
- The project employs a machine learning pipeline, primarily using a Jupyter Notebook for model development.
- Various models like Logistic Regression, Naive Bayes, and Support Vector Machines (SVM) are tested.

### 3.4 Model Evaluation
- Models are evaluated using accuracy, precision, recall, and F1-score metrics.

### 3.5 Deployment
- The model is deployed using a Streamlit-based web application, allowing users to input news headlines and receive predictions on whether the news is fake or real.
- Docker is used for containerization.

## 4. Tools and Technologies
- **Programming Languages**: Python
- **Libraries**: Pandas, Scikit-learn, Streamlit, Docker
- **Tools**: Jupyter Notebook, Docker

## 5. Results
The model achieved satisfactory accuracy, making it effective in detecting fake news. The final deployed application provides users with a quick and reliable method to verify the authenticity of news articles.

## 6. Future Work
- Enhancing the model's accuracy by experimenting with different algorithms and techniques.
- Expanding the dataset to include more diverse news sources.
- Integrating the system with social media platforms for real-time fake news detection.

## 7. Conclusion
The Fake News Detection System demonstrates the potential of machine learning in combating misinformation. With further development, it could become a vital tool in the fight against fake news.

## 8. References
- Dataset: `fake_or_real_news.csv`
- Libraries: Scikit-learn, Pandas, Streamlit
- Tools: Jupyter Notebook, Docker
