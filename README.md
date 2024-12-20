1. Install Ollama : Download Ollama from the official Ollama website.

    After installation, check if it's installed by running the following command in your terminal:
   
        ollama

2. Download the Model : Use the following command to download the Llama 3.2 model:

        ollama run llama3.2:1b

3. Set Up a Virtual Environment

        python -m venv my_venv
        source env_name/bin/activate
        pip install -r requirements.txt

4. Run the Notebook

    - Launch Jupyter Notebook

    - Open the app.ipynb ( conversation cell )  file and run the cells to start the conversation with the model.

    - Usage

        - Type your questions and interact with the Llama model.
        - Type bye to exit the conversation.