PROMPT:

Classify the following issue as "bug", "enhancement", "question" or "other" and rate your classification confidence and issue understandability in range 0 - 100. Your answer should only include:

Classification: your classification answer \n
Prediction Confidence: your level of confidence
Issue Understandability: level of understandability
issue title: 
issue body: 

1. Colab:

!curl -fsSL https://ollama.com/install.sh | sh

2. Terminal:

ollama serve & ollama pull llama3

3. Colab:

!pip install langchain
!pip install langchain-core
!pip install langchain-community

4. Colab:

from langchain_community.llms import Ollama
llm = Ollama(model = "llama3")
llm.invoke("Tell me 3 red flower names.")
