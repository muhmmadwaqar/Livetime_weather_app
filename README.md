# Live Weather App  

## Overview  
The **Live Weather App** is a dynamic web application that provides real-time weather data for any specified city. Leveraging advanced technologies, this app fetches live weather information from a public API and ensures instant updates via MQTT. With a sleek and responsive layout powered by Bootstrap, users can easily visualize weather trends through interactive charts created with Chart.js.

## Features  
- **Real-Time Updates**: Instant weather data refresh for accurate readings  
- **Responsive Design**: Seamless experience across devices  
- **Data Visualization**: Engaging charts for insightful weather patterns  
- **MQTT Integration**: Efficient real-time communication  
- **User Authentication**: Secure login for personalized access  

## Technologies Used  
- **Backend**: Django, Django Channels  
- **Frontend**: HTML5, CSS3, Bootstrap, JavaScript, Chart.js  
- **Database**: PostgreSQL  
- **Real-time Communication**: MQTT  
- **Task Queue**: Celery  
- **Caching**: Redis  

## Prerequisites  
- Python 3.7+  
- PostgreSQL 9.6+  
- Node.js  
- npm  
- Redis  

## Installation  

### 1. Clone the Repository  
```bash  
git clone https://github.com/muhmmad-waqar/live_weather_app.git  
cd live_weather_app  
```  

### 2. Create a Virtual Environment  
```bash  
python -m venv venv  
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`  
```  

### 3. Install Dependencies  
```bash  
pip install -r requirements.txt  
```  

### 4. Configure PostgreSQL  
Ensure PostgreSQL is installed and running. Create a database and user for the app:  
```sql  
CREATE DATABASE live_weather_app;  
```  

### 5. Run the Development Server  
```bash  
python manage.py runserver  
```  

## Access the Application  
- Visit [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to access the application.  
- Log in using your superuser account.  
- Enter a city name to view real-time weather data.  

Contributing
We welcome contributions from the community! To contribute:

Fork the repository.
Create a new branch:
sh
Copy code
git checkout -b my-feature-branch
Make your changes and commit them:
sh
Copy code
git commit -m 'Add new feature'
Push your changes to the branch:
sh
Copy code
git push origin my-feature-branch
Submit a pull request for review.
License
This project is licensed under the MIT License. For more details, please refer to the LICENSE file.

Contact
For inquiries, support, or feedback, please reach out:

Muhammad Waqar
Email: itswaqarmalik11@gmail.com
I welcome any questions or assistance you may need regarding the platform.

This README was generated with ❤️ by Muhammad Waqar

