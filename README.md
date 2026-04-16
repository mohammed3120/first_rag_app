# first_rag_app

This is a minimal implementation of the RAG model for question answering.

## Requirements

- Python 3.10

#### Install Dependencies
1) Install python3 if is not installed before

```bash
$ sudo apt update
$ sudo apt install libpq-dev gcc python3-dev
```

2) Create a new environment using the following command:
```bash
$ python3 -m venv first_rag_venv
```
3) Activate the environment:
```bash
$ source first_rag_venv/bin/activate
```

### Setup the environment variables

```bash
$ cp .env.example .env
```

Set your environment variables in the `.env` file. Like `OPENAI_API_KEY` value.

