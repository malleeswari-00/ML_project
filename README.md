# ML Project

This is a small Machine Learning project built using Python and Flask.  
The project trains a machine learning model, saves it as a pickle file, and uses Flask to create a simple web interface for making predictions.

## Features
- Data preprocessing and model training
- Model saved using pickle
- Flask web application for predictions
- HTML template for user input and result display

## Project Structure
ML_project/
│── application.py 
│── models/ 
│ ├── ridge.pkl 
│ └── scaler.pkl 
│── notebook/ 
│ └── Model Training.ipynb 
│── templates/
│ └── index.html
│── requirements.txt 
│── README.md 


## Installation and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/malleeswari-00/ML_project.git
   cd ML_project
2. Create a virtual environment and activate it:
    python -m venv venv
    venv\Scripts\activate  

3. Install the dependencies:
    pip install -r requirements.txt

4. Run the application:
    python app.py

5. Open the browser and go to:
    http://127.0.0.1:5000