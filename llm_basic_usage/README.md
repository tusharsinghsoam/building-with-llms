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

## LangChain Tools

1. This project contains practical examples demonstrating how to create and integrate custom tools with LangChain agents, enabling LLMs to perform precise, verifiable actions beyond text generation.

2. It covers essential tool patterns including single-parameter tools with the `@tool` decorator for mathematical calculations like `calculate_circumference`, multi-parameter tools with optional arguments for geometric computations like `calculate_hypotenuse`, and a custom `CustomAgentExecutor` class that manages the tool-call loop with scratchpad-based reasoning.

3. Advanced features include multimodal tool usage with the Salesforce BLIP image captioning model, where a `caption_image` tool accepts image URLs and returns natural language descriptions, demonstrating how to wrap deep learning models as LangChain-compatible tools for use within conversational agents.

## LangChain Agents

1. This project contains practical examples demonstrating how to build intelligent agents using LangChain that can reason, plan, and execute multi-step tasks by dynamically selecting and invoking tools.

2. It covers three core agent types including Zero-Shot ReAct for SQL database querying with `create_sql_agent`, Conversational ReAct with persistent session-based memory using `InMemoryChatMessageHistory`, and ReAct Docstore for information retrieval via Wikipedia search and lookup tools.

3. Advanced features include a custom `CustomAgentExecutor` class with configurable iteration limits and scratchpad-based reasoning, history-aware agents that analyze prior conversation context to avoid redundant calculations, and tool-binding patterns using `bind_tools` with `final_answer` enforcement for structured responses.

## LangChain Retrieval Agents

1. This project contains practical examples demonstrating how to combine RAG and agent-based reasoning to build a conversational assistant that dynamically retrieves knowledge from a Pinecone vector store built on the SQuAD dataset.

2. It covers two core approaches including a RAG chatbot using `RunnableWithMessageHistory` and `RunnablePassthrough` for context-injected LCEL chains with windowed session memory, and a RAG agent using a custom `RAGAgentExecutor` with a `knowledge_base` tool that retrieves relevant passages on demand and a `final_answer` tool for structured response delivery.

3. Advanced features include session-aware windowed conversation history managed via `InMemoryChatMessageHistory`, graceful fallback when max iterations are exceeded, and flexible tool orchestration that bypasses retrieval for simple conversational exchanges while querying the vector store for factual or domain-specific questions.

## Prerequisites

- Python 3.x
- API keys for LLM providers (e.g., Gemini API, HuggingFace API, Pinecone API)
- Required libraries: `google-generativeai`, `requests`, `httpx`, `langchain-core`, `langchain-huggingface`, `langchain-pinecone`, `langchain-text-splitters`, `numexpr`, `tiktoken`,  `pinecone`, `tqdm`
- Basic understanding of REST APIs, JSON, prompt engineering, and vector databases

## Acknowledgment

1. [Gemini API Docs](https://ai.google.dev/gemini-api/docs/text-generation)
2. [LangChain Handbook](https://github.com/pinecone-io/examples/tree/f13c63dd4452031e2c2c26a25bb99c1c63725220/learn/generation/langchain/handbook)
