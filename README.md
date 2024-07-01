# Retail Analytics Chatbot


A sophisticated retail analytics chatbot designed to follow analytics, provide strategic recommendations, and enhance decision-making for the retail industry.

## Features

- **Sales Data Analysis**: Provides insights on sales data, including total sales, monthly sales, and yearly trends.
- **Inventory Analysis**: Gives information about inventory levels and stock status.
- **Sales Forecasting**: Predicts future sales based on historical data using advanced forecasting models.
- **Natural Language Processing**: Utilizes NLP to understand and respond to user queries effectively.

## Tech Stack

- **Backend**: Flask, SQLAlchemy, spaCy, Pandas, Statsmodels
- **Frontend**: React, JavaScript, HTML, CSS
- **Database**: SQLite

## Setup Instructions

### Backend Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Raj24Patel/retail-analytics-chatbot.git
   cd retail-analytics-chatbot/backend

2. **Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. Install packages
   ```bash
   pip install -r requirements.txt

4. Generate data
   ```bash
   python generate_synthetic_data.py

5. run frontend
   ```bash
   python app.py

6. Navigate to frontent
   ```bash
   cd ../frontend

7. Install packages
    ```bash
    npm install

8. run frontend
   ```bash
   npm start
