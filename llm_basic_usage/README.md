# About

## LLM Basic Usage using Gemini

1. This project contains practical examples demonstrating fundamental concepts and techniques for working with Large Language Models using the Gemini API.

2. It covers essential interaction patterns including single-turn and multi-turn conversations, system instructions for controlling model behavior, and conversational memory for maintaining context across multiple exchanges.

3. Advanced features include streaming responses for real-time content generation, multimodal inputs for processing documents, and prompt engineering techniques that demonstrate how to improve response quality through better prompting strategies.

## LangChain Chat Templates and Prompt Engineering

1. This project contains practical examples demonstrating LangChain's powerful prompt templating system and chain composition patterns using the LangChain Expression Language (LCEL).

2. It covers essential prompt engineering techniques including simple templates, few-shot learning with dynamic example selection, and chat prompt templates with system/human/ai message patterns for conversational applications.

3. Advanced features include LCEL chain composition for building complex workflows, parallel execution with RunnableParallel for simultaneous operations, and batch processing capabilities for efficient handling of multiple inputs.

## LangChain Conversational Memory

1. This project contains practical examples demonstrating various memory strategies for maintaining conversation context in LLM applications using LangChain's memory management system.

2. The project covers four essential memory types including Buffer Memory for complete history retention, Summary Memory for condensed conversation summaries, Window Buffer for keeping recent interactions, and Hybrid Summary Buffer combining both approaches.

3. We also show token usage optimization across different memory strategies, custom memory implementations with configurable parameters, and comparative analysis using visualization to demonstrate trade-offs between context retention and computational efficiency.

## LangChain Retrieval Augmented Generation (RAG)

1. This project contains practical examples demonstrating how to build a complete RAG system that combines LLMs with external knowledge bases for accurate question-answering using real-world financial data.

2. It covers essential RAG components including text chunking with RecursiveCharacterTextSplitter, semantic embeddings using BAAI/bge-small-en model, and vector storage with Pinecone for efficient similarity search and retrieval.

3. Advanced features include batch indexing with metadata preservation, LangChain integration for building retrieval chains with LCEL, and semantic search with relevance scoring to provide context-aware responses with source attribution.

## Prerequisites

- Python 3.x
- API keys for LLM providers (e.g., Gemini API, HuggingFace API, Pinecone API)
- Required libraries: `google-generativeai`, `requests`, `httpx`, `langchain-core`, `langchain-huggingface`, `langchain-pinecone`, `langchain-text-splitters`, `numexpr`, `tiktoken`,  `pinecone`, `tqdm`
- Basic understanding of REST APIs, JSON, prompt engineering, and vector databases

## Acknowledgment

1. [Gemini API Docs](https://ai.google.dev/gemini-api/docs/text-generation)
2. [LangChain Handbook](https://github.com/pinecone-io/examples/tree/f13c63dd4452031e2c2c26a25bb99c1c63725220/learn/generation/langchain/handbook)
