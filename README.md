# 🧠 Mistral Personality Chatbot

Chat with a powerful LLM in different personalities — from Shakespeare to Stand-up Comedian. Built using **Gradio** and **Mistral 7B Instruct**, this chatbot runs locally with GPU support and supports math, memory, and personality-based conversations.

---

## 🚀 Features

- 🗣️ Multiple personalities (Default, Comedian, Wizard, Shakespeare, Motivator)  
- ⚡ Powered by [Mistral-7B-Instruct-v0.1](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1)  
- 🔐 Token-based access for gated model loading  
- 💻 Runs locally on Colab or your own GPU  
- 🌐 Gradio-based web UI with a custom theme  
- 🔄 Memory for multi-turn conversation

---

## 🛠️ Setup Instructions

1. **Clone this repo**  
   ```bash
   git clone https://github.com/yourusername/mistral-chatbot.git
   cd mistral-chatbot
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run on Colab** (recommended if you don’t have a local GPU)  
   - Upload the notebook or open this in Colab: `[link to your Colab notebook]`  
   - Paste your HuggingFace token when prompted

4. **Run Locally** (GPU required)  
   ```bash
   python app.py
   ```

---

## 🔑 HuggingFace Token Required

Since the Mistral model is gated, you need a [HuggingFace account](https://huggingface.co/) and an access token.

---

## 📁 Files in This Repo

- `app.py` — Main chatbot code  
- `requirements.txt` — Python dependencies  
- `README.md` — You’re here  
- `LICENSE` — MIT License for open usage  
- (Optional) `colab_notebook.ipynb` — Ready-to-use Colab version

---

## ✨ Contributing

Want to add a new personality? Better memory? UI themes?  
Pull requests are welcome! Open an issue first to discuss.



---

## 📜 License

MIT — feel free to use, share, and build on it.
