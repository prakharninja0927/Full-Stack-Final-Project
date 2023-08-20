
# Parkinson Disease Detection using Speech Analysis

![Parkinson Disease Detection](https://img.freepik.com/free-vector/parkinson-disease-symptoms-infographic_1308-48653.jpg?w=2000)

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Contributors](#contributors)
- [License](#license)

## Introduction

Parkinson's Disease is a neurodegenerative disorder that affects a person's movement. This repository contains a tool for detecting Parkinson's Disease through speech analysis. The tool uses machine learning techniques to analyze speech recordings and determine the likelihood of the presence of Parkinson's Disease.

## Installation

1. Clone this repository to your local machine.
   ```shell
   git clone https://github.com/prakharninja0927/Full-Stack-Final-Project.git
   ```

2. Navigate to the project directory.
   ```shell
   cd Full-Stack-Final-Project
   ```

3. Install the required dependencies.
   ```shell
   pip install -r requirements.txt
   ```

## Usage

1. Place your speech recordings in the `data` directory.

2. Run the detection script.
   ```shell
   python app.py
   ```

3. The script will output the likelihood of Parkinson's Disease presence based on the provided speech recording.

## Dataset

The dataset used for training and evaluation is the [Parkinson's Disease Classification Dataset](https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set), which contains speech recordings from individuals with and without Parkinson's Disease. The dataset is preprocessed to extract relevant features from the audio recordings.

## Methodology

The detection model is built using machine learning techniques, employing features extracted from speech recordings as inputs. and pass to algorithms and do benchmarking and selecte Sequentian Model to be the best and selected for our project, is trained on these features to differentiate between individuals with and without Parkinson's Disease.

## Results

The performance of the Parkinson's Disease detection model is evaluated using metrics such as accuracy, precision, recall, and F1-score. The model's effectiveness in identifying Parkinson's Disease from speech recordings is presented in the project's documentation.

