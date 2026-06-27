# 🤖 AI Chatbot with FLAN-T5 & Gradio

An intelligent chatbot built using **Google FLAN-T5-Large**, **Gradio**, and **SymPy**. The chatbot can answer general questions, explain concepts, solve mathematical expressions accurately, and provide step-by-step explanations for math problems.

---

## 🚀 Features

- 💬 General conversation using FLAN-T5-Large
- 📚 Definition and explanation of concepts
- ➗ Accurate mathematical calculations using SymPy
- 📝 Step-by-step mathematical explanations
- 🌐 Interactive web interface using Gradio
- ⚡ GPU support (if CUDA is available)

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Transformers (Hugging Face)
- Google FLAN-T5-Large
- SymPy
- Gradio
- Regular Expressions (re)

---

## 📂 Project Structure

```
.
├── chatbot.ipynb        # Main notebook
├── README.md            # Project documentation
```

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/chatbot-project.git
cd chatbot-project
```

Install the required packages:

```bash
pip install transformers torch accelerate gradio sympy
```

---

## ▶️ Running the Project

Open the notebook:

```bash
jupyter notebook chatbot.ipynb
```

or

```bash
jupyter lab
```

Run all cells.

The Gradio interface will launch automatically and provide a local URL in your browser.

---

## 💡 How It Works

### 1. General Chat

The chatbot uses the **Google FLAN-T5-Large** language model to answer user questions naturally.

### 2. Mathematical Solver

For mathematical expressions:

- Detects mathematical input
- Solves it using SymPy
- Produces accurate results
- Generates step-by-step explanations

### 3. Definition Questions

The chatbot identifies questions such as:

- What is AI?
- Define Machine Learning.
- Explain Python.

It then generates informative responses using the language model.

---

## 📸 Interface

The application provides an interactive Gradio web interface where users can:

- Ask questions
- Solve mathematical problems
- Receive detailed explanations
- Continue conversations naturally

---

## 📋 Example Questions

```
What is Artificial Intelligence?

Define Machine Learning.

Explain Cloud Computing.

25 + 75

(15 * 8) / 4

Solve x² + 5x + 6

Explain how to solve 45 × 12.
```

---

## 📌 Requirements

- Python 3.9+
- Internet connection (for first model download)
- Approximately 3–5 GB RAM (more recommended for FLAN-T5-Large)
- Optional GPU for faster inference

---

## 🔮 Future Improvements

- Voice input and speech output
- Conversation memory
- Dark mode interface
- Chat history export
- PDF question answering
- Image understanding (multimodal support)
- Deployment on Hugging Face Spaces or Streamlit Cloud

---

## 👨‍💻 Author

**Keerthy K**

B.Sc. Computer Science Student

---

## 📄 License

This project is licensed under the MIT License.
