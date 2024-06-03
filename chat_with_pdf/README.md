## 📄 Chat with PDF 

LLM app with RAG to chat with PDF in just 30 lines of Python Code. The app uses Retrieval Augmented Generation (RAG) to provide accurate answers to questions based on the content of the uploaded PDF.

### Features

- Upload a PDF document
- Ask questions about the content of the PDF
- Get accurate answers using RAG and the selected LLM

### How to get Started the Ollama (local hosted llama3) way

Assumptions: 
Ollama is already installed and running and llama3 model has been downloaded.

If not, on a M1/2/3 Mac - "brew install ollama", "ollama pull llama3:instruct" should do the trick.

1. Clone the GitHub repository

```bash
git clone https://github.com/Shubhamsaboo/awesome-llm-apps.git
```

2. Install the required dependencies

```bash
pip install -r requirements.txt
```

3. Run the Streamlit App

```bash
streamlit run chat_pdf_llama3.py
```

Note: a better way would be to use miniconda / miniforge (for Mac users), and create a separate environment (with python=3.10) for running the apps in this repo.

### How to get Started the OpenAI way

1. Clone the GitHub repository

```bash
git clone https://github.com/Shubhamsaboo/awesome-llm-apps.git
```
2. Install the required dependencies

```bash
pip install -r requirements.txt
```
3. Get your OpenAI API Key

- Sign up for an [OpenAI account](https://platform.openai.com/) (or the LLM provider of your choice) and obtain your API key.

4. Run the Streamlit App
```bash
streamlit run chat_pdf.py
```

### Interactive Application Demo
https://github.com/Shubhamsaboo/awesome-llm-apps/assets/31396011/12bdfc11-c877-4fc7-9e70-63f21d2eb977

