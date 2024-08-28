# Cricket_Analysis-and-Prediction-system

# Project Overview

This repository contains various components for image classification and predictive modeling related to cricket match outcomes. Below is a summary of the folder structure and contents:

## Folder Structure

### `CNN_Runout/`

This folder contains datasets and code related to image classification for predicting "out" and "not out" scenarios.

- **`Dataset/`**: Contains images split into training and validation folders for both "out" and "not out" categories.
- **`Practice_Work/`**: Contains preliminary work and experiments related to Convolutional Neural Networks (CNN).
- **`CNN_Final/`**: Contains the final code for CNN models used to classify images.

### `Match_Prediction/`

This folder contains models for predicting cricket match outcomes.

- **`ODI_Model/`**: Contains a Decision Tree model trained on One Day International (ODI) match data.
- **`T20_Model/`**: Contains a Random Forest model trained on Twenty20 (T20) match data.

### `Data_Analysis/`

This folder includes Streamlit apps for exploratory data analysis.

- **`Streamlit_App/`**: Contains the Streamlit app files for data analysis and visualization.

### `Final_Streamlit/`

This folder contains the final Streamlit application which integrates all models and analyses.

- **`Final_Streamlit_App.py`**: The main Streamlit application that combines all models and data analysis.
- **Supporting Files**: Note that supporting files such as saved models and label encoders are not included in this repository. You can download these files from the following link:
  [Download Supporting Files](https://drive.google.com/drive/folders/16k6hCIrqIwT6Z18F-2TXsSFpFSBccV5l?usp=sharing)

## Getting Started

### Prerequisites

- Python 3.x
- Required Python libraries: TensorFlow, scikit-learn, Streamlit, and other dependencies listed in `requirements.txt`.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository-url.git
