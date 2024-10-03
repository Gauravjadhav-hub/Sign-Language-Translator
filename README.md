Hearing Impairment Assistant
This Python-based project helps bridge the communication gap for individuals with hearing impairments by converting spoken language into Indian Sign Language (ISL) visuals. Using real-time speech recognition, the application displays ISL GIFs for commonly used phrases or alphabet images for spelling out other words.

Features
Real-time Speech Recognition: Captures live speech using speech_recognition and converts it into ISL gestures.
ISL Visuals: Displays appropriate ISL GIFs for common phrases or letters from A-Z.
Dynamic Display: Phrases that are not predefined will be spelled out letter by letter.
Simple GUI: Easy-to-use graphical interface using Tkinter and EasyGUI.
How It Works
Speech Input: The user selects the "Live Voice" option and speaks into the microphone.
ISL Gesture Display: If the spoken phrase matches a predefined ISL phrase, the corresponding GIF is displayed. Otherwise, the system displays letters as images.
Quit: The user can exit the application by choosing the "All Done!" option.
Prerequisites
Python 3.x
Libraries:
speech_recognition
matplotlib
opencv-python
PIL
easygui
tkinter
numpy
Install the dependencies using the following command:

bash
Copy code
pip install speechrecognition numpy matplotlib opencv-python easygui pillow
How to Run
Clone the repository:
bash
Copy code
git clone https://github.com/Sign-Language-Translator/hearing-impairment-assistant.git
Navigate to the project directory:
bash
Copy code
cd hearing-impairment-assistant
Run the Python script:
bash
Copy code
python hearing_impairment_assistant.py
Select "Live Voice" to start recognizing speech and translating it to ISL.
Directory Structure
ISL_Gifs/: Contains the ISL GIFs for predefined phrases.
letters/: Contains images for alphabet letters A-Z.
signlang.png: GUI background image for the main menu.
Future Improvements
Add more phrases and gestures.
Expand support to other sign languages.
Develop a mobile version using Flutter.
