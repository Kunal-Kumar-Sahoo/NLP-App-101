# NLP 101

## Overview

This repository contains a Python-based web application for Natural Language Processing (NLP) tasks. The application leverages various pre-trained transformer models to perform a range of NLP tasks. Users can interact with the app through a web interface to perform tasks such as text summarization, named entity recognition, sentiment analysis, question answering, and text completion.

## Dependencies

Before running the application, ensure you have the following dependencies installed:

- [Streamlit](https://streamlit.io/): A Python library for creating web applications.
- [tqdm](https://github.com/tqdm/tqdm): A fast, extensible progress bar for loops and processes.
- [pandas](https://pandas.pydata.org/): A popular data manipulation library for Python.
- [transformers](https://huggingface.co/transformers/): A library by Hugging Face that provides pre-trained NLP models.
- [spacy](https://spacy.io/): An NLP library for text processing and entity recognition.
- [spacy-streamlit](https://github.com/explosion/spacy-streamlit): A Streamlit extension for visualizing spaCy NER results.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Kunal-Kumar-Sahoo/NLP-App-101.git
   cd NLP-App-101
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the spaCy English language model:

   ```bash
   python -m spacy download en_core_web_sm
   ```

## Usage

To run the NLP web application, execute the following command in your terminal:

```bash
streamlit run app.py
```

This will launch the application in your default web browser. You can then interact with the app using the provided web interface.

## Features

### 1. Text Summarization

- Select "Summarizer" from the menu.
- Enter the text you want to summarize in the text area.
- Specify the number of words you want in the summary.
- Click the "Generate Summary" button to receive a summarized version of the input text.

### 2. Named Entity Recognition (NER)

- Select "Named Entity Recognition" from the menu.
- Enter the text you want to analyze in the text area.
- Click the "Analyze Text" button to extract and visualize named entities in the text.

### 3. Sentiment Analysis

- Select "Sentiment Analysis" from the menu.
- Enter the text you want to analyze in the text area.
- Click the "Analyze Sentiment" button to determine whether the text has a positive, negative, or neutral sentiment.

### 4. Question Answering

- Select "Question Answering" from the menu.
- Enter the context and a question related to the context in the respective text areas.
- Click the "Find Answer" button to obtain an answer to your question based on the provided context.

### 5. Text Completion

- Select "Text Completion" from the menu.
- Enter an incomplete text in the text area.
- Click the "Complete Text" button to generate a completion for the input text.

## About NLP

Natural Language Processing (NLP) is a subfield of Artificial Intelligence (AI) that focuses on enabling computers to understand, interpret, and generate human language. NLP tasks include text summarization, sentiment analysis, entity recognition, question answering, and more. This web application demonstrates the capabilities of pre-trained NLP models in performing these tasks.

## Acknowledgments

This application utilizes pre-trained transformer models from Hugging Face's Transformers library and the spaCy library for named entity recognition.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as per the license terms.

For any questions or issues, please contact [here](mailto:kunal.sahoo2003@gmail.com).

Enjoy exploring the NLP Web App!
