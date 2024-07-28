
# Voice Chat App Powered by OpenAI

## Description
A voice chat application that leverages OpenAI's language model for intelligent responses. This project sets up the environment using a Python virtual environment and installs the required libraries.

## Preparing the Environment

### Step 1: Install Virtualenv
First, install `virtualenv` if you haven't already:
```bash
pip3 install virtualenv
```

### Step 2: Create and Activate a Virtual Environment
Create a virtual environment named `my_env` and activate it:
```bash
virtualenv my_env  # create a virtual environment my_env
source my_env/bin/activate  # activate my_env
```

### Step 3: Install Required Libraries
Install the required libraries in the environment (this will take some time ☕️):
```bash
pip install transformers==4.35.2 torch==2.1.1 gradio==4.17.0 langchain==0.0.278 librosa==0.10.0 numpy==1.24.3
```

### Step 4: Install ffmpeg
We need to install `ffmpeg` to be able to work with audio files in Python.

First, update the package list:
```bash
sudo apt update
```

Then, install `ffmpeg`:
```bash
sudo apt install ffmpeg -y
```

## Running the Application
After setting up the environment and installing all the required libraries, you can run the application with the following command:
```bash
python3 speech_analyzer.py
```
