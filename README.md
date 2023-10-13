# My Transcript tool

This is a simple python program that uses FFMPEG to turn video into audio, audio into text with OpenAI Whisper, text into summary with chatgpt

# Usage
clone the repo (or download zip)

Make a virtual environment and install the requirements.txt file into it (developed in python 3.9.16 should work in newer versions) also sorry that the requirements.txt file is long, I should not have done this in a conda environment

Make sure you have ffmpeg installed

Make a folder in the unzipped folder

make an environment variable and call it OPENAIKEY and set it to your openAI api key or just replace os.getenv("OPENAIKEY") from openai.api_key = os.getenv("OPENAIKEY") to your key with " on each side

change the fileStorage = "xxxxx" to the name of your folder in whisper.ipynb no shashes or anything else required

add the videos to that folder

run every cell in whisper.ipynb

