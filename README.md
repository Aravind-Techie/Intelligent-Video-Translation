# **Intelligent Video Translation**

## **Project Overview**
The **Intelligent Video Translation** project translates audio from videos in one language into another, clones the original speaker’s voice, and overlays the translated audio back onto the video. The goal is to produce a translated video while retaining the original speaker’s voice characteristics.

## **Features**
- Extracts audio from videos.
- Transcribes audio into text.
- Translates the transcribed text into the target language.
- Generates speech from the translated text using voice cloning.
- Overlays the translated and cloned voice back onto the original video.

## **Project Structure**
```bash
.
├── extract_the_audio.py       # Script to extract audio from video
├── audio_to_text.py           # Script to transcribe audio from video
├── translate_text.py          # Script to translate transcribed text
├── text_to_audio.py           # Script to convert translated text to speech
├── combine_audio_video.py     # Script to combine the translated audio back to the video
├── requirements.txt           # Python package dependencies
└── README.md                  # Project documentation (this file)
