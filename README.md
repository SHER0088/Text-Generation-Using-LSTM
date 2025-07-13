# 🧠 Text Generation Using LSTM – Robert Frost Poetry 🌲

This project demonstrates a text generation model trained on the poetic works of Robert Frost using an LSTM-based Recurrent Neural Network in Python and TensorFlow. The model learns poetic patterns and generates stylistically similar text from input prompts.

---

## 📌 Project Highlights

- 📚 Dataset: [Robert Frost Poetry Collection](https://www.kaggle.com/datasets/archanghosh/robert-frost-collection)
- 📦 Framework: TensorFlow / Keras
- 🔢 Model: Embedding → LSTM → Dense(softmax)
- 📈 Metrics: Accuracy ~ 83.54%, Perplexity ≈ 2.03
- 📜 Output: Generates creative poetic text from user-defined prompts

---

## 📂 Directory Structure

```
text-generation-robert-frost/
├── robert_frost_collection.csv       # Dataset
├── text_generation_lstm.ipynb        # Colab-ready notebook
├── robert_frost_text_generator.h5    # Trained model (HDF5)
├── prompt_outputs.txt                # Sample outputs
├── samples/
│   └── wordcloud.png                 # Word cloud of corpus
└── README.md                         # This file
```

---

## 🚀 Quick Start

### 📍 Step 1: Clone the Repo
```bash
git clone https://github.com/your-username/text-generation-robert-frost.git
cd text-generation-robert-frost
```

### 📍 Step 2: Install Requirements
```bash
pip install -r requirements.txt
```

### 📍 Step 3: Run in Google Colab
Open the notebook:
```
text_generation_lstm.ipynb
```

Follow the steps inside to:
- Load dataset via Kaggle API
- Preprocess data
- Train the LSTM model
- Generate poetry using your own prompts

---

## 🧪 Evaluation Metrics

| Metric             | Value         |
|--------------------|---------------|
| Final Accuracy     | 83.54%        |
| Final Loss         | 0.7067        |
| Perplexity Score   | ≈ 2.03        |

---

## ✨ Sample Outputs

```text
Prompt: "the woods are"
Generated: the woods are dark and deep i have miles to go
```

---

## 🙋‍♂️ Author

**Mayank Singh**  
MCA Graduate, Central University of Himachal Pradesh  
[LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com/your-username)
