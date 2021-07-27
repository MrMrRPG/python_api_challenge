# python_api_challenge
This repository is for the API challenge at UCI's data bootcamp.

The main use of this repository is to gather real time weather information and
to locate suitable vacation spots based on weather preference. This program is
not intended for commercial use.
## Prerequisites
The follow prerequisites are **required** to properly run this program, or else it will not run propperly.
1. You will need a program that will run `.ipynb` files. Jupyter Notebook is highly recommended.
2. Install the following dependencies if your environment does not have them already:
	* citipy
	* gmaps
3. You will need your own [OpenWeather](https://openweathermap.org/api) and
[Google Cloud](https://cloud.google.com/docs/authentication/api-keys) API keys
to properly run this program. 
	* If you do not have one, register one each.
	* Once you have registered your api keys, paste them respectively in `starter_code/api_keys.py`. 

## Instructions
1. In the `starter_code` directory, use your program of choice to run `WeatherPy.ipynb`. 
	* All relevant outputs are saved in `starter_code/outputdata`

2. After that, run `VacationPy.ipynb`. All previously saved screenshots are also
saved in `starter_code/outputdata/gmaps_screenshots` marked with their saved dates.
	* Note that the images saved in this directory may not reflect the same date as you are running your code, since there saved images are samples of previous attempts.