# Building a RAG system with DeepSeek, LangChain, HuggingFace

This repository contains the code and resources needed to build a RAG (Retrieval Augmented Generation) system that uses videos as a source of information. The system can extract text from videos, generate embeddings, index them, and then use an LLM to answer questions based on the video content.

## Overview

The system is divided into two main stages:

1.  **Data Preprocessing:**
    *   Extracting text from videos using Speech to Text and Whisper from HuggingFace.
    *   Dividing the text into chunks for better processing with Langchain.
    *   Generating high-quality embeddings with VertexAI.
    *   Storing and querying the embeddings in an in-memory vector database.

2.  **Building the Retriever and Text Generation:**
    *   Using the DeepSeek Distilled LLM to generate coherent and accurate responses.
    *   Implementing the Retriever to retrieve relevant information from the vector database.
    *   Using Langchain and HuggingFace to access the LLM model.

## Usage

1.  Configure the necessary environment variables (API keys, etc.).

2.  Run the notebook

This repository is actively maintained and updated with new examples and use cases. Contributions are welcome!

Made with ❤ by  [jggomez](https://devhack.co).

[![Twitter Badge](https://img.shields.io/badge/-@jggomezt-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/jggomezt)](https://twitter.com/jggomezt)
[![Linkedin Badge](https://img.shields.io/badge/-jggomezt-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/jggomezt/)](https://www.linkedin.com/in/jggomezt/)
[![Medium Badge](https://img.shields.io/badge/-@jggomezt-03a57a?style=flat-square&labelColor=000000&logo=Medium&link=https://medium.com/@jggomezt)](https://medium.com/@jggomezt)

## License

    Copyright 2025 Juan Guillermo Gómez

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS 
