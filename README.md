
# 🤖 Generative AI Chatbot using DialoGPT & Gradio

A conversational AI chatbot built using Hugging Face's `DialoGPT-medium` model and deployed with a web interface via `Gradio`. This project demonstrates the real-world application of Generative AI in building intelligent, interactive systems—specifically, a healthcare assistance chatbot prototype.

---

## 📌 Project Overview

This chatbot project is part of an academic industry training report titled:

**"Generative AI: Principles, Challenges, and Case Studies in Conversational AI"**  
🔸 **Author**: Venkatesh Uttam  
🔸 **Semester**: VIII, 2024-2025  
🔸 **University**: KLE Technological University, Hubballi  
🔸 **Guide**: Mrs. Preeti Pilai  

---

## 🎯 Objectives

- Understand and apply Transformer-based generative models.
- Build a chatbot for basic healthcare-related interactions.
- Implement a web-based interface for user-friendly access.
- Explore limitations, performance, and ethical implications of Generative AI.

---

## 🧠 Technologies Used

| Technology           | Purpose                                                  |
|----------------------|----------------------------------------------------------|
| `Python`             | Core scripting and control logic                         |
| `Hugging Face Transformers` | Pre-trained NLP models and tokenizers               |
| `DialoGPT-medium`    | GPT-2-based conversational model by Microsoft            |
| `PyTorch`            | Deep learning framework for inference                    |
| `Gradio`             | Rapid web UI development                                 |

---

## 🧩 Features

- ⚡ **Real-time AI responses** using a pre-trained language model.
- 🧠 **Contextual understanding** of user input (within session).
- 🌐 **Web-based interface** accessible via browser.
- 🚀 **Lightweight and scalable** architecture.
- 📉 **Handles errors and invalid input** gracefully.

---

## 🏗️ System Architecture

1. **User Input**: Provided via Gradio UI.
2. **Tokenization**: Input text tokenized with special EOS marker.
3. **Model Inference**: DialoGPT-medium predicts next best tokens.
4. **Decoding**: Tokens are converted to human-readable text.
5. **Output**: Displayed back to the user in the Gradio interface.

---

## 🧪 Sample Interaction

```
User: Hello, how are you?
Bot: I'm good, how are you?
```

```
User: What’s the weather like today?
Bot: It's been pretty nice.
```

---




## 🔍 Insights & Challenges

- Generative AI offers fluent, flexible responses—but lacks real-time or persistent memory.
- Performance tuning and error handling are crucial in healthcare applications.
- Ethical concerns like hallucination and bias must be mitigated for trustworthy AI.

---

## 🔮 Future Scope

- 📚 Contextual memory for long conversations
- 🗣️ Voice input and TTS output (multimodal interface)
- 🌐 Cloud deployment for wider accessibility
- 🌎 Multilingual support
- 🛡️ Security enhancements for sensitive data

---

## 📜 License

This project is for academic use under [MIT License](https://opensource.org/licenses/MIT).

---

## 🙏 Acknowledgments

- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [Gradio](https://www.gradio.app/)
- KLE Technological University, School of ECE
