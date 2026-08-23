# LLM-Powered Search Engine (Agentic)

A Streamlit app where an LLM agent answers questions by autonomously calling search/lookup tools (via LangChain agents) rather than relying only on its own knowledge.

## How it works
- Wraps external tools (e.g. web/Wikipedia search) as LangChain Tool objects
- - An agent decides which tool to call and when, then synthesizes a final answer
  - - Runs interactively in Streamlit with visible tool-use steps
   
    - ## Tech stack
    - Python, LangChain (agents and tools), Streamlit
   
    - ## Run locally
    - pip install -r requirements.txt
    - streamlit run app.py
    - 
