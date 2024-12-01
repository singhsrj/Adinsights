# AdInsights AI 🎯

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://adinsights.streamlit.app/)

A machine learning web application that predicts customer purchase behavior using Decision Tree Classification.

## Overview
AdInsights AI is a practice project that demonstrates the implementation of machine learning for customer behavior prediction. Using features like age and salary, the application predicts whether a potential customer is likely to make a purchase.

## Features
- Real-time purchase prediction based on customer demographics
- Interactive web interface built with Streamlit
- Visual representation of model performance
- Feature distribution visualization
- Configurable model parameters display

## Tech Stack
- Python
- Streamlit
- scikit-learn
- Plotly Express
- Pandas
- NumPy

## Installation

```bash
# Clone the repository
git clone https://github.com/[your-username]/adinsights-ai.git

# Navigate to project directory
cd adinsights-ai

# Install required packages
pip install -r requirements.txt

# Run the application
streamlit run app.py
```

## Usage
1. Run the Streamlit app:
```bash
streamlit run app.py
```
2. Enter customer details (age and salary)
3. Click "Generate Prediction" to see the results
4. Toggle "Show Technical Details" for additional model insights

## Model Details
- Algorithm: Decision Tree Classifier
- Features: Age, Estimated Salary
- Preprocessing: Standard Scaling
- Train-Test Split: 75-25
- Criterion: Log Loss

## Dataset
The model uses the 'Social_Network_Ads.csv' dataset containing:
- Age
- Estimated Salary
- Purchase Decision (Target Variable)

## Project Structure
```
adinsights-ai/
│
├── app.py              # Main Streamlit application
├── requirements.txt    # Project dependencies
├── README.md          # Project documentation
└── Social_Network_Ads.csv  # Dataset
```

## Contributing
This is a learning project and contributions are welcome! Here's how you can contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Requirements
Create a `requirements.txt` file with the following dependencies:
```
streamlit
numpy
pandas
scikit-learn
plotly
```

## Demo
Live demo available at: https://adinsights.streamlit.app/

## Contact


Project Link: 

---

⭐ Star this repo if you find it helpful!

Note: This is a practice project created for learning purposes. Feel free to use it as a reference for your own learning journey.
