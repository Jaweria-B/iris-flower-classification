# Iris Flower Prediction App

This is a simple web application built with Streamlit that predicts the type of Iris flower based on user input parameters. It utilizes a Random Forest Classifier model trained on the famous Iris dataset.

## About the Iris Dataset

The Iris dataset is a classic dataset in machine learning and statistics. It contains information about the sepal and petal lengths and widths of three species of Iris flowers: Iris setosa, Iris versicolor, and Iris virginica. The goal is to predict the species of an Iris flower based on these measurements.

## Model

The application uses a Random Forest Classifier from scikit-learn to predict the type of Iris flower.

## How to Use

1. Clone the repository:

```
git clone https://github.com/Jaweria-B/iris-flower-classification
cd iris-flower-classification
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

3. Run the Streamlit app:

```
streamlit run app.py
```

4. The app will open in your default web browser. Adjust the sliders for sepal length, sepal width, petal length, and petal width to input your parameters. The predicted type of Iris flower and the prediction probabilities will be displayed.

## Demo
[Live Demo](https://iris-flower-classification-jb.streamlit.app)

## Requirements

- Python 3.x
- Streamlit
- Pandas
- Scikit-learn

## Files in the Repository

- `app.py`: The Streamlit web application script.
- `README.md`: This README file providing information about the app.
- `requirements.txt`: A list of Python dependencies required to run the app.

## Acknowledgements

- This application was created for educational purposes.
- The Iris dataset is sourced from the UCI Machine Learning Repository.
- The app design and development were inspired by Streamlit's documentation and examples.
