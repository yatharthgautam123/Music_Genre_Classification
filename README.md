# GTZAN Music Genre Classification Project

## Overview
This project aims to perform music genre classification using the GTZAN Dataset for Music Genre Classification. The GTZAN dataset is a widely used benchmark dataset in the field of music genre classification, containing audio excerpts of 10 music genres.

## Dataset
The GTZAN dataset consists of audio excerpts from various music genres:
- Blues
- Classical
- Country
- Disco
- Hip-Hop
- Jazz
- Metal
- Pop
- Reggae
- Rock

The dataset contains 100 audio excerpts per genre, each approximately 30 seconds long.

### Dataset Source
The GTZAN dataset is available on Kaggle at [GTZAN Dataset for Music Genre Classification](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification).

## Project Structure
GTZAN-Music-Genre-Classification/
│
├── data/
│ ├── GTZAN_dataset/ # Directory containing the GTZAN dataset files
│ │ ├── blues/
│ │ ├── classical/
│ │ ├── country/
│ │ ├── disco/
│ │ ├── hip-hop/
│ │ ├── jazz/
│ │ ├── metal/
│ │ ├── pop/
│ │ ├── reggae/
│ │ └── rock/
│ ├── features_3_sec.csv # CSV file containing extracted features for classification
│ └── README.md # Readme file for data directory
│
├── notebooks/
│ └── music_genre_classification.ipynb # Jupyter notebook containing the project code
│
└── README.md # Project overview and instructions


1. **Download the Dataset**:
- Download the GTZAN dataset from [Kaggle](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification).
- Extract the dataset files into the `data/GTZAN_dataset/` directory.

2. **Setup Environment**:
- Ensure you have the required Python packages installed.


3. **Run the Jupyter Notebook**:
- Open and run the `notebooks/music_genre_classification.ipynb` Jupyter notebook to execute the project code.

## Results
The project utilizes machine learning algorithms and neural networks to classify music genres based on extracted features from audio files. The performance of the models is evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Contributors
- [Yatharth Gautam](https://github.com/yatharthgautam123)

