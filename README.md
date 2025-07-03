#technologies used 

- Ollama (TinyLLaMA)
- LangChain
- Hugging Face (sentence-transformers)
- FAISS
- Streamlit
- PyPDFLoader
- Python's tempfile module



# Used Ollama to run the LLM specifically (Tinyllama) to contextualize the query and give relevant answers
#used streamlit web app for user interface
#used FAISS + Huggingface embeddings (sentence-transformers) 
#from langchain.document_loaders import PyPDFLoader to load and access the PDF and tempfile to create a #temporary file of the pdf 


#changes from origianl model - 
#instead of OpenAI used Ollama (Tinyllama)
#and instead of flask used streamlit