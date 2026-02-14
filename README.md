🎓 Student Performance Prediction

This project implements and compares multiple machine learning and deep learning architectures to predict student performance levels (Low, Medium, or High) based on academic and behavioral features.

🚀Project Overview

The core of this project is a comparative analysis of three different algorithmic approaches:

1. Decision Tree: A baseline categorical model.

2. Support Vector Machine (SVM): A high-performance statistical model using an RBF kernel.

3. Hybrid CNN + SVM: A deep learning feature extractor (CNN) combined with an SVM classifier.

📊 Dataset Description

The model is trained on student_data.csv, which includes the following features:

1.Academic Scores: Math, Science, and English.

2.Behavioral Data: Attendance, Assignments Submitted, and Study Hours.

3.Demographics: Parent Education Level and Extra-Curricular involvement.

4.Target: Performance level (represented as 0, 1, or 2).

🛠️ Technology Stack

Language: Python

Libraries: * pandas & numpy (Data Processing)

scikit-learn (ML Models & Metrics)

tensorflow/keras (CNN Architecture)

📈 Results Summary

Based on the final execution, here is how the models performed:

| Model Name             | Accuracy | Precision | Recall | F1 Score |
| :--------------------- | :------- | :-------- | :----- | :------- |
| Decision Tree          | 0.7000   | 0.6985    | 0.7139 | 0.6995   |
| SVM (RBF)              | 0.9167   | 0.9183    | 0.9268 | 0.9194   |
| Hybrid CNN + SVM       | 0.5333   | 0.5428    | 0.5911 | 0.5148   |

Note: The standard SVM significantly outperformed the other models on this specific dataset, achieving over 91% accuracy.








