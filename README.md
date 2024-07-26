# HistoryQuest-Arabic-Question-Answering-in-Egyptian-History-with-LLM-Fine-Tuning and Transformer-Models.
The project explores how large language models (LLMs), and transformers can improve the way we answer questions about Egyptian history in Arabic. Using models like AraBERTv2 and LLaMa-2 & 3. This work shows how modern technology can make understanding Egypt's rich history easier and more accessible.
# Introduction
This repository comprises three primary Python notebooks, each showcasing the application of advanced machine learning models to historical datasets. The featured models include fine-tuned versions of the Llama 2 and Llama 3 models, along with a Retrieval-Augmented Generation (RAG) system.
# Notebook (1): Llama-2 Model
The first notebook illustrates the use of the Llama 2 model, which is fine-tuned on specific historical datasets. This model aims to deliver precise and insightful analyses of the data, highlighting key historical trends and patterns.
### Features:
•	Data preprocessing and cleaning
•	Model training and fine-tuning
•	Analysis and contextual generation

# Notebook (2): Llama-3 Model
The second notebook introduces the Llama 3 model, which builds upon the Llama 2 model. It is also fine-tuned on historical datasets, offering enhanced performance and accuracy.
### Features:
•	Data preprocessing techniques
•	Model training and fine-tuning
•	Analysis and contextual generation


# Notebook (3): Retrieval-Augmented Generation (RAG) System
The third notebook delves into the Retrieval-Augmented Generation (RAG) system. This system merges retrieval-based methods with generation-based models to produce more accurate and contextually relevant outputs.
### Features:
1) Indexing: Indexing involves segmenting text into smaller chunks through chunking, transforming these chunks into vector representations using an embedding model, facilitating similarity comparisons, and storing the text chunks and their vector embeddings as key-value pairs in a Vector DB.
2) Retrieving: Retrieval involves searching the indexed database to find the most relevant documents or text fragments based on a given query.
3) Generation: Generation involves creating a coherent and contextually appropriate response or continuation based on the retrieved documents.

# Historical Datasets:
- Arabic History-QA: A dataset of 420 question-answer pairs covering key periods in Egyptian history, including the Pharaohs' era, the Roman occupation, the Ptolemaic Dynasty, and the Greek era with Alexander the great.
- Contextual Articles: A collection of web-scraped articles in PDF format, providing a knowledge base for the Retrieval-Augmented Generation (RAG) component of the question-answering system.
