# ESC50 with TensorFlow
The ESC50 dataset is a small audioset of 2000 audio samples, each 5 seconds long. It's available from [GitHub](https://github.com/karolpiczak/ESC-50#download) in raw audio (i.e., wave format) form.

This repository contains a small script that reads the audio files and writes them to TFRecords, TensorFlow's way of efficient data storage and streaming.
Additionally, it contains sample code to read the data from the TFRecords into a dataset.
