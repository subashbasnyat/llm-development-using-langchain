# LangChain for LLM Application Development

This repository contains a Jupyter Notebooks that demonstrates the development and usage of LangChain, a framework for building applications powered by large language models (LLMs). The notebook includes detailed examples and code snippets to guide you through various aspects of using LangChain.
This is a code implementation of short course [LangChain for LLM Application Development](https://learn.deeplearning.ai/courses/langchain/) from [Deeplearning.ai](https://deeplearning.ai)

We use NVIDIA's `mistralai/mixtral-8x7b-instruct-v0.1` using NVIDIA-API. Also, we experiment with local `llama-3` model using Ollama.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [NVIDIA NIMs API Key](#nvidia-nims-api-key)
- [Chapters](#chapters)

## Introduction

LangChain is a powerful framework designed to facilitate the creation of applications that leverage large language models. This notebook provides an in-depth exploration of LangChain's capabilities, including how to integrate different tools and technologies to enhance your LLM-based applications.

## Installation

To run the notebook and experiment with LangChain, you'll need to set up your environment with the required dependencies. Follow the instructions below to get started:

1. Clone this repository:
   ```sh
   git clone https://github.com/subashbasnyat/llm-development-using-langchain.git
   ```
2. Change to the repository directory:
   ```sh
   cd llm-development-using-langchain
   ```
3. Open the Jupyter Lab to explore and run the examples provided. Launch Jupyter Lab with the following command:
   ```sh
   jupyter-lab
   ```

The notebook contains various sections that cover different functionalities and use cases of LangChain. Follow the step-by-step instructions and execute the code cells to see LangChain in action.

## NVIDIA NIMs API Key

- Create a free account with [NVIDIA](https://build.nvidia.com/).
- Choose your model. Click on the link if you want to use the [mistralai/mixtral-8x7b-instruct-v0.1](https://build.nvidia.com/mistralai/mixtral-8x7b-instruct) model.
- Under Input select the Python tab, and click Get API Key. Then click Generate Key.
- Copy and save the generated key as NVIDIA_API_KEY. From there, you should have access to the endpoints.

## Chapters

- [Introduction](1-Introduction.ipynb)
- [Models Prompts and Parsers](2-ModelsPromptsandParsers.ipynb)
- [Memory](3-Memory.ipynb)
- [Chains](4-Chains.ipynb)
- [Question Answering](5-QuestionAnswer.ipynb)
- [Langchain Evaluation](6-LangchainEvaluation.ipynb)
- [Langchain Agents](7-Agents.ipynb)

If you want everything in a single Jupyter Notebook

- [Langchain For LLM Application Development](LangChainforLLMApplicationDevelopment.ipynb)
