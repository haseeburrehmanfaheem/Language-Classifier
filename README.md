
# Language Classifier

This repository contains a project aimed at classifying speech samples into different language categories using machine learning techniques. The project is divided into two phases:

## Table of Contents
- [Project Overview](#project-overview)
- [Phase 1: Multi-Language Classifier](#phase-1-multi-language-classifier)
- [Phase 2: English-Urdu Classifier](#phase-2-english-urdu-classifier)
- [Datasets](#datasets)
- [Installation and Setup](#installation-and-setup)

## Project Overview

The goal of this project is to classify spoken language samples into different language categories by extracting **Mel-frequency Cepstral Coefficients (MFCCs)** from the audio files and using machine learning models to classify these features.

The languages involved in this project include:
- **English**
- **Urdu**
- **Punjabi**
- **Saraiki**
- **Mixed Languages** (a combination of multiple languages in a single sample)

The classification is divided into two phases, each with different objectives and datasets.

## Phase 1: Multi-Language Classifier

In the first phase, the classifier is designed to distinguish between five different language categories:
- **English**
- **Urdu**
- **Punjabi**
- **Saraiki**
- **Mixed Languages**

The classifier extracts MFCCs from the audio recordings and uses these features to make language predictions.

## Phase 2: English-Urdu Classifier

In the second phase, the classifier is fine-tuned to focus on classifying between:
- **English**
- **Urdu**
- **Mixed Languages**

The dataset used in Phase 2 consists of **17,380 recordings**. This phase narrows the scope of classification to improve accuracy in distinguishing between fewer language categories.

## Datasets

Links to the datasets used in both phases are provided in the respective `.ipynb` files:
- The dataset for **Phase 1** can be found in the `Phase-1.ipynb` notebook.
- The dataset for **Phase 2** is provided in the `Phase-2.ipynb` notebook.

The datasets contain audio recordings in `.wav` format, with labels corresponding to the spoken language.

## Installation and Setup

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   ```
   
2. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the datasets** as indicated in the Jupyter notebooks.

4. **Run the Jupyter notebooks**:
   Open `Phase-1.ipynb` or `Phase-2.ipynb` in Jupyter and run the cells to reproduce the results.
