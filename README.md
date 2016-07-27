# coscup-line-bot

## How to deploy

### Requirements

* python 3.5

### Install Dependency

```
pip install -r /path/to/requirements.txt
```

### Configuration

Coscup line bot will use these env. Please make sure you setup these value:

```
CHANNEL_MID = 'Your line bot's channel mid'
CHANNEL_ID = 'Your line bot's channel id'
CHANNEL_SECRET = 'Your line bot's channel secret'
WIT_ZHTW_TOKEN = 'Your wit.ai app token'
DEBUG = '1' # If DEBUG env is '1' will set logger's level to debug else INFO.
```

### Run

```
python server.py
```