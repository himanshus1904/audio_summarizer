****YouTube Audio Summarizer****

****Overview:****

This project aims to summarize YouTube videos into concise text summaries. It utilizes Python libraries and AI models to achieve this goal. The process involves downloading the audio from YouTube videos, converting the audio to text, and then generating a summary of the text using GenAI.

**Process:**

Download YouTube videos as audio files using **pytube** library.

Convert audio files(mp3 currently) to text using **OpenAI Whisper** tiny.en model.

Generate text summaries using Google's Generative AI **gemini-pro** model

Customize summary length and other parameters.

**Requirements:**

Python 3.x

PyTube

OpenAI's Whisper

Google's gemini-pro


**Installation:**

Clone the repository:

git clone https://github.com/your_username/YouTube-Audio-Summarizer.git

**Install dependencies:**

**ffmpeg** is required for this project to run. Follow this link- https://www.geeksforgeeks.org/how-to-install-ffmpeg-on-windows/
**Google gemini** api key (Free) - https://aistudio.google.com/app/apikey
