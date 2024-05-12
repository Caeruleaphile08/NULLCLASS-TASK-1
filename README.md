# NULLCLASS TASK-1 (Machine Translation MModel)

This script demonstrates how to perform translation from English to French using the Hugging Face Transformers library. It utilizes a pre-trained sequence-to-sequence model (`Helsinki-NLP/opus-mt-en-fr`) for translation.

# Installation

If cloning is required use the below link for cloning.

- Clone the repository to your local machine:

    ```
    git clone https://github.com/Caeruleaphile08/NULLCLASS-TASK-1.git
    ```

- Install the required dependencies:

    ```
    pip install transformers
    ```
# Usage

The script will load the pre-trained tokenizer and model, translate sentences from English to French using " BEAM SEARCH DECODING ", and save the translated dataset to a CSV file.

# Requirements

- Python 3.x
- `transformers` library
- `pandas` library
  
# Dataset 

The dataset used for translating English to French is loaded from a CSV file containing English and French parallel corpus. You can find the dataset [here]([link_to_dataset](https://www.kaggle.com/datasets/adewoleakorede/english-french-translation)).


# Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.
