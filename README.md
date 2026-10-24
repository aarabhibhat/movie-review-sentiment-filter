# Movie Review Sentiment Filter

## Project Overview
This project classifies movie reviews as positive or negative using a fine-tuned GPT-2 sequence classification model.

## Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Gradio
- Google Colab

## Dataset
IMDb movie reviews dataset from Hugging Face:
https://huggingface.co/datasets/stanfordnlp/imdb

## Model
GPT-2 fine-tuned for binary sentiment classification.

## Results
- Baseline test accuracy: 50.00%
- Fine-tuned test accuracy (keep-beginning): 56.67%
- Fine-tuned test accuracy (keep-ending): 63.33%
- Validation accuracy: 76.67%

Results are based on a small, balanced sample of 200 reviews. Performance may vary on larger datasets and real-world reviews.

## How to Run
1. Open the notebook in Google Colab.
2. Install the required dependencies if prompted.
3. Run the notebook cells in order.
4. Launch the Gradio interface to enter a review and view its predicted sentiment.
