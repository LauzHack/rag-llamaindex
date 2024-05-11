# Intro to RAG with LlamaIndex


Below we setup a [simple example](https://docs.llamaindex.ai/en/stable/getting_started/starter_example/) to demonstrate how to use the LlamaIndex for RAG (Retrieval-Augmented Generation).
```
# create and activate virtual environment
conda create -n rag python=3.11
conda activate rag

# install llama index
pip install llama-index

# set up openai api key
export OPENAI_API_KEY=XXXXX

# run example
python test_llamaindex.py
```

You can try changing the question in the script, or putting other content in the ``data`` folder!