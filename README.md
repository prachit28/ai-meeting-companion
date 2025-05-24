# ai-meeting-companion

Business AI Meeting Companion STT

## Preparing the environment

```sh
pip3 install virtualenv 
virtualenv my_env # create a virtual environment my_env
source my_env/bin/activate # activate my_env
```

## Install the dependencies

```sh
pip3 install -r requirements.txt
```

## Install ffmpeg

> This is required to work with audio files

```sh
sudo apt update
sudo apt install ffmpeg -y
```