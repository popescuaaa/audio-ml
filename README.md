# audio-ml
Automatic Speech Recognition and other audio explorations...


## Setup

### Create a new conda environment

```bash
conda create -n audio-ml python=3.10
conda activate audio-ml
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Install ffmpeg (optional for audio recording)


```bash
# macOS
brew install ffmpeg

# Ubuntu
sudo apt install ffmpeg

# Windows
choco install ffmpeg 

# or download from https://ffmpeg.org/download.html

```


### Note
The audio record part will work only in the browser version of the notebook, not the vscode version. You need to allow the browser to access your microphone.
