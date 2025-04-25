# NLP and LLM Learning Workspace

This repository contains a collection of Jupyter notebooks and resources for learning and experimenting with Natural Language Processing (NLP) and Large Language Models (LLMs). The project is organized into different subdirectories, each focusing on specific topics or tutorials.

## Project Structure

```
.gitignore
README.md
notebooks/
    huggingface_learning/
        datasets_tutorial.ipynb
    nlp_learning/
        tokenization.ipynb
    SQLDB_chain/
        experiment_001.ipynb
```

### Notebooks

1. **Hugging Face Learning**
   - `datasets_tutorial.ipynb`: Demonstrates how to use the Hugging Face `datasets` library to load and process datasets like WMT14 for machine translation tasks.

2. **NLP Learning**
   - `tokenization.ipynb`: Explores tokenization techniques using `spaCy` for English and French text, vocabulary building, and dataset preprocessing for translation tasks.

3. **SQLDB Chain**
   - `experiment_001.ipynb`: Experiments with the `langchain_community` library for SQL database tools, including error handling and debugging.

## Requirements

- Python 3.11 or higher
- Jupyter Notebook
- Required Python libraries:
  - `spacy`
  - `datasets`
  - `sqlalchemy`
  - `torch`
  - `langchain_community`

## Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd NLP_LLM_Coding
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Download `spaCy` language models:
   ```bash
   python -m spacy download en_core_web_sm
   python -m spacy download fr_core_news_sm
   ```

## Usage

- Open the Jupyter notebooks in the `notebooks/` directory to explore the tutorials and experiments:
  ```bash
  jupyter notebook
  ```

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- [Hugging Face](https://huggingface.co/) for the `datasets` library.
- [spaCy](https://spacy.io/) for NLP tools.
- [LangChain](https://www.langchain.com/) for SQL database tools.
