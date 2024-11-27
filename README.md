## Local PDF Chat App featuring Streamlit, Ollama, Langchain, and Mistral 7B LLM

A chatbot that can respond to inquiries regarding a PDF file is known as a PDF chatbot. It can accomplish this by first comprehending the user's question using a large language model (LLM) and then looking through the PDF file for pertinent information. The application creates responses within the context of a certain document by utilizing the Retrieval-Augmented Generation (RAG) concept. By obtaining pertinent data from an external knowledge base, RAG apps enhance their generation capabilities. This makes it possible for RAG applications to generate more thorough and instructive answers to a greater variety of prompts and queries.

## Running Mistral 7B Locally using Ollama 🦙

Ollama allows you to run open-source large language models, such as Llama 2, locally. It bundles model weights, configuration, and data into a single package, defined by a Modelfile, optimizing setup and configuration details, including GPU usage.

#### NOTE: First install Ollama in docker and run mistral as stated above

1. Clone this repository:
   
 ```
 git clone https://github.com/krishna-shah-07/ChatBot_Langchain.git
 ```
2. Install all the depenedencies :
   
```
pip install -r requirements.txt
```
3. Open terminal and run the following command:
```
streamlit run app.py
```
