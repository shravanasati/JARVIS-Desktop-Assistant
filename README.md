# JARVIS-Desktop-Assistant
**Desktop Assistant** - An ultimate desktop assistant that makes your life easier by automating some mundane, daily tasks. It's an AI without any algorithm. 

## Functionalities:
* starts some applications
* automatically joins ZOOM meetings
* reports latest news and weather 
* runs games namely, Guess the number and Snake Water Gun on the console
* has speech recognition property which enables user to look up in the internet
* can change the robotic voice from male's voice to female's voice
* informs the magnitude of confirmed cases of SARS-COV2 of the country asked (and of India by default)
* initiates timer and stopwatch
* can send as well as read emails
* kicks off screen recording when asked through Icecream screen recorder
* automatically displays images from web browser when asked to do so


NOTE: Provide URLs and application paths for the repective sites/apps to run this program. Also find the dependencies for this program below.

*External Modules required:*
- pyttsx3 --> ```pip install pyttsx3``` == For speaking ability.
- SpeechRecognition --> ```pip install SpeechRecognition``` == For listening ability.
- wikipedia --> ```pip install wikipedia``` == To search through the wikipedia for the query.
- pyautogui --> ```pip install pyautogui``` == For controlling the GUI.
- pyaudio --> ```pip install pyaudio``` == Dependency for speech recognition module.

### Solving issues
1. If you are unable to install ```pyaudio```, type the following commands:

```pip install pipwin```

```pipwin install pyaudio```

It should work now.
