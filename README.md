# Machine-translation-with-Flores200-devtest
# Machine Translation Model with GPT-4o Mini

## Overview
This project implements a machine translation model leveraging the FLORES-200 dataset to translate sentences between English and several Indian languages, including Hindi, Marathi, Gujarati, Bengali, Telugu, and Tamil. The model utilizes **GPT-4o Mini** for generating translations and evaluates their quality using **BLEU scores**, a metric that assesses the accuracy of translations by comparing them to reference translations.

## Features
- **Dataset**: Utilizes the FLORES-200 dataset for multilingual translation tasks.
- **Languages**: Supports translations for English to Hindi, Marathi, Gujarati, Bengali, Telugu, and Tamil.
- **Random Sampling**: Implements random sampling of sentences for balanced evaluation.
- **Translation Evaluation**: Employs GPT-4 Mini to generate translations and assess their accuracy using BLEU scores, including smoothing techniques to ensure meaningful results.
- **Output Generation**: Saves evaluation results and parallel datasets in Excel format for easy analysis.

## Installation
To run this project, ensure you have the following libraries installed:
```bash
pip install pandas openai nltk
```
## Usage
1. Load the development test files.
2. Generate random samples from the dataset.
3. Evaluate the translations using the GPT-4 Mini model.
4. Save the evaluation results to Excel files for further analysis.

