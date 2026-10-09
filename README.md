# Week 4: AI Agent Systems

## Project Overview

This project implements a Retrieval-Augmented Generation (RAG) system using LangChain, LangGraph, FAISS, and a local FLAN-T5 model.

## Technologies Used

* Python
* LangChain
* LangGraph
* FAISS Vector Store
* Hugging Face Transformers
* FLAN-T5
* Google Colab
* LangSmith (tracing setup attempted)

## Project Workflow

1. Prepare AI and ML notes as the knowledge source.
2. Split the text into smaller chunks.
3. Generate embeddings and store them in FAISS.
4. Retrieve relevant context for user questions.
5. Generate answers through the LangGraph workflow.
6. Test the system with multiple questions and save evaluation results.

## Files

* `Week4_AI_Agent_Systems.ipynb` — Project implementation
* `rag_evaluation_results.csv` — Evaluation results

## Evaluation

The system was tested with six questions related to AI, Machine Learning, Deep Learning, NLP, Computer Vision, and AI applications.

The evaluation CSV contains the recorded results. LangSmith tracing was attempted, but traces were not confirmed in the dashboard.

## Status

The RAG workflow and evaluation are completed. Further verification of LangSmith tracing remains pending.
