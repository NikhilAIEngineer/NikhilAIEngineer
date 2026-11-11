Hi, I'm Nikhil Kumar Nyalam 👋
Senior AI Engineer · Multi-Agent Systems · MCP · Production LLM Infrastructure

I design and ship production-grade agentic AI for enterprise teams: multi-agent systems that plan, call tools, search the web, query live data, and check their own output before it reaches a user. I focus on what comes after the demo: reliability, cost, latency, and safety at scale.

🔭 Implemented Agentic healthcare AI: A multi-agent Clinical Trials Assistant
🧠 Deep in LangGraph, MCP, LLM evaluation, and LLM cost optimization
🏅 AWS Certified Solutions Architect – Associate
🏅 AWS Certified Generative AI Developer - Professional
🏅 Claude Certified Architect — Professional 
🏅 IBM AI Certification - Professional

🧠 What I Build
Multi-agent orchestration: supervisor and planner–executor architectures in LangGraph with stateful routing, specialized sub-agents, and autonomous tool use
MCP-native tool ecosystems: Model Context Protocol servers and clients that expose 30+ tools (web search, SQL, vector search, internal APIs, document stores) to any LLM
Advanced RAG: hybrid retrieval (dense + keyword), reranking, and agentic retrieval over both structured and unstructured data
LLM cost and latency optimization: prompt caching, semantic response caching, token budgeting, and context compression so every call uses as few tokens as possible
Evaluation: LLM-as-a-Judge pipelines that score groundedness, relevance, and hallucinations
Guardrails and safety: input/output validation, prompt-injection defense, PII redaction, and schema-enforced structured outputs
Model-agnostic LLM layer: OpenAI, Anthropic, Gemini, and local models behind one interface

📌 Featured Projects
🤖 Enterprise AI Platform

A production-grade, model-agnostic agentic AI platform for enterprise knowledge and workflows.

Multi-agent orchestration (LangGraph): a supervisor agent breaks requests into steps and delegates them to specialized agents for retrieval, web research, data, and tools
MCP integration: 30+ tools exposed through the Model Context Protocol, plus 40+ enterprise data integrations
Hybrid RAG: dense + keyword retrieval with reranking for high-precision answers over enterprise documents
Prompt caching + semantic caching and token-minimized prompts to cut LLM cost and latency
LLM-as-a-Judge evaluation of answer quality and groundedness
Input and output guardrails: prompt-injection defense, PII handling, and structured-output validation
Multi-provider LLM layer: OpenAI, Anthropic, Gemini, and local models

Python LangGraph LangChain MCP FastAPI Redis PostgreSQL Docker

🏥 Clinical Trials AI Assistant

An autonomous AI agent for exploring and analyzing clinical trial data in natural language.

Agentic hybrid RAG: a LangGraph router classifies each question and sends it to the right tool. Text-to-SQL handles structured stats (enrollment, phases, outcomes), and ChromaDB semantic search handles trial descriptions and eligibility criteria
Live data pulled from the ClinicalTrials.gov API
Multi-step reasoning that combines SQL results and semantic context into one grounded answer
Gemini Flash for fast, low-cost inference

Python LangGraph ChromaDB SQL Gemini ClinicalTrials.gov API

🎯 How I Approach Production AI
Evaluate before you scale: every agent ships with automated, judge-based evals
Cache aggressively, spend tokens deliberately: cost is an architecture decision
Guardrails are part of the system, not an add-on
Model-agnostic by default: no lock-in to a single provider
