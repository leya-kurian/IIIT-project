# IIIT Hyderabad Speech Analytics Research Teaser Program

## Speaker Recognition Model Repository

Welcome to the IIIT Hyderabad Speech Analytics Research Teaser Program Speaker Recognition Model repository! This repository contains files related to the speaker recognition model developed as part of the research teaser program at IIIT Hyderabad.

## Dataset

The dataset used for training and evaluation is sourced from Kaggle. It contains speeches of five prominent leaders, namely:

- Benjamin Netanyahu
- Jens Stoltenberg
- Julia Gillard
- Margaret Thatcher
- Nelson Mandela

Each speaker's speeches are stored in separate folders with the respective names. Each audio file in the folder represents one second of speech, sampled at 16000 Hz and encoded in PCM format.

The original speeches for each speaker were single lengthy audio files, which have been chunked into one-second segments for easier workability. Combining the chunked audios from 0.wav to 1500.wav forms a complete speech of the respective speaker.

Additionally, there is a folder called `background_noise` containing audio clips that are not speeches but represent ambient sounds found inside and around the speaker environment, such as audience laughing or clapping. These can be mixed with the speeches during training for a more realistic environment.

The dataset details can be found at [Kaggle Dataset]([https://www.kaggle.com/datasetname](https://www.kaggle.com/datasets/kongaevans/speaker-recognition-dataset)).
