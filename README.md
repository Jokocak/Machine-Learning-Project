# Machine Learning Project

This project aims to predict the sales needed for each location using historical Clover POS data, weather data, and event data. The application uses a Python/Flask backend for data processing and machine learning predictions, and a React frontend for visualization.

## Getting Started

### Prerequisites
- Python 3.8+
- Node.js & npm
- Git

### Setup
```bash
# Clone the repository
git clone https://github.com/Jokocak/Machine-Learning-Project.git
cd Machine-Learning-Project

# Backend setup
python -m venv venv
source venv/bin/activate  # venv\Scripts\activate on Windows
pip install -r requirements.txt
python backend/app.py

# Frontend setup
cd frontend
npm install
npm start
