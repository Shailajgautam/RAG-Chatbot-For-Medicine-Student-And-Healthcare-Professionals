
# RAG-Chatbot

**Author:** Shailaj Gautam

RAG-Chatbot is an advanced conversational AI platform designed for **MBBS students and healthcare professionals**. It leverages **Retrieval-Augmented Generation (RAG)** to provide precise, context-aware answers by combining large language models with structured and unstructured data sources.

---

## Features

* **Knowledge Base Chat:** Query the chatbot’s curated medical knowledge base.
* **PDF Upload Chat:** Upload PDF documents and interact with their content.
* **URL-Based Chat:** Provide a URL, and the chatbot will extract and answer questions from the linked content.
* **Combined Mode:** Seamlessly integrate all modes for a unified chat experience.

---

## Key Contributions

* Engineered a **RAG system** using **LLMs and FAISS**, enabling dynamic querying across **100+ document chunks** from PDFs, URLs, and internal knowledge bases.
* Applied **NLP, semantic search, and vector similarity techniques** to ensure accurate, context-aware information retrieval.
* Built a modular and scalable architecture, allowing easy integration of additional data sources.

---

## Tech Stack

* **[LangChain](https://www.langchain.com/):** Framework for building LLM-powered applications.
* **[Hugging Face Transformers](https://huggingface.co/transformers/):** Fine-tuning and deployment of language models.
* **[PyTorch](https://pytorch.org/):** Deep learning library for model training.
* **[FAISS](https://github.com/facebookresearch/faiss):** Efficient similarity search and vector indexing.
* **[ChainLit](https://chainlit.io/):** Framework for chatbot interaction.

---

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Shailajgautam/RAG-Chatbot.git
cd RAG-Chatbot
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Chatbot

```bash
chainlit run model.py -w
```

### 4. Interact

Follow the prompts in your browser and start chatting with RAG-Chatbot!

---

## Future Enhancements

* Add **multi-language support** for diverse medical audiences.
* Integrate **real-time clinical data retrieval**.
* Improve **model fine-tuning** for specialized medical knowledge.

---

**🚀 Ready to explore? Dive in and start interacting with RAG-Chatbot today!**

---

