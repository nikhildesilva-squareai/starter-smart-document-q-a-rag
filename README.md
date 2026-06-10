# Smart Document Q&A (RAG)

![Beginner](https://img.shields.io/badge/difficulty-beginner-22C55E) ![Generative AI](https://img.shields.io/badge/course-Generative%20AI-0056CE) ![10 hours](https://img.shields.io/badge/estimated-10h-lightgrey)

> **Square 1 AI** starter template — Generative AI

## Overview

In this introductory project, you'll build a **Smart Document Q&A (RAG)** using Python, Anthropic SDK, pgvector or Chroma, Next.js. Build a system that lets users upload a PDF or paste text and ask questions about it using RAG. This is a hands-on project where you'll write real code, solve real problems, and build something you can showcase in your portfolio.

This project is part of the **Generative AI** course, where you'll build applications powered by large language models and AI generation capabilities.

## What You'll Learn

- Write clean, well-structured Python code following PEP 8 conventions
- Integrate with the Anthropic Claude API for AI-powered features
- Build a production-grade web application with Next.js and TypeScript
- Follow software engineering best practices: version control, documentation, testing
- Write a comprehensive README with setup instructions, usage examples, and architecture overview

## Tech Stack

`Python` `Anthropic SDK` `pgvector or Chroma` `Next.js` 

## Requirements

- [ ] Document upload and chunking
- [ ] Embedding generation
- [ ] Vector similarity search
- [ ] Context-injected Q&A

## Approach

Start with `npx create-next-app` and set up your project structure. Build the data model and database schema first. Create the API routes, then the UI pages. Start with a working prototype before adding polish, authentication, and advanced features.

## Milestones

### 1. Document ingestion
Parse and chunk a PDF

### 2. Embeddings
Generate and store embeddings

### 3. Retrieval
Find relevant chunks for a query

### 4. Generation
Inject context and generate an answer

## Deliverables

- Working application with all requirements implemented
- Clean, well-documented source code on GitHub
- README with setup instructions, screenshots, and usage guide

## Tips & Guidance

- Commit early and often — the AI reviewer can see your commit history and values incremental progress
- Write your README as you build, not at the end — it helps clarify your thinking
- Use virtual environments (`python -m venv venv`) to manage dependencies cleanly
- Use TypeScript for better code quality — the type system catches bugs before runtime
- Implement proper error handling for API rate limits, timeouts, and unexpected responses

## How You'll Be Evaluated

The AI reviewer will analyse your actual source code and evaluate:

- **Code quality**: clean, readable, well-structured code with proper naming conventions
- **Completeness**: all requirements are implemented and functional
- **Documentation**: README is comprehensive with setup instructions and usage examples
- **Git history**: regular commits with meaningful messages showing progressive development

## Getting Started

```bash
# Clone this template
git clone https://github.com/nikhildesilva-squareai/starter-smart-document-q-a-rag.git
cd starter-smart-document-q-a-rag

# Set up Python environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\\Scripts\\activate
pip install -r requirements.txt

# Run
python main.py
```

## Submission

1. Complete the project following all requirements above
2. Push your code to your own **public** GitHub repository
3. Go to [Square 1 AI](https://square1-tutor.vercel.app/projects) and submit your repo URL
4. Our AI will review your actual code and give you a score with line-level feedback

## Career Relevance

This project builds skills directly applicable to roles like: **AI Engineer, LLM Application Developer, GenAI Specialist**.

---

Built with [Square 1 AI](https://square1ai.com) | Learn. Build. Get Hired.
