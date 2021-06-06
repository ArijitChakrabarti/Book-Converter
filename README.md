# Book-Converter
This python file allows anybody to convert any book or other document to an mp3 file

There are two ipynb files one using gTTS - the Google Text to speech api and the other using pyttsx3 with adjustments.
The Google Text to Speec implementation can fail while trying to convert long texts as it accesses  input from google servers.  While the pyttsx3 implementation is much faster and uses local system data.
