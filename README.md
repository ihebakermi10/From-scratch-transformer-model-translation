

# Multilingual NLP Translation Models with Name Similarity System

## Overview

This project develops a state-of-the-art multilingual Natural Language Processing (NLP) translation system utilizing the transformer architecture, primarily powered by Hugging Face and PyTorch. Our system is designed to handle multiple languages efficiently, featuring a unique proper name similarity component that enhances the accuracy of name translation across various languages.

The model is built as a self-learning system using transfer learning techniques, enabling continuous improvement as it processes more data. We leverage Azure ML for scalable training and deployment, MongoDB Atlas for efficient data storage and retrieval through Vector Search, and the Levenshtein algorithm to enhance our name similarity checks.

## Features

- **Transformer Architecture**: Utilizing cutting-edge transformer models for high accuracy and context-aware translations.
- **Hugging Face Integration**: Implementation of pre-trained models from Hugging Face for robust performance in multiple languages.
- **Name Similarity System**: A custom system to handle the translation of proper names with higher accuracy using the Levenshtein distance metric.
- **Self-Learning Capabilities**: Employing transfer learning methods to adapt and improve with every translation task.
- **Multilingual Support**: Designed to support numerous languages, facilitating global communication.
- **Technology Stack**: Azure ML, PyTorch, NLP, Large Language Models (LLM), Python, MongoDB Atlas, and regular expressions (re).

## Getting Started

To get started with this project, clone the repository and set up your environment with the required dependencies.

```bash
git clone https://github.com/[your-github-username]/[your-repo-name]
cd [your-repo-name]
# Install dependencies
pip install -r requirements.txt
```

## Usage

For a quick demonstration, you can run the following script after setting up your environment:

```python
from translator import translate
print(translate("Your text here", target_language='fr'))
```

## Contributing

We welcome contributions from the community, whether they are feature requests, improvements, or bug fixes. Please follow the standard fork-and-pull request workflow to contribute.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

