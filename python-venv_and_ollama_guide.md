## Commands to create a new venv
1. python3 -m venv venv
2. source venv/bin/activate

## Commands to run Ollama
1. Ollama ls
2. ollama run phi3:latest
3. How to use LLM from Ollama

<code>
from langchain_ollama import OllamaLLM

llm = OllamaLLM(model='phi3')
</code>