# Kazakh Text Normalization Dataset

## Overview
This dataset is designed for Kazakh text normalization at the **character level**. It consists of pairs of input and target words, where the input contains common incorrect spellings of Kazakh words (typically due to neglecting Kazakh-specific letters), and the target represents the correct form.

## Dataset Format
The dataset is structured in a CSV format with two columns:
- **`input`**: The misspelled or incorrectly formatted Kazakh word.
- **`target`**: The correct, normalized version of the word.

### Sample Data
| input       | target      |
|------------|------------|
| тилеймин   | тілеймін   |
| табигат    | табиғат    |
| апатынын   | апатының   |
| зардаптарын | зардаптарын |
| жоюга      | жоюға      |
| деп        | деп        |

> **Note:** Some words in Kazakh do not contain any specific Kazakh letters and remain unchanged in both columns.

## Usage
This dataset can be used for:
- **Character-level sequence-to-sequence models** for text normalization.
- **Neural machine translation (NMT) approaches** for spelling correction.
- **Rule-based or statistical models** for Kazakh text processing.

## Model Architecture
- A character-level recurrent **sequence-to-sequence** (seq2seq) model is used.

## Training & Evaluation
- Evaluating with standard NLP metrics: **BLEU**.

## Implementation
- **Language:** Python
- **Libraries:** numpy, pandas, TensorFlow/Keras


## Citation
If you use this dataset in your research or project, please cite:
```
@dataset{kazakh_text_normalization,
  title={Kazakh Text Normalization Dataset},
  author={Dana Tussupbekova},
  year={2025},
  description={A dataset for normalizing Kazakh words with incorrect spellings into their correct forms.}
}
```

## Contact
For any questions or contributions, feel free to reach out!



