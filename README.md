# BASIC-ML-Project
🎬 Movie Interest Prediction Using Decision Tree

This basic ML project uses a Decision Tree Classifier to predict if users are interested in a movie based on interaction data. It's a beginner-friendly project to help you learn key concepts like data preprocessing, model training, and prediction.

🎯 Project Overview
Objective: Predict user interest in movies based on interactions (e.g., ratings).

📖Learning Goals:
🗂 Load and explore datasets.
✂ Preprocess data by separating inputs and targets.
🎯 Train a Decision Tree model.
🔮 Predict outcomes using the trained model.

📊 Dataset
►Movie Interests DS.csv contains:
►Feature 1: User interaction score.
►Feature 2: Binary movie attribute (e.g., genre).
►Interest: Target (1 = interested, 0 = not interested).

🧠 Model
The model is a Decision Tree Classifier trained on the input features to predict user interest.

🛠 Key Steps:
1. 📥 Load Dataset using pandas.
2. ✂ Preprocess: Drop "Interest" from input features.
3. 🎯 Train the Model on the features and target.
4. 🔮 Make Predictions on new data.

🔮 Example Prediction

➤Given input data [[9, 1], [33, 0]]:
➤First prediction: User with score 9 and movie feature 1.
➤Second prediction: User with score 33 and movie feature 0.

📝 How to Run

1. Install the required libraries:
➤pip install pandas scikit-learn
2. Ensure the dataset is in Downloads/ or update the path.
3. Run the script to load data, train the model, and make predictions.

🛠 Requirements

➤🐍 Python 3.x
➤🗃 pandas
➤🔍 scikit-learn

🎓 Educational Purpose
This project introduces core ML concepts in a simple, approachable way. It’s ideal for beginners wanting to explore data preprocessing and model training.

⚖ License
Open-source under the MIT License.
