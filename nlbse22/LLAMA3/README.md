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
