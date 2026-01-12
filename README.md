# Telegram Weather Bot 🌤

This project demonstrates how to work with external APIs using Python.
The goal of the project is to retrieve weather data from a public Weather API
and send the result automatically to a Telegram chat using the Telegram Bot API.

---

## Project Overview

In this project, a Telegram bot is created to send weather reports.
The bot fetches the current temperature of a selected city from a weather API
and delivers the information to Telegram programmatically.

This project focuses on understanding API communication, data processing,
and automated message delivery.

---

## APIs Used

- **Open-Meteo Weather API**  
  Used to retrieve real-time weather data (current temperature).

- **Telegram Bot API**  
  Used to send messages from the Python program to a Telegram chat.

---

## Implementation Steps

The project was implemented in the following steps:

1. **Creating a Telegram Bot**  
   A Telegram bot was created using BotFather, and a bot token was generated.

2. **Starting a Chat with the Bot**  
   A chat was initiated with the bot in Telegram to generate a unique chat ID.

3. **Retrieving the Chat ID**  
   The chat ID was obtained from JSON data after sending a message to the bot.

4. **Fetching Weather Data from the API**  
   The program sends a request to the Open-Meteo API and retrieves the current
   temperature in JSON format.

5. **Processing API Response**  
   The JSON response is parsed to extract the temperature value.

6. **Sending Data to Telegram**  
   The extracted temperature is formatted into a message and sent to the
   Telegram chat using the Telegram Bot API.

7. **Automation (Optional)**  
   The script can be extended to run automatically at specific times
   (morning, afternoon, and evening).

---

## Technologies Used

- Python
- REST APIs
- JSON
- Telegram Bot API
- Open-Meteo Weather API

---

## Example Output

🌤 Weather Report  
City: Austin  
Current Temperature: 28 °C  

---

## Purpose of the Project

The purpose of this project is to practice working with APIs, handling JSON
responses, and integrating multiple services using Python. It serves as a
hands-on example of API-based automation and messaging.

---

## Notes

- Sensitive information such as bot tokens is not included in the repository.
- The project can be easily extended with additional features such as
  scheduling, multiple cities, or different weather parameters.
