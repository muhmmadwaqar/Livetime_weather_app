# Livetime_weather_app

## Overview
The Live Weather App is a web application that displays real-time weather data for a specified city. The app fetches weather data from a public API and updates the data in real-time using MQTT. The data is displayed in a responsive layout using Bootstrap and visualized with Chart.js.

## Features
- Real-time weather data updates
- Responsive user interface
- Data visualization using charts
- MQTT for real-time communication
- Secure user authentication

## Technologies Used
- **Backend**: Django, Django Channels
- **Frontend**: HTML5, CSS3, Bootstrap, JavaScript, Chart.js
- **Database**: PostgreSQL
- **Real-time Communication**: MQTT
- **Other**: Celery, Redis

## Prerequisites
- Python 3.7+
- PostgreSQL 9.6+
- Node.js
- npm
- Redis

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/live_weather_app.git
cd live_weather_app

## 2. Create a Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
### 3. pip install -r requirements.txt
## 4 . 4. Configure PostgreSQL
Ensure PostgreSQL is installed and running. Create a database and user for the app
CREATE DATABASE live_weather_app;
 ##5 Run the Development Server
python manage.py runserver
## 
## Additional Instructions

1. **Update the Repository URL**:  `https://github.com/muhmmad-waqar/live_weather_app.git` 
2. **Database Configuration**: Ensure the database settings in the `settings.py` file match your PostgreSQL setup.
3. **Contact Information**:  `[itswaqarmalik11@gmail.com]`

Access the application at http://127.0.0.1:8000/.
Login with the superuser account.
Enter a city name to view real-time weather data.
Contributing
Contributions are welcome! Please open an issue or submit a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.



