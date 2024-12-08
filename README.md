# Python_error_fixer

**The project is currently under development. The README will be updated as progress is made.**
The project aims to create a system based on Retrieval-Augmented Generation (RAG) to assist users with their Python programming errors/issues (similar to answers on StackOverflow). The target audience includes beginner programmers, schoolchildren, and students learning to program.

## Contents
- [Data Preprocessing](#data-preprocessing)
- [FAQ](#faq)
- [Project Team](#project-team)
- [Links](#links)

## Data Preprocessing
The [dataset](https://huggingface.co/datasets/TacoPrime/errored_python) was taken and processed. During processing, the data was divided into 4 categories: `prompt`, `input` (erroneous Python code), `explanation` (description of the error), and `correct_code`. Duplicates were removed, resulting in a final dataset of 7,095 data points. The data was saved in formats that are convenient for working with the RAG system (`csv` and `json`).

## FAQ
This section will include information on common errors when using the tool or attempting to reproduce experiments.

## Project Team
- [Michail Ivanov]() - ML Engineer
- [Viacheslav Siniaev](https://www.linkedin.com/in/vyacheslavsinyaev/) - ML Engineer

## Links
- [Raw Dataset](https://huggingface.co/datasets/TacoPrime/errored_python)
- [Preprocessed Datasets](https://drive.google.com/drive/folders/1vEvFF5a6vSkaRhjf0WylZPu9a6R5hIS0?usp=sharing)
