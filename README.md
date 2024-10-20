# Machine-translation-with-Flores200-devtest
Machine Translation Model with GPT-4 Mini
Overview
This project implements a machine translation model leveraging the FLORES-200 dataset to translate sentences between English and several Indian languages, including Hindi, Marathi, Gujarati, Bengali, Telugu, and Tamil. The model utilizes GPT-4 Mini for generating translations and evaluating their quality through BLEU scores.

Features
Dataset: Utilizes the FLORES-200 dataset for multilingual translation tasks.
Languages: Supports translations for English to Hindi, Marathi, Gujarati, Bengali, Telugu, and Tamil.
Random Sampling: Implements random sampling of sentences for balanced evaluation.
Translation Evaluation: Employs GPT-4 Mini to generate translations and assess their accuracy using BLEU scores, including smoothing techniques to ensure meaningful results.
Output Generation: Saves evaluation results and parallel datasets in Excel format for easy analysis.
Installation
To run this project, ensure you have the following libraries installed:

bash
Copy code
pip install pandas openai nltk
Usage
Load the development test files.
Generate random samples from the dataset.
Evaluate the translations using the GPT-4 Mini model.
Save the evaluation results to Excel files for further analysis.
Contributing
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

License
This project is licensed under the MIT License. See the LICENSE file for more details.
