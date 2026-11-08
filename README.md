# Aicademy: AI-Powered High School Tutoring System

**An AI learning assistant that gives high school students round-the-clock help** with quizzes, personalized teaching sessions and study tools across six subjects.

> Source code is private under an NDA. This repository documents the project and my role in it.

![Private backend repository (code under NDA)](<Aicademy-Backend source.png>)
*The private Django backend repository, shared as a snapshot because the code is under NDA.*

## My role: main AI engineer

This was a 3-person team project. I was the main AI engineer and owned the AI layer of the backend:

- **RAG pipeline:** retrieval over course material with Hugging Face embeddings, a FAISS vector store and LangChain, so answers are grounded in the right content
- **Agents:** specialized autonomous agents (quiz generation, teaching sessions, summarization, visual explanations) orchestrated with LangGraph
- **Student memory:** persistent memory of each student's weak areas and preferences, used to adapt teaching sessions
- **Visual learning pipeline:** a crawler that collects educational diagrams, AI captioning, and an agent that explains visual concepts
- **LLM integration:** OpenAI models for explanations and Q&A, integrated into the Django backend

## Subjects

English 📚 · Mathematics ➗ · Chemistry 🧪 · Physics ⚛️ · Computer Science 💻 · Biology 🧬

## Features

**Smart quiz system**
- Auto-generated practice quizzes
- Instant grading with detailed explanations
- Progress tracking

**Personalized teaching sessions**
- Adapts to each student's performance
- Remembers weak areas and preferences between sessions
- Targeted reinforcement of difficult concepts

**Study tools**
- Automated flashcard generation
- Textbook chapter summaries
- Past exam paper database
- Visual learning with AI-generated diagrams

## Tech stack

| Area | Tools |
|---|---|
| LLMs | OpenAI models |
| Retrieval | Hugging Face embeddings, FAISS, LangChain |
| Agents | LangGraph |
| Backend | Django |
| Deployment | Docker on AWS |
