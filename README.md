# 🔍 **Zeteo**

### *Seek. Understand. Respond.*

Zeteo is a lightweight, context-aware AI chatbot built using **LangChain**, **Hugging Face models**, and a **Gradio** web interface.
It focuses on smooth conversational flow, memory retention, and a simple architecture that’s easy to modify and extend.

---

## ✨ Features

* **Contextual Memory**
  Remembers previous user messages to deliver connected, human-like responses.

* **LangChain-Powered Pipeline**
  Uses Prompt Templates, ConversationBufferMemory, and model chaining for modular design.

* **Hugging Face LLM Support**
  Works with open-source models like Mistral-7B, Llama-2, etc.

* **Clean Gradio UI**
  Instant browser-based chat interface.

* **Fully Extensible**
  Add RAG, custom prompts, vector search, API integrations, or domain-based fine-tuning.


---

## 🧠 How Zeteo Works

1. Loads an open-source LLM via Hugging Face.
2. Wraps it inside a LangChain LLM wrapper.
3. Uses a structured **PromptTemplate** for consistent responses.
4. Maintains history using **ConversationBufferMemory**.
5. Streams responses in real time through Gradio.

The goal is simplicity + extensibility without unnecessary complexity.

---

## 🔮 Future Enhancements

* Add Retrieval-Augmented Generation (RAG)
* Use a vector DB like Pinecone / Chroma
* Integrate voice input/output
* Deploy on Hugging Face Spaces or AWS
* Add chat analytics and logging
* Role-based system prompts


## 🙌 Acknowledgements

Built using LangChain, Gradio, and Hugging Face open-source models.
Inspired by modern conversational AI system design patterns.

