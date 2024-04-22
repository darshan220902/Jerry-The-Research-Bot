# Jerry: The Research Bot

Description:
Jerry is your personal research assistant powered by the Gemini Pro generative model. It loads web pages, splits them into smaller chunks, and embeds them into vectors for quick retrieval. When a user asks a question, Jerry retrieves relevant context, generates a prompt, and provides a concise answer.

Components
* Generative Model: Gemini Pro
* Data Loading: URL Loader
* Text Processing: Recursive Text Splitter
* Vector Embedding: GoogleGenerativeAIEmbeddings
* Indexing: FAISS
* Pipeline: Langchain
  
Workflow
* Check user query.
* Load FAISS index.
* Define prompt template.
* Retrieve context.
* Generate prompt.
* Provide answer.


Below is Demo of Jerry Takes The Virat Kohli's Related Information From Websites and Generated a very Concise Output


![Jerry_demo](https://github.com/darshan220902/Jerry-The-Research-Bot/assets/109534955/abf1b3ee-451e-4f4b-906e-305aefc0d0a3)
