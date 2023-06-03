# Pdf-GPT

This is Langchain project that enables you to interact with any PDFs via Gradio chat interface. It not only fetches relevant answers but also renders relavant page of the PDFs.

# Technologies Used
1. Langchain
2. ChromaDB as vector store
3. OpenAI embeddings
4. OpenAI chat model (gpt-3.5-turbo)
5. Gradio 

# Steps we perform

1. Build a chatbot interface using Gradio
2. Extract texts from pdfs and create embeddings
3. Store embeddings in the Chroma vector database
4. Send query to the backend (Langchain chain)
5. Perform semantic search over texts to find relevant sources of data
6. Send data to LLM (ChatGPT) and receive answers on the chatbot

# How does the end product look like

![alt text](https://github.com/sunilkumardash9/Pdf-GPT/blob/main/Resources/Screenshot%20from%202023-05-10%2022-07-20.png?raw=true)

# Demo Video

[![Demo Video for pdf-GPT](https://github.com/sunilkumardash9/Pdf-GPT/blob/main/Resources/Screenshot%20from%202023-05-10%2022-07-20.png?raw=true)](https://www.youtube.com/watch?v=RNFDj3zA6Vk&t=4s "Demo Video for pdf-GPT")
