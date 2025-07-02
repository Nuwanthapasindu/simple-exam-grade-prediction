# Student Grade Predictor

A simple Python project that predicts a student's final grade based on their exam marks. This project is a great starting point for beginners looking to understand the fundamentals of machine learning and data preprocessing.

## 🚀 Features

* **Grade Prediction:** Input a numerical mark and get a predicted letter grade (e.g., A+, B, C-, etc.).
* **Simple Model:** Uses a straightforward classification model, making the code easy to follow and understand.
* **CSV Dataset:** Comes with a pre-generated dataset of 1000 student records (`student_exam_marks.csv`) for training and testing.

## 🛠️ How It Works

The project uses a machine learning model (like a Decision Tree or K-Nearest Neighbors) trained on the provided dataset. The model learns the relationship between the marks and the corresponding grades. When you provide a new mark, it uses this learned pattern to predict the most likely grade.

## 💻 Getting Started

### Prerequisites

* Python 3.x
* pip (Python package installer)

### Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/student-grade-predictor.git](https://github.com/your-username/student-grade-predictor.git)
    cd student-grade-predictor
    ```

2.  **Install the required packages:**
    ```bash
    pip install pandas scikit-learn
    ```

3.  **Run the prediction script:**
    ```bash
    python predict_grade.py
    ```

## 📂 Dataset

The model is trained on the `student_exam_marks.csv` file, which contains two columns:
* `mark`: The numerical score of the student (0-100).
* `grade`: The corresponding letter grade based on the institution's grading scale.

## ✨ Technologies Used

* **Python**
* **Pandas** - For loading and manipulating the dataset.
* **Scikit-learn** - For building and training the classification model.
