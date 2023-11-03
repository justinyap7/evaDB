
# MP3 Summarizer EvaDB

MP3 Summarizer EvaDB is an innovative application designed to transcribe and summarize audio content from MP3 files. Leveraging the power of SpeechRecognition, pydub, and GPT4All, it transforms spoken words into written summaries, making it easier to digest and understand audio content quickly.

[Project Repository](https://github.com/justinyap7/mp3_summarizer_evaDB)

## Features

- **Transcription**: Convert spoken language within MP3 files to text using SpeechRecognition and pydub.
- **Summarization**: Summarize the transcribed text with the assistance of GPT4All's QA functionalities.
- **Ease of Use**: Simply input the path to your local MP3 file, or use the demo file provided by pressing "enter".
- **Local Processing**: Everything runs on your local machine, with no need for an external API key.

## Prerequisites

- Python >= 3.8
- FFmpeg must be installed and added to the system's PATH.
- Access to local MP3 files for summarization.

## Installation

Clone the repository and navigate to the project directory:

```sh
git clone https://github.com/justinyap7/mp3_summarizer_evaDB.git
cd evaDB
```
## Setup
Ensure that the local Python version is >= 3.8. Install the required libraries:

```bat
pip3 install -r requirements.txt
```

### How to Run
```bash
python mp3ToSum.py
```
