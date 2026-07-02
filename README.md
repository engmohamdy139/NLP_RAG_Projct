# mini-rag

this is minimal implementation of the RAG  model for question answering. 

## Requiremnts 

- python 3.8 or later 

#### Install Python using MiniConda

1) Download and Install Miniconda from [here] (https://www.anaconda.com/download/success?reg=auth)

2) Create a new enviroment using the following command :
```bash
$ conda create -n mini-rag python=3.8
```
3) Activate the environment :
```bash
$ conda activate mini-rag
```  

## Installation 

### Install required pakages

```bash
$ pip install -r requirements.txt
```

### Step the environment variable
```bash 
$ cp .env.example .env
```
set your environment variables in the `.env` files. Like `OPENAI_API_KEY` value. 

