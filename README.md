# Py-Media-Editor
This Python script allows users to download audio from YouTube videos, crop the audio, and combine multiple audio files into a single MP3. It uses the `pytube` library for downloading audio and `pydub` for processing audio files.

## Features

- **Download YouTube Audio**: Download the audio track from a YouTube video in MP4 format.
- **Crop Audio Files**: Convert downloaded audio files into MP3 format and crop them to a specified time range.
- **Combine MP3 Files**: Merge multiple MP3 files into a single audio file.

## Requirements

- Python 3.x
- `pytube`
- `pydub`
- `ffmpeg` (required by `pydub` for audio conversion)

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Amysoj-Louis/Py-Media-Editor.git
   ```

2. Install the required Python packages:

   ```bash
   pip install pytube pydub
   ```

3. Make sure `ffmpeg` is installed and added to your system's PATH. if running locally

## Usage

1. Run the script:

   ```bash
   python main.py
   ```

2. Follow the on-screen instructions to download audio, crop files, or combine MP3 files.

### Commands

- **Download**: Enter a YouTube video link to download its audio.
- **Crop**: Provide start and end times (in milliseconds) to crop the audio.
- **Combine**: Merge all MP3 files in the directory into a single `output.mp3`.
- **Exit**: Exit the program.
