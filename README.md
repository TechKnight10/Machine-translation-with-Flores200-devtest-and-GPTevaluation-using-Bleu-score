# Machine-translation-with-Flores200-devtest
# Machine Translation Model with GPT-4 Mini

## Overview
This project implements a machine translation model leveraging the FLORES-200 dataset to translate sentences between English and several Indian languages, including Hindi, Marathi, Gujarati, Bengali, Telugu, and Tamil. The model utilizes GPT-4 Mini for generating translations and evaluating their quality through BLEU scores.

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



### How to Implement the License Section
1. **License Header**: Add a section titled `## License` to your README.
2. **Brief Description**: State that your project is licensed under a specific license (e.g., "This project is licensed under the MIT License").
3. **Link to LICENSE File**: Provide a link to the LICENSE file in your repository using Markdown syntax: `[LICENSE](LICENSE)`.
4. **Optional License Text**: If you prefer, you can include a brief excerpt of the license text directly in the README, but it’s usually cleaner to keep that in the LICENSE file and link to it.

### Example License Section
```markdown
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
