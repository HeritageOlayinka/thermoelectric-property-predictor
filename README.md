# Thermoelectric Property Predictor

## Overview
This project is a machine learning–based tool for predicting thermoelectric material properties using chemical formula and temperature as input. It was developed as an independent project to support early-stage material evaluation and reduce the need for costly experimental testing.

The model was trained on a curated dataset with data cleaning, outlier handling, and hyperparameter tuning to improve prediction accuracy. A simple web interface was built in Python to make the tool accessible to users without programming experience.

---

## Key Features
- Predicts thermoelectric properties from material composition and temperature  
- Machine learning pipeline with data cleaning and outlier handling  
- Model tuning to improve predictive performance  
- Simple web interface for non-technical users  
- Useful for researchers and engineers in materials science

---

## Technologies Used
- Python  
- scikit-learn  
- pandas, numpy  
- Flask / Streamlit (update if needed)

---

## Project Structure
├── model/ # Trained model files
├── app.py # Web application
├── requirements.txt # Dependencies
└── README.md


## Setup Instructions
````
1. Clone the repository:
```bash
git clone https://github.com/your-username/thermoelectric-property-predictor.git
cd thermoelectric-property-predictor
````

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python app.py
```

4. Open the web interface in your browser:
```text
http://localhost:5000
```

## Use Case
This tool helps materials scientists and engineers estimate thermoelectric performance before laboratory synthesis and testing, enabling faster and more cost-effective material screening.

## Notes
This project was developed as an independent machine learning project (2025).

```
```
