# Desktop-Assistant

Nowadays, with the development of technology, we are preferring to speak rather than type. We all would be using Siri, Google Assistant, Alexa, etc. All these assistants are built using complex algorithms and steady hard work. These not only make our task easy but also save time. It would be wonderful to build a personal voice assistant right?
We will be using multiple Python modules to build this voice assistant for doing different tasks like accessing files from the device, opening a browser, finding time, weather, etc. One of the main modules is the speech_recognition which is the heart of the whole project. Using this, we will be listening to the voice messages, decode them and also give vocal outputs.

Other modules can be used based on the commands we are adding to our assistant. The ones we will be using in this article are:

1.  Subprocess: This module can be used to get information from the device to do the tasks like sleep, shutdown, etc.

2. Wolframalpha: This module helps us in answering some questions with the help of Wolfram’s algorithms, knowledgebase and AI technology.

3. Pyttsx3: Using this module helps in converting the text to speech form.

4. Datetime: This module is used to get the current time

5. Wikipedia: This module helps in opening wikipedia and searching for what the user asks.

6. Webbrowser: This module also helps in opening the browser and performing search.

7. Winshell and Os: This module helps in accessing the files and folders in the device

8. Pyjokes: Pyjokes module contains different jokes which can be made listened to by the user.

9. Requests: This helps in accessing the websites using url.

10. Shutil: This allows us to modify and operate on the files in the device.

11. Smtplib: This module helps in sending emails.

12. Bs4: This module helps in extracting information from the request made to the website.

13. Tkinter: We use this module to build the GUI

Prerequisites
It is advised that the user has prior knowledge of python and some command on basic Python modules. Some of the module we use are standard ones, while the ones that we have to import are as follows:

pip install wolframalpha
pip install pyttsx3
pip install wikipedia
pip install winshell
pip install pyjokes
pip install smtplib
pip install twilio
pip install beautifulsoup4
pip install tk

Steps to build the Voice Assistant Project using Python
We will be following the below steps to build the voice assistant:

1. First, we import the modules.

2. Followed by this, we will be building the voice assistant and create function to speak using the voice engine

3. Then we create the function to wish, get the name of the user and command

4. Next, we will be writing functions to do various tasks like getting a weather report, sending mail, etc.

5. Finally, we write the while loop to run the assistant continuously. In which we take the command and check the command to do the respective task using if else statements.

6. Note that all the tasks we include are our choice. Depending on your comfort, you can add required commands and remove the ones that you don’t need. And make the voice assistant based on your suitability.

