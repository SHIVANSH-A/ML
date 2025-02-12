# Text Summarization using T5 Transformer

## Overview
This project utilizes the T5 (Text-To-Text Transfer Transformer) model for text summarization. It provides a simple interface using `ipywidgets` in Jupyter Notebook to input text and generate a concise summary.

## Features
- User-friendly text input area for entering text to be summarized.
- Summarization button to process and generate the summary.
- Display of summarized text in a separate text area.
- Uses `T5-small` model from Hugging Face's Transformers library.

## Installation
Ensure you have Python installed along with the required dependencies. Install them using:
```bash
pip install transformers ipywidgets torch
```

## Usage
1. Run the script in a Jupyter Notebook.
2. Enter the text to be summarized in the provided input area.
3. Click the 'Summarize' button to generate a summary.
4. The summarized text will be displayed in the output text area.

## Code Explanation
- **Model Loading**: Loads the pre-trained `T5-small` model and tokenizer.
- **Summarization Function**: Processes and summarizes the input text using the model.
- **UI Components**: Uses `ipywidgets` to create an interactive interface.



