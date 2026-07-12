# 📰 Task 1 - News Topic Classifier Using BERT

## 📌 Objective

The objective of this project is to build a news topic classification model using the BERT (Bidirectional Encoder Representations from Transformers) model. The classifier predicts the category of a news article into one of four classes: **World**, **Sports**, **Business**, and **Sci/Tech**.

---

## 📂 Dataset

- **Dataset:** AG News Dataset
- **Source:** Hugging Face Datasets
- **Classes:**
  - World
  - Sports
  - Business
  - Sci/Tech

---

## 🛠 Technologies Used

- Python
- Google Colab
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Evaluate
- Gradio
- NumPy

---

## 🚀 Methodology

1. Loaded the AG News dataset.
2. Explored and analyzed the dataset.
3. Created a smaller subset for faster training.
4. Tokenized news articles using the BERT tokenizer.
5. Loaded the pre-trained **bert-base-uncased** model.
6. Fine-tuned the model for text classification.
7. Evaluated the model using Accuracy and F1-score.
8. Built a Gradio web application for live prediction.

---

## 📊 Results

| Metric | Value |
|--------|-------|
| Model | bert-base-uncased |
| Accuracy | **90.65%** |
| Weighted F1-Score | **90.62%** |
| Epochs | 2 |

---

## 💡 Features

- News Topic Classification
- Transfer Learning using BERT
- Hugging Face Transformers
- Interactive Gradio Interface
- Production-ready NLP Workflow

---

## ▶️ How to Run

1. Clone the repository.
2. Install the required packages.

```bash
pip install -r requirements.txt
```

3. Open the notebook in Google Colab or Jupyter Notebook.
4. Run all cells in order.
5. Launch the Gradio interface for live predictions.

---

## 📁 Project Structure

```
Task-1-News-Topic-Classifier-Using-BERT/
│
├── Task-1-News-Topic-Classifier-Using-BERT.ipynb
├── README.md
└── requirements.txt
```

---

## 👨‍💻 Author

**Muhammad Ahmad**

AI/ML Engineering Intern

DevelopersHub Corporation
