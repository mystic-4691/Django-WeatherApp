Django Weather App with OpenWeather API
This is a simple Django web application designed to fetch and display weather information using the OpenWeather API.

Features:
Current Weather: Display current weather conditions for a specific location.
Forecast: View a 5-day weather forecast for a specified location.
Prerequisites:
Python 3.x installed on your system.
Django framework installed (installation instructions available at Django Installation).
An API key from OpenWeather API. Sign up and get your API key here.
Installation:
Clone this repository to your local machine:
bash
Copy code
git clone <repository_url>
Navigate to the project directory:
bash
Copy code
cd django-weather-app
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Set up your API key:
Create a .env file in the root directory.
Add your OpenWeather API key to the .env file:
makefile
Copy code
OPENWEATHER_API_KEY=your_api_key_here
Migrate the database:
bash
Copy code
python manage.py migrate
Run the development server:
bash
Copy code
python manage.py runserver
Visit http://localhost:8000 in your web browser to access the application.
Usage:
Enter a location in the search bar.
Click on "Get Weather" to view current weather conditions or "Get Forecast" to view a 5-day weather forecast for the specified location.
Weather information will be displayed on the page.
Contributing:
Contributions are welcome! If you'd like to contribute to this project, feel free to open an issue or submit a pull request.

License:
This project is licensed under the MIT License. See the LICENSE file for details.
