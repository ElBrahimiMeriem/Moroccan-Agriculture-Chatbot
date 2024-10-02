# Moroccan Agriculture Chatbot using LLaMA Models with Retrieval-Augmented Generation (RAG) and Fine-Tuning


This project focuses on developing a Moroccan Agriculture Chatbot using the LLaMA models and exploring different approaches to determine the most effective model for assisting Moroccan farmers. The chatbot leverages both Retrieval-Augmented Generation (RAG) with FAISS and RAG with Qdrant, as well as fine-tuning techniques, with the goal of evaluating which model and approach yield the best results.

**Datasets**

The dataset used in this project is available in the repository under the dataset folder. These datasets offer comprehensive coverage of agricultural knowledge relevant to Moroccan farming, with content in both French and Arabic.

***1. Training Datasets***
   
Dataset 1: Contains 35,208 rows of data.

Dataset 2: Contains 18,209 rows of data.

Each dataset is structured with three columns:

Prompt: Questions or topics related to various aspects of agriculture, such as crop cultivation, soil management, and pest control.

Context: Detailed responses, explanations, or contextual information corresponding to the prompt.

PromptContext: A combination of the Prompt and Context. This column is specifically designed for use in Retrieval-Augmented Generation (RAG) models. It merges the query with its response, enabling the model to better capture relevant information for more precise chatbot interactions.

The datasets cover a wide range of topics essential for Moroccan farmers, including crop types, farming techniques, and fertilizer usage. The bilingual nature of the datasets, with content in both French and Arabic, ensures that the chatbot is accessible to a broader audience.

***2. Evaluation Dataset***

To evaluate the chatbot’s performance in answering Moroccan farmers’ questions, a separate evaluation dataset was created. This dataset contains 73 questions and answers generated using ChatGPT (GPT-4). OpenAI’s GPT-4 model was utilized to generate detailed and contextually appropriate answers, simulating real-world scenarios where the chatbot provides responses to farmers' inquiries. 

**Code and Models**

The code for the chatbot and its training can be found in the code folder of this repository. The fine-tuned models are hosted on Hugging Face and can be accessed via the following links:

**LLaMA 2 Agricultural Model:** https://huggingface.co/MeelUnv/llama2_agri

**LLaMA 3 Agricultural Model:** https://huggingface.co/MeelUnv/llama3_agri

**LLaMA 3.1 Agricultural Model:** https://huggingface.co/MeelUnv/llama3.1_agri
