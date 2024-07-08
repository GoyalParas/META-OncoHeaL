## Preview
[![image](https://github.com/GoyalParas/Project_Pics/blob/main/Repo%20Front.png)](https://1drv.ms/v/s!Ap1njuuXv2Tegcsgbm8pOvNNPVEqbw?e=RFctIw)

WORKING PROTOTYPE  [VIDEO](https://1drv.ms/v/s!Ap1njuuXv2Tegcsgbm8pOvNNPVEqbw?e=RFctIw) ▶️
## About The Project 

"META OncoHeal"an AI-driven conversational agent designed to provide counselling to Cancer affected individuals & support to practising oncologists. Built using [Llama 2](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main) (7B GGML quantized version),[FAISS](https://engineering.fb.com/2017/03/29/data-infrastructure/faiss-a-library-for-efficient-similarity-search/) (library for efficient similarity search and clustering of dense vectors) , LangChain & Streamlit, this chatbot leverages sentence transformers [all mini LML6V2 model](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2) for doing embeddings provided by [hugging face API](https://huggingface.co/docs/api-inference/en/index) .It possesses historical conversational memory, making the interaction more engaging.

## Approach
This process initiates by extracting data, which is then fragmented into manageable text chunks which I have kept to be 500 here. Each chunk undergoes transformation into semantic embeddings, forming a robust semantic index stored within a knowledge base. Upon user inquiry, the question is encoded into query embeddings and subjected to a sophisticated semantic search within the knowledge base, producing ranked results. These results are then processed by the LLM, which synthesizes and returns precise, contextually relevant answers, seamlessly integrating state-of-the-art semantic indexing and AI-driven generation for a relaxing user experience.

![image](https://github.com/GoyalParas/Project_Pics/blob/main/Approach_Final.png)

## Built With
- ctransformers
- torch
- accelerate
- FAISS
- langchain-community
- sentence_transformers
- altair
- streamlit
- HuggingFaceEmbeddings
- pypdf
- LLAMA 
 
## Dataset 
The dataset used for this project is taken from the [DEPARTMENT OF ONCOLOGY CANCER CENTRE TOWNSVILLE UNIVERSITY](https://www.townsville.health.qld.gov.au/services/cancer-services/adult-cancer-services/medical-oncology/) , availabe on [kaggle](https://www.kaggle.com/code/mpwolke/covid-19-oncology-repercussions) also.
