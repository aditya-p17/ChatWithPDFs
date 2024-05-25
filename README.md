# ChatWithPDFs

This project involves the development of a robust RAG (Retrieval-Augmented Generation) application designed to facilitate user interactions with PDF documents. By leveraging the Gemini API for advanced document processing and LangChain for natural language understanding and generation, this application provides an intuitive and efficient interface for users to query, summarize, and interact with PDF content.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.


### Prerequisites

- Python version greater than 3.11 installed
- Gemini API key from [AI Studio](https://aistudio.google.com/app/apikey)
  

### Installing

1. Clone the repository

   You can clone the repository by running the following command in your terminal:

   ```bash
   git clone https://github.com/aditya-p17/ChatWithPDFs.git
   ```
2. Set up a virtual environment 

   It's recommended to set up a virtual environment to isolate the dependencies of this project. 

   - On Linux:

     You can do this by running:

     ```bash
     python3 -m virtualenv venv
     source venv/bin/activate
     ```

   - On Windows:

     You can do this by running:

     ```bash
     py -m virtualenv venv
     .\venv\Scripts\activate
     ```

   This will create a new virtual environment in a folder named `venv` and activate it. While the virtual environment is activated, any packages you install with pip will be installed in the virtual environment, not globally.

3. Install the dependencies

   After setting up and activating the virtual environment, you can install the required Python packages with pip by running:

   ```bash
   pip install -r requirements.txt
   ```
4. Get your Gemini API key from [AI Studio](https://aistudio.google.com/app/apikey).
   
5. Create a .env file in the project directory and add your Gemini API key:
   ```makefile
   GEMINI_API_KEY=your_gemini_api_key_here
   ```
6.Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```
