# LiveCityInfo-Weather-Map-News-Insights
Certainly, here are the step-by-step instructions for setting up and running the WeatherMapNews App using a virtual environment for Python 3.13.5:

1. Setup Virtual Environment:
* Open the terminal or Anaconda Prompt.
* Install the virtual environment package if you haven’t already: conda create -p venv python=3.13.5 -y
* Create a virtual environment: virtualenv venv
* Activate the virtual environment: conda activate venv/

2.Install Requirements:

* Install all necessary dependencies from the requirements file:
 
    ->pip install -r requirements.txt
* If you don’t have a requirements.txt file, manually install required packages like:
  
    ->pip install requests pillow tkinter matplotlib geopy gtts playsound deep-translator
