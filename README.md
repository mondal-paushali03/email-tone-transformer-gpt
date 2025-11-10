# ✉️ Email Tone Transformer — AI-Powered Email Rewriter

Transform your everyday emails into professional, friendly, or polished versions using open-source GenAI models — **no API keys or paid tokens required**.

This lightweight app runs on **TinyLlama 1.1B Chat (v0.6)** locally and uses **Gradio** for an interactive interface.  
Perfect for students, freelancers, and professionals who want to improve their email communication style with one click.

---

## 🚀 Live Demo
[🔗 Try on Hugging Face Spaces](https://huggingface.co/spaces/paushali03/email-tone-transformer)

---

## 🧠 Overview

The **Email Tone Transformer** rewrites raw emails into a variety of tones without changing their original meaning.  
It runs completely offline (no OpenAI or Hugging Face API calls) and uses a compact LLM that fits within Colab or free CPU hosting limits.

### ✨ Features
- 🧾 **7 tone options:** Formal, Friendly, Polite-Assertive, Short-Direct, Managerial, Complaint, Apology  
- ⚙️ **Adjustable creativity:** control text style with a temperature slider  
- 🔁 **Compare all tones** in a single click  
- 📋 **One-click copy button** for easy reuse of rewritten emails  
- 💾 **Download outputs** as `.txt` or `.md` files  
- 💡 100% Free & Token-Free — works on Hugging Face Spaces or Google Colab

---

## 🧩 Example

**Input:**
<img width="1821" height="920" alt="image" src="https://github.com/user-attachments/assets/658c9a89-bd00-4b49-a1e2-aa337c5799fc" />


**Formal Tone Output:**
<img width="1817" height="638" alt="image" src="https://github.com/user-attachments/assets/f2a4678d-0f9d-4fb3-bac5-7bb12ec1da2a" />


---

## ⚙️ Setup

### 🪜 Run Locally or on Colab
```bash
!git clone https://github.com/your-username/email-tone-transformer.git
cd email-tone-transformer
pip install -r requirements.txt
python app.py
```
---
## 🪜 Deploy on Hugging Face Spaces

1. **Create a new Space**
   - Go to [Hugging Face Spaces](https://huggingface.co/spaces)
   - Choose **SDK:** Gradio · **Hardware:** CPU Basic (Free)
   - Name it `email-tone-transformer` and set **Visibility:** Public

2. **Upload Files**
   - `app.py`
   - `requirements.txt`

3. **Wait for Build**
   - Spaces auto-installs dependencies and launches your app in a few minutes.

---

### 🧱 Requirements

```bash
transformers>=4.38.0
accelerate>=0.26.0
sentencepiece
gradio>=4.29.0
torch>=2.1.0
```
---
## 🧠 Model Info

- **Model:** [TinyLlama/TinyLlama-1.1B-Chat-v0.6](https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v0.6)  
- **Type:** Instruction-tuned open LLM  
- **Size:** 1.3B parameters  
- **Runs On:** Free CPU / Colab (8 GB RAM works perfectly)

---

## 💬 Feedback & Contributions

Pull requests and ideas are welcome!  
If you use this project, please ⭐ star the repo and share your feedback 🙌
