Hearing Impairment Assistant
This Python-based project helps bridge the communication gap for individuals with hearing impairments by converting spoken language into Indian Sign Language (ISL) visuals. Using real-time speech recognition, the application displays ISL GIFs for commonly used phrases or alphabet images for spelling out other words.

Features
Real-time Speech Recognition: Captures live speech using speech_recognition and converts it into ISL gestures.
ISL Visuals: Displays appropriate ISL GIFs for common phrases or letters from A-Z.
Dynamic Display: Phrases that are not predefined will be spelled out letter by letter.
Simple GUI: Easy-to-use graphical interface using Tkinter and EasyGUI.
How It Works
1.Speech Input: The user selects the "Live Voice" option and speaks into the microphone.
2.ISL Gesture Display: If the spoken phrase matches a predefined ISL phrase, the corresponding GIF is displayed. Otherwise, the system displays letters as images.
3.Quit: The user can exit the application by choosing the "All Done!" option.
Prerequisites:
Python 3.x
Libraries:
1.speech_recognition
2.matplotlib
3.opencv-python
4.PIL
5.easygui
6.tkinter
7.numpy
Install the dependencies using the following command: pip install speechrecognition numpy matplotlib opencv-python easygui pillow
How to Run
Clone the repository: git clone https://github.com/Sign-Language-Translator/hearing-impairment-assistant.git
Navigate to the project directory: cd hearing-impairment-assistant
Run the Python script: python hearing_impairment_assistant.py
Select "Live Voice" to start recognizing speech and translating it to ISL.
Directory Structure
ISL_Gifs/: Contains the ISL GIFs for predefined phrases.
letters/: Contains images for alphabet letters A-Z.
signlang.png: GUI background image for the main menu.
Future Improvements:
1.Add more phrases and gestures.
2.Expand support to other sign languages.
3.Develop a mobile version using Flutter.
