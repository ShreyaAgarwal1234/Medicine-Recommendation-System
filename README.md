# Medicine-Recommendation-System
This project uses AI to predict possible diseases based on user-input symptoms. It also recommends descriptions, precautions, medications, workouts, and diets based on the AI's prediction.

🚀 Features
Symptom Input:
Users can type or use speech recognition to input symptoms.

AI Disease Prediction:
The model predicts the most probable disease based on entered symptoms.

Recommendations:
After prediction, the app displays:

Disease Name

Description

Precautions

Medications

Workout Suggestions

Diet Recommendations

User-friendly UI:
Simple and responsive design for a smooth user experience.

🛠️ Tech Stack
Frontend: HTML, CSS (basic UI)

Backend: Flask (Python)

Machine Learning: Scikit-learn, Pandas, NumPy

Others: Speech Recognition API (for voice input)

📋 How to Run Locally
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/health-center-ai.git
cd health-center-ai
Install the required libraries:

bash
Copy
Edit
pip install -r requirements.txt
Run the Flask app:

bash
Copy
Edit
python app.py
Open your browser and navigate to:

cpp
Copy
Edit
http://127.0.0.1:5000/
📁 Project Structure
csharp
Copy
Edit
health-center-ai/
│
├── templates/
│   └── predict.html         # Frontend HTML file
│
├── static/
│   ├── css/                 # Stylesheets
│   └── js/                  # JavaScript files (if any)
│
├── model/
│   └── disease_prediction.pkl  # Trained ML model
│
├── app.py                   # Flask server
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
