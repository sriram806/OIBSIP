Voice Assistant:
This is a Python script that will create a simple voice assistant which will be able to perform tasks through voice such as, tell time, date, do web searches among others.

Description:
The Voice Assistant script allows users to interact verbally with their computer to:The Voice Assistant script allows users to interact verbally with their computer.

Says hello when he/she hears hello being said.
Retrieve Time: Gives out the current time depending on the format that is set.
Retrieve Date: Prints out the current date in the format that people like to read it – dd.mm.yyyy.
Web Search: Provides the user with an option of searching through Google in relation to the input made.
Exit: Closes the voice assistant interaction and ends the user’s commands and inquiries on the application.
It utilizes the following libraries:It utilizes the following libraries:

speech_recognition: for converting speech to text the following package is used pip install SpeechRecognition.
pyttsx3: for converting text to speech ,pip install pyttsx3.
datetime: For performing date and time related operations the built-in Python module named datetime is used.
webbrowser: for opening web browser i.e. to find some search results and in the analysis part for opening Json file in another window (pip install pycopy-webbrowser).

Function:
Speech Recognition: Uses speech_recognition library to listen for command and then convert the speech given into a text command.
Text-to-Speech Conversion: Uses pyttsx3 for text to speech conversion in order to give the responses in words.
Time and Date: Fetches and pronounces the current time and date by using the Python’s datetime function.
Web Search: This opens a web browser and searches Google using the webbrowser with the queries from the user.
Command Handling: Reacts to the names and recognizes manners of salutations, time related questions and inquiries about dates and web searches.
