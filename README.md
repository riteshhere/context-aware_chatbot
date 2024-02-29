# context-aware_chatbot
Chatbot using Amazon Bedrock, Langchain &amp; Streamlit

### Project Overview
Leveraging LangChain and Amazon Bedrock, we develop a context-enhanced chatbot utilizing ConversationSummaryBufferMemory for historical context retention, ConversationChain for dialogue orchestration, and Streamlit for UI deployment. This guide covers environment setup, LM configuration, memory handling, and UI development for advanced, context-aware chatbot creation, targeting developers and AI aficionados to elevate digital user interaction and engagement.

------------------------------------------

### Project Architecture
![architecture](https://github.com/riteshhere/context-aware_chatbot/assets/39124014/ceba22b4-d789-4510-8b8b-67ad1fa397bb)

------------------------------------------
### Detailed Explanation

For an in-depth guide on the implementation, please visit: [Medium Blog](https://medium.com/@xriteshsharmax/context-aware-chatbot-development-59d8c8731987)

------------------------------------------

### How to run
1. **Repository Cloning**: Clone the repository to initiate your local setup.
2. **Virtual Environment**: Establish an isolated environment for dependency management
   ```
   conda create -p env_name python==3.10 -y
   ```
3. **Dependency Installation**: Install necessary dependencies using `requirements.txt`
   ```python
   pip install -r requirements.txt
   ```
4. **Application Initialization**: Launch the application through Streamlit
   ```python
   streamlit run app.py
   ```
5. **AWS Configuration**: To configure AWS please run the following in the terminal and provide AWS credentials.
   ```
   aws configure
   ```
   
------------------------------------------
