# Weather-Based Activity Recommender API

An API built with FastAPI that takes a city name, fetches live weather data from the OpenWeatherMap API, and returns a recommendation for a suitable activity based on the weather conditions.

## About The Project

This project demonstrates the ability to build an intelligent API that adds business logic on top of an external data source. Instead of just returning raw data, it processes the information to provide a valuable, user-friendly recommendation.

This project showcases an end-to-end development process:
* Building a live web server using FastAPI.
* Interacting with a third-party REST API (`requests`).
* Parsing and handling JSON data.
* Implementing custom business logic to generate insights.

## Skills Showcased

* **Python**
* **API Development (FastAPI)**
* **Working with External APIs**
* **JSON Data Handling**
* **Business Logic Implementation**

## How to Run Locally

1.  Clone this repository.
2.  Install the required libraries:
    ```bash
    pip install fastapi "uvicorn[standard]" requests
    ```
3.  **Important:** You must get your own free API key from [OpenWeatherMap](https://openweathermap.org/) and replace the `API_KEY` placeholder in the `main.py` script.
4.  Run the server from your terminal:
    ```bash
    uvicorn main:app --reload
    ```
5.  Open your web browser and navigate to `http://127.0.0.1:8000/recommendation/London` to test the API.
