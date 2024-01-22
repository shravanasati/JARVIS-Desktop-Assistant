# JARVIS-Desktop-Assistant
**Desktop Assistant** - An ultimate desktop assistant that makes your life easier by automating some mundane, daily tasks. It's an AI without any algorithm. 

## Functionalities:
* starts some applications
* automatically joins ZOOM meetings
* reports latest news and weather 
* runs games namely, Guess the number and Snake Water Gun on the console
* has speech recognition property which enables user to look up in the internet
* can change the robotic voice from male's voice to female's voice
* informs the magnitude of confirmed cases of Covid-19 of the country asked (and of India by default)
* initiates timer and stopwatch
* can send as well as read emails
* kicks off screen recording when asked through Icecream screen recorder
* automatically displays images from web browser when asked to do so


NOTE: Provide URLs and application paths for the repective sites/apps to run this program. Also find the dependencies for this program below. Zoom and IceCream Screen Recorder are required to perform two of the above tasks.

*External Modules required:*
- pyttsx3 --> For speaking ability.
- SpeechRecognition --> For listening ability.
- wikipedia --> To search through the wikipedia for the query.
- pyautogui -->  For controlling the GUI.
- pyaudio --> Dependency for speech recognition module.

To install all the dependencies at once, execute:

`pip install -r requirements.txt`

I've imported some of the functions/classes from my own python scripts. These scripts are:
- [news_reporter](https://github.com/shravanasati/Real-Time-Reporting)
- [weather_monitor](https://github.com/shravanasati/Real-Time-Reporting)
- [snake_water_gun](https://github.com/shravanasati/The-Leap)
- [guess_number](https://github.com/shravanasati/The-Leap)
- [spammer](https://github.com/shravanasati/Spammer)

Make sure you place these scripts in the same working directory as of this one.


### Solving issues
1. If you are unable to install ```pyaudio```, type the following commands:

```pip install pipwin```

```pipwin install pyaudio```

It should work now.
