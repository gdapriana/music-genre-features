# 🎵 Music Genre Feature Extraction

A Python project for extracting audio features from music tracks across 5 different genres using MFCC (Mel-frequency cepstral coefficients) analysis.

## 🎯 Overview

This project downloads music from various online sources and extracts audio features for classification across five genres:
- 🎸 Rock
- 🎹 Pop
- 🎧 EDM
- 🎤 Rap/Hip-hop
- 🎼 R&B

## 📁 Project Structure

```
├── audio/              # Music files sorted by genre
│   ├── edm/
│   ├── pop/
│   ├── rap/
│   ├── rnb/
│   └── rock/
├── csv/                # Source CSV files with music download links
├── final/              # Extracted features in CSV format for each genre
├── dataset.ipynb       # Script for downloading music tracks
├── mfcc.ipynb         # Feature extraction implementation
├── display.ipynb      # Visualization of extracted features
├── requirements.txt    # Project dependencies
└── .gitignore         # Git ignore configurations
```

## ⚡ Features

- 🎵 Audio file downloading from online sources
- 📊 Feature extraction using:
    - Pre-emphasis
    - Framing & Windowing
    - Mel Filterbank
    - Discrete Cosine Transform (DCT)
- 📈 Visualization of extracted features
- 🎧 Support for multiple music genres

## 🛠️ Technologies Used

- 🐍 Python
- 📓 Jupyter Notebook
- 📚 Key Libraries:
    - 🎼 Librosa (audio processing)
    - 🔢 NumPy (numerical operations)
    - 📊 Matplotlib (visualization)
    - 📈 SciPy (signal processing)

## 🚀 Usage

1. Run `dataset.ipynb` to download music files
2. Execute `mfcc.ipynb` to perform feature extraction
3. Use `display.ipynb` to visualize the extracted features and analysis results

## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/[username]/music-genre-feature-extraction.git
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

## 📄 License
- [ ]

## 🤝 Contributing
- [ ]
