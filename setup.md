## Install Ollama

Go to: https://ollama.com/download

Download the .dmg file for macOS.

Open the file and drag Ollama to Applications.

### Test Installation
We will try downloading and interacting with the llama3 model by Meta.
```
ollama run llama3
```

**Note:** Llama 3 is a versatile model for natural language processing (NLP) tasks, like text generation, summarization, and machine translation.

## Basic Setup

1. create virtual environment
   ``python -m venv .venv``
2. activate
```
source .venv/bin/activate
```
3.install requirements
```
pip install -r requirements.txt
```

4. Start jupyter lab

```
jupyter lab
```