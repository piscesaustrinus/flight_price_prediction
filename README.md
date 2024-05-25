
# Flight Price Prediction

## Overview
This project predicts flight prices to help travelers find the best time to buy tickets.

## Setup
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.

## Running the Application
1. Start the Flask API: `python app.py`.
2. Access the API at `http://localhost:5000/predict`.

## API
### Endpoint: `/predict`
- **Method:** POST
- **Input:**
  ```json
  {
    "Dep_Time": "2023-07-01T14:00",
    "Arrival_Time": "2023-07-01T16:00",
    "stops": 1,
    "airline": "IndiGo",
    "Source": "Delhi",
    "Destination": "Cochin"
  }
