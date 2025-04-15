# Currency Exchange Rate Tracking Application

## Project Overview
The project involves building a simple web application to track and display exchange rates of selected currencies. The application will retrieve historical and real-time exchange rate data from an API and visualize the fluctuations in a user-friendly interface. 

The goal is to showcase your skills in API integration, data manipulation, and web development, specifically focusing on currency exchange trends related to the supply chain crisis.

## Scope and Objectives
**Objective**: Determine the currencies and time frame for tracking and analysis.

**Tasks**:
Choose Currencies: Select a pair of currencies to track. Example: USD/TZS (US Dollar / Tanzanian Shilling).

**Define Time Period**: Decide on the historical data range you will track. Suggested time frame: 2021 - 2023, capturing key changes during and after the supply chain crisis.

Key features of the application.
 -  Track daily exchange rate changes.
 -  Visualize trends over selected periods (e.g., monthly or quarterly).
 -  Option to update daily exchange rate data.

**Data Sources**: Choose an API (e.g., ExchangeRatesAPI.io) for fetching exchange rate data.

## Set up the Development Enviroment
1. Install Python (if not installed) and python required libraries 
     -  Download and install Python from python.org.
     -  Make sure to install pip (Python's package installer)
     -  ```pip install requests``` to make API calls
     -  ```pip install streamlit``` to build web app
     -  ```pip install pandas``` to manipulate and porcess the data
     - ```pip install matplotlib``` to visualize the data

2. Create requirements.txt listing all the dependencies in this file 

3. Create a Project Directory and organizing project files as follows
```
currency-tracker/
├── app/
│   ├── app.py
├── data/
│   ├── exchange_rates.json
├── requirements.txt
└── README.md
```  
## Connect, Retrieve and Store Exchange Rate API
1. Sign Up for an API Key:
   - Register on the ExchangeRatesAPI.io website or any other exchange rate
     service you choose.
   - Obtain your API key for authentication.

2. Send API Request
   - Write a Python script to connect to the API.
   - Retrieve exchange rates for the selected base currency (e.g., USD) and 
     target currency (e.g., TZS).

3. Handle API Response
   - Parse the JSON response to extract the relevant exchange rate data
   - Ensure you capture all the needed information, including the rates, base      currency, target currency, and date.

4. Store Data in JSON Format
   - Save the retrieved exchange rate data into a JSON file    (exchange_rates.json).
   - Ensure that the structure is clear and ready for further analysis.

5. Process Historical Data
   - If your API supports it, retrieve historical exchange rate data.
   - Store this historical data in a separate file (historical_rates.json) for trend analysis.

