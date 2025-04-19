# Final_Project-stats507_Fine-Tuning-DistilBERT-on-IMDB# Final Project – STATS 507  
**Fine-Tuning DistilBERT on IMDB Dataset for Sentiment Classification**

This project fine-tunes a pre-trained [DistilBERT](https://huggingface.co/distilbert-base-uncased) model on the IMDB sentiment analysis dataset using the Hugging Face `transformers` library and PyTorch.

## 📁 Notebook
You can view the notebook here:  
🔗 [Final_Project.ipynb (via nbviewer)](https://nbviewer.org/github/Windyzsy/Final_Project-stats507_Fine-Tuning-DistilBERT-on-IMDB/blob/main/Final_Project.ipynb)

> If GitHub preview fails to render the notebook properly, please use the nbviewer link above.

## 🧠 Model Details
- **Base model**: distilbert-base-uncased
- **Dataset**: IMDB (binary sentiment classification)
- **Training epochs**: 5
- **Optimizer**: AdamW
- **Loss function**: Weighted CrossEntropyLoss (to address class imbalance)
- **Evaluation metrics**: Accuracy, Training & Validation Loss tracking

## 📊 Output
The training process tracks:
- Training loss
- Validation loss
- Validation accuracy  
... all plotted over epochs.

## 🧪 Dependencies
```bash
pip install transformers datasets torch scikit-learn matplotlib
