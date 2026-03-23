# 🚀 Transformer Architecture – Interactive Visual Explorer

<p align="center">
  <b>An interactive platform to visualize and understand the internal mechanics of the Transformer architecture used in modern LLMs such as GPT and BERT.</b>
</p>

<p align="center">
  🌐 <a href="https://transformer-lime.vercel.app/" target="_blank"><b>Live Demo</b></a>
</p>

---
## 📖 Overview

Transformer Visual Explorer is a **browser-based interactive learning platform** that demonstrates how the Transformer model works internally.
Instead of only presenting theory, this platform converts **mathematical operations into interactive visual simulations**, allowing users to explore attention mechanisms, positional encoding, and encoder–decoder interactions step-by-step.

It helps learners build **deep intuition about attention**, which is the core mechanism behind modern Large Language Models.

---

## ✨ Key Features

- Interactive Self-Attention visualization  
- Multi-Head Attention simulation  
- Positional Encoding heatmap (Sine–Cosine formulation)  
- Encoder architecture breakdown  
- Decoder architecture breakdown  
- Masked Self-Attention explanation  
- Cross-Attention conceptual visualization  
- Mathematical formulas with implementation logic  
- Fully client-side execution (no backend required)  

---

## 🧠 Concepts Implemented

This platform demonstrates the complete Transformer pipeline:

- Token Embeddings  
- Positional Encoding  
- Scaled Dot-Product Attention  
- Multi-Head Attention  
- Masked Self-Attention  
- Cross Attention  
- Residual Connections  
- Layer Normalization  
- Position-wise Feed Forward Network  
- Encoder Stack  
- Decoder Stack  

---

## 🧩 Transformer Architecture Flow

Input Tokens
↓
Embedding Layer
↓
Positional Encoding
↓
Encoder Stack
├── Multi-Head Self Attention
├── Add & LayerNorm
├── Feed Forward Network
└── Add & LayerNorm
↓
Decoder Stack
├── Masked Self Attention
├── Cross Attention
├── Feed Forward Network
└── LayerNorm
↓
Output Probabilities

---

## 🔬 Core Attention Formula

Scaled Dot-Product Attention:

Attention(Q, K, V) = softmax((QKᵀ) / √dₖ) V


Implementation includes:

- Linear projections for Query, Key, and Value  
- Dot-product similarity computation  
- Scaling by √dₖ for stability  
- Softmax normalization  
- Weighted aggregation with Value vectors  
- Multi-head splitting and concatenation  

---

## 📸 Screenshots
<img width="1919" height="897" alt="image" src="https://github.com/user-attachments/assets/30c25c7a-0e6a-4fd5-b888-9164a67ea7a5" />


<img width="1919" height="901" alt="image" src="https://github.com/user-attachments/assets/4e438528-f271-47e1-89f2-47d083f37c23" />


<img width="1919" height="904" alt="image" src="https://github.com/user-attachments/assets/4cf3e816-3b47-4c9d-8a8e-f60865c2ff47" />


<img width="1919" height="907" alt="image" src="https://github.com/user-attachments/assets/8462f57f-bb92-42f5-9b02-cc7f6c4158c4" />

---

## 🛠 Tech Stack

| Layer | Technology |
|------|------------|
| Frontend | HTML5, CSS3, JavaScript |
| Visualization | Canvas / SVG / DOM |
| Architecture Logic | Custom JavaScript |
| Deployment | Vercel |
| Hosting | Static Web App |

---

## 📂 Project Structure
Transformer-visual-explorer/
│
├── index.html
├── style.css
├── script.js
├── assets/
├── screenshots/
└── README.md


---

## 🌐 Deployment

Live Application:  
https://transformer-lime.vercel.app/

Hosted using Vercel with:

- Automatic GitHub deployment  
- HTTPS enabled  
- Global CDN  
- Fast static serving  

---

## 🎯 Purpose

Transformers involve complex matrix operations and abstract mathematical concepts.  
This project makes those concepts **visual, interactive, and intuitive**, helping learners move from theory to real understanding.

---

## 🚀 Future Improvements

- Real text input attention visualization  
- Token-level attention heatmaps  
- PyTorch integration  
- Training visualization  
- Interactive parameter tuning  

---
GitHub:  
https://github.com/Pushprajgadhvi/

---



