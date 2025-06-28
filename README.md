# TrafficTelligence - Traffic Volume Estimation with Machine Learning

This project is a web-based Traffic Volume Estimation system built using Python, Flask, and Machine Learning. It predicts estimated traffic volume based on user inputs like weather, date, and time.

---

## Features

✅ Predict traffic volume using trained machine learning model  
✅ Web interface for user inputs  
✅ Displays estimated traffic volume instantly  
✅ Uses Flask for backend server  
✅ Supports integration with React.js frontend (optional)

---

## Project Structure

TrafficTelligence/
├── app.py # Flask application
├── model.pkl # Trained ML model (Linear Regression)
├── encoder.pkl # LabelEncoders for categorical features
├── traffic_volume.csv # Dataset
├── templates/
│ ├── index.html # Input form page
│ └── output.html # Results display page
└── static/ # Optional static files like CSS, images



---

## Installation & Setup

1. **Clone the repository:**

git clone <your-repo-url>
cd TrafficTelligence
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
If you don't have a requirements.txt, install basic dependencies:

bash
Copy
Edit
pip install flask pandas numpy scikit-learn
Run the Flask Application:

bash
Copy
Edit
python app.py
Access the Application:

Open your browser and go to:
http://127.0.0.1:5000

How to Use
Enter required inputs like:

Holiday type

Temperature

Rain/snow condition

Weather

Date and time details

Click Predict

The estimated traffic volume is displayed on the results page.

Dataset Information
File: traffic_volume.csv

Contains features like:

Holiday

Temperature

Rain/Snow

Weather Condition

Date & Time

Traffic Volume

Optional: React Frontend Integration
You can enhance the project with a React.js frontend for modern UI. Example code for React is available separately.

Requirements
Python 3.x

Flask

Pandas

NumPy

scikit-learn

Author
TrafficTelligence - Advanced Traffic Volume Estimation

