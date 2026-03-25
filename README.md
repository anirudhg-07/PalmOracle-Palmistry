🖐️ AI-Based Palmistry Prediction System

📌 Overview

This project is a web-based application that simulates palmistry using basic AI techniques. Users can upload an image of their palm, and the system analyzes palm lines using computer vision to generate predictions about personality, career, and emotions.

⚠️ Note: This project does not perform real palmistry. It uses image processing and rule-based logic to simulate predictions for educational purposes.

⸻

🚀 Features
	•	📤 Upload palm image
	•	🖼️ Image preview (React frontend)
	•	🔍 Edge detection using OpenCV
	•	🧠 Rule-based prediction system
	•	❤️ Multi-section results (Love, Personality, Career)
	•	🎲 Randomized responses for dynamic output
	•	⚠️ Basic validation for incorrect inputs

⸻

🧱 Tech Stack

Frontend
	•	React.js
	•	HTML, CSS, JavaScript

Backend
	•	Python (Flask)

Libraries
	•	OpenCV
	•	NumPy
	•	Flask-CORS

⸻

⚙️ How It Works
	1.	User uploads a palm image via the frontend
	2.	The image is sent to the Flask backend
	3.	The backend processes the image:
	•	Converts to grayscale
	•	Applies Gaussian blur
	•	Detects edges using Canny algorithm
	4.	Extracted edge patterns are analyzed
	5.	Rule-based logic generates predictions
	6.	Results are sent back and displayed

⸻

🧪 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/your-username/palmistry-ai.git
cd palmistry-ai


⸻

2️⃣ Backend Setup (Flask)

cd backend
pip install -r requirements.txt
python app.py


⸻

3️⃣ Frontend Setup (React)

cd frontend
npm install
npm start


⸻

🌐 API Endpoint

POST /analyze

Request:
	•	Form-data with image file

Response:

{
  "prediction": {
    "personality": "You are calm and practical",
    "career": "You are suited for leadership roles",
    "love": "You value deep emotional connections"
  }
}


⸻

⚠️ Limitations
	•	Not a real palmistry system
	•	No deep learning or trained model
	•	Accuracy depends on image quality
	•	Cannot verify if the image is actually a palm

⸻

🚀 Future Improvements
	•	Real palm detection using deep learning
	•	Improved accuracy with trained datasets
	•	User authentication system
	•	Report generation (PDF)
	•	Mobile app version

⸻

📊 Project Structure

palmistry-ai/
│
├── frontend/        # React app
├── backend/         # Flask server
│   ├── app.py
│   └── requirements.txt
└── README.md


⸻

🎯 Learning Outcomes
	•	Understanding of computer vision basics
	•	Integration of frontend and backend
	•	Working with REST APIs
	•	Simulating AI behavior using rule-based systems

⸻

🎤 Viva Note

This project uses computer vision (OpenCV) for edge detection and applies rule-based logic to simulate palmistry predictions. It is not a trained AI model but demonstrates AI concepts effectively.

⸻

📜 License

This project is for educational purposes only.

⸻

🙌 Acknowledgements
	•	OpenCV Documentation
	•	Flask Documentation
	•	React Documentation
