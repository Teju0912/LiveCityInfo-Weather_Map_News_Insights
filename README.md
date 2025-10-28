# LiveCityInfo-Weather-Map-News-Insights
Certainly, here are the step-by-step instructions for setting up and running the WeatherMapNews App using a virtual environment for Python 3.13.5:

1. Setup Virtual Environment:
* Open the terminal or Anaconda Prompt.
* Install the virtual environment package if you haven’t already:
     - conda create -p venv python=3.13.5 -y
* Create a virtual environment:
     - virtualenv venv
* Activate the virtual environment: conda activate venv/

2. Install Requirements:

* Install all necessary dependencies from the requirements file:
    - pip install -r requirements.txt
* If you don’t have a requirements.txt file, manually install required packages like:
    - pip install requests pillow tkinter matplotlib geopy gtts playsound deep-translator

3. Set Up the Jupyter Notebook:

* Open the Jupyter Notebook in your virtual environment.
* Run the following commands:
   - pip install ipykernel
   - pip install jupyter notebook
* Then, start Jupyter Notebook:
   - jupyter notebook
* Open your project file WeatherMapNews_App.ipynb inside Jupyter.

4. Add Your API Keys (Important):

* Before running, make sure to add your API keys inside the code:
   - OpenWeatherMap API Key → for live weather data
   - NewsAPI.org Key → for live news updates

     *Example:
         - weather_api_key = "your_openweather_api_key"
         - news_api_key = "your_news_api_key"
