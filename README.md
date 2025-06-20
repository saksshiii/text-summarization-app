# text-summarization-app
=======
# Text Summarization using Transformers

## Overview
This project demonstrates text summarization using the T5 transformer model from Hugging Face.

## Features
- Summarize long-form text into short summaries
- Streamlit app interface
- Modular code structure

## How to Run
1. Install dependencies:
```
pip install -r requirements.txt
```
2. Run the Streamlit app:
```
streamlit run streamlit_app/app.py
```

## Model Used
- [`t5-small`](https://huggingface.co/t5-small)

## Folder Structure
- `src/`: Model loading and summarization logic
- `streamlit_app/`: Streamlit interface
- `data/`, `outputs/`: Optional dataset and outputs storage