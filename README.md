

# Multilingual NLP Translation Models 

## Overview

This project develops a state-of-the-art multilingual Natural Language Processing (NLP) translation system utilizing the transformer architecture, primarily powered by Hugging Face and PyTorch. Our system is designed to handle multiple languages efficiently, featuring a unique proper .

The model is built as a self-learning system using transfer learning techniques, enabling continuous improvement as it processes more data. We leverage Azure ML for scalable training and deployment, MongoDB Atlas for efficient data storage and retrieval through Vector Search, and the Levenshtein algorithm to enhance our name similarity checks.


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
print(translate("Your text here"))
```



