# AI Youtube Shorts Generator

AI Youtube Shorts Generator is a Python tool designed to generate engaging YouTube shorts from long-form videos. By leveraging the power of GPT-4 and Whisper, it extracts the most interesting highlights, detects speakers, and crops the content vertically for shorts. This tool is currently in version 0.1 and might have some bugs.


![longshorts](https://github.com/user-attachments/assets/3f5d1abf-bf3b-475f-8abf-5e253003453a)

[Demo Input Video](https://github.com/SamurAIGPT/AI-Youtube-Shorts-Generator/blob/main/videos/Blinken%20Admires%20'Friend%20Jai'%20As%20Indian%20EAM%20Gets%20Savage%20In%20Munich%3B%20'I'm%20Smart%20Enough...'%20%7C%20Watch.mp4)

[Demo Output Video](https://github.com/SamurAIGPT/AI-Youtube-Shorts-Generator/blob/main/Final.mp4)

## Features

- **Video Download**: Given a YouTube URL, the tool downloads the video.
- **Transcription**: Uses Whisper to transcribe the video.
- **Highlight Extraction**: Utilizes OpenAI's GPT-4 to identify the most engaging parts of the video.
- **Speaker Detection**: Detects speakers in the video.
- **Vertical Cropping**: Crops the highlighted sections vertically, making them perfect for shorts.

## Installation

### Prerequisites

- Python 3.7 or higher
- FFmpeg
- OpenCV

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/SamurAIGPT/AI-Youtube-Shorts-Generator.git
   cd AI-Youtube-Shorts-Generator
   ```

2. Create a virtual environment

```bash
python3.10 -m venv venv
```

3. Activate a virtual environment:

```bash
source venv/bin/activate # On Windows: venv\Scripts\activate
```

4. Install the python dependencies:

```bash
pip install -r requirements.txt
```

---

1. Set up the environment variables.

Create a `.env` file in the project root directory and add your OpenAI API key:

```bash
OPENAI_API=your_openai_api_key_here
```

## Usage

1. Ensure your `.env` file is correctly set up with your OpenAI API key.
2. Run the main script and enter the desired YouTube URL when prompted:
   ```bash
   python main.py
   ```

