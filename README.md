
Hi, I'm Nikhil Kumar Nyalam 👋
Senior AI Engineer · Agentic AI · Amazon Bedrock AgentCore · LLM Evaluation · Healthcare AI

I build production multi-agent systems for regulated industries: systems that have to be accurate, observable, HIPAA-safe, and fast enough to sit in front of millions of transactions a day. 6+ years of software engineering, now focused on taking agentic AI from prototype to production with real evals behind every release.



🚀 What I'm Working On
🏥 Senior Software Engineer (Agentic AI) at CVS Health: shipped 8+ production multi-agent use cases across pharmacy claims, compliance auditing, text-to-SQL analytics, and drug-safety literature retrieval
⚙️ Building with Strands Agents and LangGraph on Amazon Bedrock and Bedrock AgentCore (Runtime, Memory, Gateway, Identity, Observability)
🧪 Practicing eval-driven delivery: golden Q&A datasets, LLM-as-a-judge, CI regression gates, and A/B testing on every prompt and model change
🔭 On the side: an air-gapped Enterprise AI Platform and a Clinical Trials AI Assistant (see below)
📈 Impact Highlights
Result	How
90% less manual claims & audit review time	Supervisor and planner–executor multi-agent workflows with human-in-the-loop escalation
99.95% availability at 9M+ daily transactions	Retries with backoff, idempotent tool calls, model fallbacks, checkpointed state, AgentCore Memory
45% lower p95 latency (2.1s → 1.15s)	Claude model routing, Bedrock prompt caching, token-efficient hybrid RAG context
Releases moved quarterly → weekly	Automated eval harness on a 1,200-case golden dataset with CI regression on every version
85% fewer harmful outputs	Bedrock Guardrails (PHI/PII redaction), prompt-injection defenses, tool-call policies, audit trails
60% fewer support tickets	Customer-facing AI product assistant on Bedrock AgentCore with Knowledge Bases RAG
🛠️ Tech Stack

Agentic AI LangGraph LangChain Strands Agents MCP / FastMCP A2A Multi-agent Orchestration Tool Calling Human-in-the-Loop

AWS AI Amazon Bedrock Bedrock AgentCore Knowledge Bases Guardrails Bedrock Evaluations Prompt Management SageMaker OpenSearch Serverless

LLMs & RAG Claude GPT Gemini Llama (Ollama, vLLM) Hybrid RAG Text-to-SQL ChromaDB Sentence-Transformers

Evaluation & LLMOps LLM-as-a-Judge RAGAS Langfuse Arize OpenTelemetry CloudWatch A/B Testing

Backend Python FastAPI Django React Node.js Go PostgreSQL MongoDB Redis

Cloud, Data & DevOps AWS (Lambda, ECS, EKS, Step Functions, EventBridge, DynamoDB) Docker Kubernetes Terraform GitLab CI/CD Spark / PySpark Databricks Kafka

📌 Featured Projects
🤖 Enterprise AI Platform

Self-hosted, air-gapped AI platform that unifies 40+ data sources behind permission-aware multi-agent orchestration, MCP, and hybrid RAG. Model-agnostic across OpenAI, Anthropic, Gemini, and local LLMs, built for teams that can't send their data to a third party.

Python LangGraph LangChain MCP Hybrid RAG FastAPI React Docker Ollama / vLLM

🏥 Clinical Trials AI Assistant

Autonomous multi-agent assistant over live ClinicalTrials.gov data. LangGraph routes each question to SQL for structured statistics or ChromaDB vector search for semantic lookups, then returns source-cited, evidence-grounded answers. Async ETL keeps the data current.

Python LangGraph LangChain ChromaDB SQL Gemini Sentence-Transformers

🏅 Certifications & Education
AWS Certified Solutions Architect – Associate
AWS Generative AI Developer Advanced Professional Certificate
IBM AI Engineering Professional Certificate
Google Data Analytics Professional Certificate
🎓 M.S. Computer Science, University of North Texas (GPA 3.75/4.0)
