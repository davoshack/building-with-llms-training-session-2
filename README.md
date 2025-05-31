# Building software on top of Large Language Models - Session 2

## Prerequisites

If you are attending this tutorial you will need a **laptop with a browser** and a **GitHub account**. The tutorial can be entirely completed using [GitHub Codespaces](https://github.com/features/codespaces), a free online development environment.

If you would prefer to run everything on your own machine you will need a **Python 3.9 or higher** local development environment with the ability to create a virtual environment and install packages using `pip`.

You can pre-install the packages we will be using like this:

```bash
git clone git@github.com:davoshack/building-with-llms-training-session-2.git
cd building-with-llms-training-session-2

# Optional if you want a virtual environment (no need to do this on Codespaces):
python -m venv venv
source venv/bin/activate
```

## Install Agentic Patterns Requirements
```sh
cd agentic-patterns
pip install -r requirements.txt

```

## Install FastAPI For AI Applications Requirements
```sh
cd fastapi-for-ai-applications
pip install -r requirements.txt
```

## Install LangChain Fundamentals Requirements
```sh
cd langchain-fundamentals
pip install -r requirements.txt
```

## Workshop description

Large Language Models such as GPT-4o, Claude and Google Gemini provide APIs that can be used to develop features that were almost impossibly difficult to build in the past, spanning areas that include human language understanding, image recognition and structured data extraction.

Building software that uses these APIs reliably and responsibly is a topic with a great deal of depth and a lot of hidden traps.

In this second session, we'll explore the fundamentals of the RAG Architecture, Agent Patterns and Architectures for AI Applications

Topics we will cover include:

* [LangChain Fundamentals](docs/langchain-fundamentals/README.md)
* [Agentic Patterns](docs/agentic-patterns/README.md)
* [FastAPI for AI Applications](docs/fastapi-for-ai-applications//README.md)



