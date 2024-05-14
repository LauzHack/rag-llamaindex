# Intro to RAG with LlamaIndex (Presentation [Google Slide](https://docs.google.com/presentation/d/1rdoaHVmVTn5GYl2xXo83BB_A09MjC6SAkJfjbnlgd8U/edit?usp=sharing) | [PDF](./data/LlamaIndex_lauzhack.pdf), Recording [Youtube](https://youtu.be/Uh_RuwzCZhg))

This workshop was first given by [Pierre-Loic Doulcet](https://www.linkedin.com/in/doulcet/) on May 8, 2024 as part of LauzHack's tech talk series.

## Setup and example

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

Want to learn more? Check out the LlamaIndex short course on [DeepLearning.ai](https://www.deeplearning.ai/short-courses/building-agentic-rag-with-llamaindex/?utm_campaign=llamaindexC2-launch&utm_medium=video&utm_source=youtube&utm_content=teaser).
