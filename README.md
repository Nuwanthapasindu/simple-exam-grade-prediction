# Student Grade Predictor

This repository contains a machine learning model built to predict student grades from exam scores. It serves as a practical, hands-on introduction to classification problems for anyone new to machine learning and data science.

## 🚀 Features

* **Grade Prediction:** Input a numerical mark and get a predicted letter grade (e.g., A+, B, C-, etc.).

* **Simple Model:** Uses a straightforward classification model, making the code easy to follow and understand.

* **CSV Dataset:** Comes with a pre-generated dataset of almost 900 student records (`dataset.csv`) for training and testing.

## 🛠️ How It Works

The core of this project is a **Logistic Regression** model from the Scikit-learn library. The model is trained on the `dataset.csv` file, where the `mark` column serves as the input feature (X) and the `grade` column is the target variable (y). During training, the algorithm learns the statistical relationship between these variables. Once trained, it can predict the corresponding letter grade for any new mark it is given.

## 💻 Getting Started

This project was developed using a Google Colab notebook. No local installation is required.

1. **Open in Google Colab:**

   * Click the "Open in Colab" badge at the top of this repository.

   * Alternatively, go to [Google Colab](https://colab.research.google.com/) and upload the `.ipynb` file from this repository.

2. **Upload the Dataset:**

   * Make sure to upload the `dataset.csv` file to your Colab environment so the notebook can access it.

3. **Run the Cells:**

   * Execute the cells in the notebook sequentially to train the model and see the predictions.

## 📂 Dataset

The model is trained on the `dataset.csv` file, which contains two columns:

* `mark`: The numerical score of the student (0-100).

* `grade`: The corresponding letter grade based on the institution's grading scale.

## ✨ Technologies Used

* **Python**

* **Google Colab**

* **Pandas** - For loading and manipulating the dataset.

* **Scikit-learn** - For building and training the classification model.

* **NumPy** - For numerical operations.

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request. Some ideas for future work include:

* Experimenting with other classification models.

* Creating visualizations of the data.

* Building a simple web interface with Flask or Streamlit.
