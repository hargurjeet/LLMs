# Large Language Model Repository
![](Icon.png)

<br> This repository serves as a centralized hub for my contributions to large language models (LLMs). Here, you'll find my work on developing and fine-tuning LLMs, along with associated resources and documentation. By maintaining all my LLM contributions in this repository, I aim to provide a comprehensive overview of my work in this domain.

## **Crewai Multi-Agent Blog Content Creator** ([Repo link](https://github.com/hargurjeet/crewai))
- **Overview**
     <br> The Crewai Multi-Agent Blog Content Creator project uses Crewai to build multiple AI agents that communicate among each other to create blog content from YouTube videos. The project utilizes OpenAI's ChatGPT as the language model for tasks like caption extraction, research, and content creation.
- **Features**
    - Caption Extractor: Extracts captions from YouTube videos.
    - Blog Researcher: Gathers detailed information on the video's topic.
    - Blog Writer: Summarizes the information into engaging blog content.
 
- **Installation**

    To run the chatbot locally, follow these steps:
    1. Clone the repository `git clone https://github.com/hargurjeet/crewai.git`
    2. Install the required dependencies using `pip install -r requirements.txt`
    3. python main.py
 
- **Potential Use Cases**

    - **Content Creation**: Automates the creation of high-quality blog posts from video content, saving time for content creators.
    - **Educational Summaries**: Generates detailed summaries and explanations of educational YouTube videos for use in study guides or educational blogs.
    - **Marketing**: Creates blog content that can be used to promote products, services, or ideas presented in YouTube videos.
    - **SEO**: Enhances SEO by generating relevant, keyword-rich blog content derived from popular YouTube videos. 

## **AI Agents Based Data Access Application** ([Repo link](https://github.com/hargurjeet/Agent_RAG_Llama_Index))
- **Overview**
     <br> This application leverages AI agents to access and extract information from various data sources. The agents are built using llama index and gpt-3.5-turbo. The project includes two specialized agents:

     1. PDF Agent: Reads and extracts information from PDF files.
     2. Tabular Data Agent: Accesses and extracts information from tabular datasets (e.g., CSV files).
The AI agents determine the most appropriate data source based on the query and provide the relevant information. Additionally, the agents can save the extracted information to a notepad file if instructed.

- **Features**
    - AI-powered data extraction from PDF and CSV files.
    - Intelligent selection of data source based on query.
    - Save extracted information to a notepad file.

- **Installation**

    To run the chatbot locally, follow these steps:
    1. Clone the repository `git clone https://github.com/hargurjeet/Agent_RAG_Llama_Index`
    2. Install the required dependencies using `pip install -r requirements.txt`
    3. python main.py

 - **Usage**
             <br> 1. **Running the Application**:

    Execute the main script to start the application:
          
              ```bash
              python main.py
              ```

2. **Querying the AI Agents**:
     
    - You can ask questions related to the population of countries or information about India.
    - Based on your query, the appropriate agent will be activated to fetch the information.
     
3. **Saving Information**:
     
    - If you want to save the extracted information, specify this in your query.
    - The information will be saved to a notepad file.


## **QA Chatbot - Cloud Vector Store** ([Repo link](https://github.com/hargurjeet/VectoreStore_Streamlit_Projects))
This is a QA chatbot created using Langchain and Cloud Vector Store, and built with the Streamlit interface.
- **Overview**
    <br> This chatbot is designed to answer user questions based on a pre-trained knowledge base. It uses Langchain for natural language processing and Cloud Vector Store for storing and retrieving the knowledge base.
- **Features**
  - User-friendly interface built with Streamlit
  - Natural language processing powered by Langchain
  - Knowledge base storage and retrieval using Cloud Vector Store
- **Installation**

    To run the chatbot locally, follow these steps:
    1. Clone the repository `https://github.com/hargurjeet/VectoreStore_Streamlit_Projects.git`
    2. Install the required dependencies using `pip install -r requirements.txt`
    3. Run the application using `streamlit run app.py`
- **Usage**
    <br> Once the application is running, you can interact with the chatbot by asking questions in the provided input field. The chatbot will process the question and provide an answer based on the knowledge base.

## **LLM Chatbot with PDF's** ([Repo link](https://github.com/hargurjeet/LLMs-Chat-with-PDFs))
LLM Chatbot is a question answering chatbot based on the LLM (Language, Logic, and Math) framework. It can read the data from the input PDF files and store them in the form of embeddings in the FAISS vector store. It can then answer the user’s questions based on the query asked by referring to the information from the vector store.

- **Demo**
  <br> The solution is not in the production yet. You can try out the chatbot in your local environment.
- **Installation**
  <br> To install the chatbot locally, you need to have Python 3.8 or higher and pip installed. Then, you can follow these steps:
    - Clone this repository:
    git clone https://github.com/hargurjeet/LLMs-Chat-with-PDFs
    - Install the required dependencies: pip install -r requirements.txt
    - Run the chatbot: python chatbot.py

- **Usage**
        <br> To use the chatbot, you need to provide some PDF files that the chatbot can use as sources of information. You can either upload your own PDF files or use the default ones provided in the data folder.
    
    To upload your own PDF files, you need to create a folder named custom inside the data folder and place your PDF files there. Then, you need to edit the config.json file and change the value of the pdf_path key to data/custom.
    
    To use the default PDF files, you can leave the config.json file as it is.
    
    Once you have the PDF files ready, you can run the chatbot and start asking questions. The chatbot will try to find the best answer from the PDF files using the LLM model and the FAISS vector store. You can also ask the chatbot to perform some tasks related to the PDF files, such as extracting, summarizing, or translating.
    
    Here are some examples of questions and tasks you can ask the chatbot:
    
    What is the main idea of the document named sample.pdf?
    - Extract the table of contents from the document named sample.pdf.
    - Translate the first paragraph of the document named sample.pdf to French.
    - How do I install FAISS?
    - What is the LLM framework?

## **Blog Development Application with Meta Llama 2 Model**([Repo link](https://github.com/hargurjeet/Llama2))
This application is designed to facilitate blog development using the Meta Llama 2 model. It is built on Streamlit and provides a user-friendly interface for individuals, data scientists, and researchers who want to interact with the Llama 2 model without extensive app development knowledge.

- **Features**
    - Meta Llama 2 Model: Utilizes the powerful Meta Llama 2 model for blog development tasks.
    - Streamlit Interface: Provides an intuitive user interface built on Streamlit for easy interaction with the model.
    - User-Friendly: Designed to be accessible to individuals with varying levels of technical expertise.

- **Usage**
<br> The Meta Llama 2 model and generate blog content. Users can select a profile, such as "Researcher" or "Data Scientist," and specify the desired word limit for the content. The model will then generate a blog post based on the selected profile and word limit.

    The application also allows users to create both long-form and short-form content, depending on their needs. Users can specify a word limit ranging from 100 to 1000 words, providing flexibility in the length of the generated content.
    
    Overall, the application provides a simple and efficient way to generate high-quality blog content, even for users without extensive app development knowledge.

- **Installation**
  <br> To install the chatbot locally, you need to have Python 3.8 or higher and pip installed. Then, you can follow these steps:
    - Clone this repository:
      `git clone https://github.com/hargurjeet/Llama2/tree/main`
    - Install the required dependencies:
      `pip install -r requirements.txt`
    - source code - app.py
    `streamlit run app.py`


 ## **QA_Chatbot Deployed - HuggingFace CodeSpaces** ([Repo link](https://github.com/hargurjeet/Q-A_Chatbot?tab=readme-ov-file))
 QA Chatbot is a question-answering chatbot powered by OpenAI’s GPT Turbo and built using the LangChain framework. It can answer questions based on the content it has learned which is up to September 2021 at the time of writing this post.

 - **Demo**
  <br> You can try out the chatbot online using this link: [QA Chatbot Demo](https://huggingface.co/spaces/Hargurjeet/LangChainQ-AChatbot). This is a Hugging Face Space that hosts the chatbot and allows you to interact with it in real time.
- **Installation**
  <br> To install the chatbot locally, you need to have Python 3.8 or higher and pip installed. Then, you can follow these steps:
    - Clone this repository:
      `git clone https://github.com/hargurjeet/Q-A_Chatbot`
    - Install the required dependencies:
      `pip install -r requirements.txt`
    - source code - app.py
    `streamlit run app.py`
