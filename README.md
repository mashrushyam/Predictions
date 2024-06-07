# IPL Win Prediction

## Overview
This project aims to predict the outcome of IPL matches using various machine learning techniques. The prediction model utilizes factors such as team performance, player statistics, match conditions, and live match situations to determine the probability of a team winning.

## Technologies Used
- Python
- React
- Flask
- JavaScript

## Features

### Live Prediction
- Provides real-time predictions during ongoing matches based on current match situations.
- Calculates the percentage chance of winning for both the batting and bowling teams.

### Predict
- Predicts match outcomes based on historical data, player status, toss winner, toss decision, teams, and venue.

### Teams
- Displays status and squads of all IPL teams participating in the league.
- Provides insights into team performance and player statistics.

### Stats
- Presents various analyses on different parameters such as:
  - Batting and bowling averages
  - Win-loss ratios
  - Player performances
  - Venue-based statistics

## Setup Instructions
1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd ipl-win-predictor`
3. Locate the CSV file:
   - The required CSV file can be found in the project directory.
   - If it's not present, ensure it's either provided within the repository or can be downloaded separately.
   - Write the locations of csv file as per your location of file in app.py
4. Install dependencies:
   - For Python backend:
     ```
     cd ipl-win-predector\ipl-win-predector-backend
     pip install -r requirements.txt
     ```
   - For React frontend:
     ```
     cd ipl-win-predector
     npm install
     ```
5. Start the Flask server:
    cd ipl-win-predector\ipl-win-predector-backend
    python app.py

6. Start the React development server:
    cd ipl-win-predector
    npm start
7. Access the application at `http://localhost:3000`.

## Future Enhancements
- Include more sophisticated machine learning models for better prediction accuracy.
- Enhance user interface and experience.
- Integrate additional features such as player performance analysis, live match commentary, etc.

## Contributors
- [Shyam Mashru]
- [Piyush Makwana]

