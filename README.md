# Student-Productivity-Predictor

This project is a fundamental Artificial Intelligence and Machine Learning application that predicts a student’s productivity score and burnout level based on daily habits like study time, sleep, screen usage, mood, and physical activity.

It demonstrates how basic ML models can be used to solve real-life student problems in a simple and interactive way. The project was developed using Google Colab and includes an interactive UI for real-time predictions.

Features

Predicts Productivity Score (0–100)

Classifies Burnout Level (Low / Medium / High)

Interactive UI using sliders and buttons

Provides personalized suggestions

Combines both Regression + Classification models


Tech Stack

1. Python
2. Pandas
3. Scikit-learn
4. Google Colab
5. ipywidgets



📂 Dataset

The dataset is manually created for demonstration purposes and includes:

Study Hours
Sleep Hours
Screen Time
Mood (1–5 scale)
Physical Activity (Yes/No)


Outputs:

Productivity Score
Burnout Level


Machine Learning Models

1. Linear Regression
Used for predicting productivity score (continuous value)

2. Logistic Regression
Used for classifying burnout levels (categorical output)



 How It Works

1. Dataset is created and stored using Pandas
2. Features and outputs are separated
3. Data is split into training and testing sets
4. Models are trained using Scikit-learn
5. User inputs are taken via interactive widgets
6. Predictions are displayed instantly



User Interface

The project uses ipywidgets to create an interactive interface:
Sliders for study hours, sleep, screen time
Mood selection (1–5)
Activity toggle (Yes/No)
Predict button for instant results


 Output Example

Productivity Score: 82.5 / 100
Burnout Risk: Medium
Suggestion: Balance study and rest properly.

Objective

The goal of this project is to:
Demonstrate basic ML concepts
Apply AI to real-life student scenarios
Build an interactive and beginner-friendly system


Future Improvements

1. Use a real-world dataset
2. Add more features (stress, diet, social life)
3. Implement advanced ML models
4. Deploy as a web/app-based system



Conclusion

This project is a beginner-level AI/ML system (similar to foundational student projects like Vidyarthi-type models) that combines simplicity with practical application. It shows how machine learning can be used to improve productivity and manage burnout effectively.
