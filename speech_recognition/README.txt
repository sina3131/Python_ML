


Description
This is a speech recognition and live translation programe in python usuing pyaudio, vosk, and tranformers libraries.
The programe starts recording the microphone of choice, then it uses pretrained modules to convert the audio to text, finally it uses the tranformers model to translate the text 
to language of choice. 

There are 3 example languages that you can try, but the english one is more accurate due to it's large trained model.

The Vosk model is a pre-trained automatic speech recognition (ASR) model developed by Vosk Speech. 
It is trained to recognize speech in multiple languages, including Swedish. 
This particular model is optimized for small-scale applications and integrates 
with Rhasspy, an open-source voice assistant platform.
