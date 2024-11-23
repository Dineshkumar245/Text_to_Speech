# Text_to_Speech
The HTML code you've provided creates a simple and stylish text-to-speech (TTS) web application. Here's a breakdown of the content and functionality:
Overview:
Purpose: The page allows users to input text, which is then converted into speech when they click the "Convert to Speech" button. Users can also stop the speech using the "Stop Speech" button.
Design: The page features a clean, modern design with a light gradient background and a centered container for text input and buttons.

# Key Features:
1)Input Area: A text area is provided where users can type in the text they want to be converted to speech.

2)Convert to Speech Button: When clicked, this button triggers the text-to-speech conversion, reading out the inputted text using the browser's SpeechSynthesis API.

3)Stop Speech Button: This button allows users to stop the speech immediately.

4)Styling: The page uses a pleasant color scheme, a rounded container, and smooth button hover effects to enhance the user experience.

# Additional Explanation of the JavaScript Code:
The SpeechSynthesisUtterance() is used to configure and control the speech synthesis properties like text, rate, volume, and pitch.
The speak() function triggers the conversion, while the stopSpeech() function stops the speech.
This page provides a functional and visually appealing text-to-speech conversion tool for users.
