# 🧠 LLM from Scratch

This project is a minimal and educational implementation of a Generative Pre-trained Transformer (GPT) model, inspired by the paper *“Attention is All You Need”* and projects like Karpathy's `minGPT`.

The goal is to build a GPT-style language model **entirely from scratch**, without relying on high-level libraries like HuggingFace. This serves as a hands-on exercise to understand the inner workings of LLMs — including tokenization, transformer blocks, attention mechanisms, and training dynamics.

---

## 🚀 Features

- Character-level tokenizer  
- Custom embedding layers  
- Multi-head self-attention  
- Layer normalization and residual connections  
- GPT-style decoder-only transformer architecture  
- Training loop using cross-entropy loss  
- Sample generation from trained model

---
 

## 📁 Repository Structure

`````

LLM_from_scratch/
├── gpt_from_scratch.ipynb   # Main notebook: build and train GPT step by step
├── README.md     # Project overview and documentation

 `````

---

## 🛠️ Requirements

- Python 3.8+  
- PyTorch  
- NumPy  
- tqdm (for progress bar)

Install dependencies:

```bash
pip install torch numpy tqdm
```
🧪 How to Run

Clone the repo:
```
git clone https://github.com/prapti2024/LLM_from_scratch.git
cd LLM_from_scratch
```
Open the Jupyter notebook:
```
jupyter notebook gpt_from_scratch.ipynb
```

Run cells step-by-step to build the model, train it on a small dataset (like Shakespeare), and generate text samples.

---
## 📊 Training Example

The model is trained on a small text corpus using character-level prediction. Here's an example of generated text after training:

```css
Whathasth be thas areson all,
Yoe milde sape spank bores.
```
(Yes, it’s gibberish, but it demonstrates learned patterns of structure and punctuation!)

---

## 📚 Inspiration

Sebastian Raschka
(Build a LLM from Scratch)

---

## ✅ TODO

Add positional encodings (sinusoidal/trainable)

Switch to BPE or WordPiece tokenizer

Train on larger datasets

Save and reload model checkpoints

---

## 🧑‍💻 Author

Prapti Dahal

GitHub

---
