# Genre/Mood MIR

[![](https://img.shields.io/badge/-Python%203.11-ffd343?logo=python)](https://www.python.org/)
[![](https://img.shields.io/badge/-PyTorch%202.0-gray?logo=pytorch)](https://pytorch.org/)

This project explores the use of Mel Spectrogram images for AI models to predict the genre & mood of given music.

First of all, two model were freshly trained using the [GTZAN](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification) and the [DEAM](https://www.kaggle.com/datasets/imsparsh/deam-mediaeval-dataset-emotional-analysis-in-music) datasets for genre and mood prediction respectively. \
Then, a pre-trained model (ResNet18) was further trained on those datasets for the same tasks to compare against freshly trained models. \
Finally, the pre-trained models were combined into a single model to predict both genre & mood at the same time.

## Content
All of the project is documented inside the ```MAIN.ipynb``` notebook file which is already split into commented sections explaining what is going on. Since it is a jupyter notebook file, all output cells providing valuable insight were kept to show the results obtained.
