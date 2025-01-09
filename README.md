# Q-AACD Dataset

Welcome to the **Q-AACD Dataset** repository! This dataset is designed for creating and analyzing English vocabulary learning materials, such as multiple-choice quizzes, aimed at improving language proficiency in educational and research contexts.

## Dataset Overview

The Q-AACD dataset includes:
- **ID**: A unique identifier for each question.
- **Target**: The vocabulary word that is the focus of the question.
- **Question**: A sentence with a blank space to be filled in with the correct answer.
- **Correct Answer**: The word that correctly fills the blank.
- **Distractor 1, 2, 3**: Incorrect options designed to challenge the learner.
- **D1, D2, D3**: Metadata flags for distractors (1 means the distractor should be changed).
- **Notes**: Additional notes for context or issues.

### Example Entry:
| ID | Target    | Question                                             | Correct Answer | Distractor 1 | Distractor 2 | Distractor 3 | Notes       |
|----|-----------|-----------------------------------------------------|----------------|--------------|--------------|--------------|-------------|
| 1  | adhere    | It is important to \<blank\> to the rules and guidelines. | adhere         | ignore       | oppose       | violate      |             |

## Use Cases
- Developing vocabulary quizzes for educational apps.
- Training AI models for natural language understanding and assessment.
- Conducting research on vocabulary acquisition and testing.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/discoursemarker/q-aacd.git
   ```
2. Load the dataset into your preferred programming environment (e.g., Python):
   ```python
   import pandas as pd
   data = pd.read_csv('Q-AACD_dataset.csv')
   print(data.head())
   ```
3. Customize and integrate the dataset into your application or research project.

## License
This dataset is released under the [MIT License](LICENSE).

## Contributions
We welcome contributions to improve the dataset, fix errors, or add new features. Please submit a pull request or open an issue to discuss your ideas.

## Contact
For questions or support, please contact [kyudai.uchida.lab[at]gmail.com].


