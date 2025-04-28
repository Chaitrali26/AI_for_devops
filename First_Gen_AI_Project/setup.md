# DockerFile Generator [IN PROGRESS]

This project generates optimized Dockerfiles based on programming language input. 
This project uses Ollama with the Llama3 model to create Dockerfiles following best practices.

## Local LLMs setup

1. Prerequiste: Download ollama:

    ```
    Similar to how Docker uses Docker Hub as a registry for downloading container images, Ollama acts as a model hub, allowing you to easily download, manage, and run Large Language Models (LLMs) on your local machine
    ```
    1.   Download and Install Ollama
        ```
        # For Linux
        curl -fsSL https://ollama.com/install.sh | sh

        # For MacOS
        brew install ollama
        ```
    2.  Start Ollama Service
        ```
        #for linux only:
        ollama serve
        
        #for macos:
        you dont need to start, as after installation it runs a local server in the background(usually on http://localhost:11434). You can test it with this command:
        ollama --version
        ollama -h
        ```

    3.  Pull Llama3 Model
        ```
        for linux and macos:
        ollama pull llama3.2:1b

        In the above command, it pulls lllama model where 3.2 is the version and 1b means model is trained on 1 Billion parameter. 
        Parameters are the internal settings (weights) a model "learns" during training
        ```
    4. To run a chat session:
        ```
        ollama run llama3
        You can then start chatting with Llama directly on your Mac, completely offline.
        ```
## 🚀 Project Setup

1. **Create Virtual Environment**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Linux/MacOS
   # or
   .\venv\Scripts\activate  # On Windows
   ```

2. **Install Dependencies**
   ```bash
   pip3 install -r requirements.txt
   ```

3. **Run the Application**
   ```bash
   python3 generate_dockerfile.py
   ```
