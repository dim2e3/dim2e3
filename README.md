# Hi 👋 I'm Dmitriy Trunov

![Open to Work](https://img.shields.io/badge/Open%20to%20Work-brightgreen?style=flat-square)

### Software Engineer | AWS Solutions Architect | 6x AWS Certified | CloudOps | AI/ML | Node.js

I'm a Software Engineer and AWS CloudOps Engineer/Solutions Architect with 20+ years in 
software development, including 5+ years specializing in AWS cloud architecture, CloudOps, 
and infrastructure design. I build secure, scalable cloud solutions following AWS 
Well-Architected principles, with deep expertise in Node.js/TypeScript full-stack development 
and a growing focus on production AI/ML and generative AI systems.

- 🤖 Hands-on builder across agentic RAG, LLM evaluation, speech ML, and generative imagery 
  (see AI/ML Experience below)
- ☁️ 6x AWS Certified — Solutions Architect, CloudOps Engineer, Developer, ML Engineer, 
  AI Practitioner, Generative AI Developer (Professional)
- 🛠️ Daily use of agentic coding tools: Claude Code, Cursor, Kiro, LM Studio
- 📫 Connect: [LinkedIn](https://www.linkedin.com/in/dmitriy-trunov) · [X/Twitter](https://twitter.com/dmitriy_trunov)

## 🤖 AI/ML & Agentic Systems Experience

Hands-on builder across agentic RAG, LLM evaluation, speech ML, generative imagery, and 
AI-native development workflows — spanning cloud-native (AWS Bedrock/Lambda) and self-hosted 
architectures.

<details>
<summary><b>Agentic RAG & Retrieval Systems</b></summary>
<br>

- Built an agentic RAG assistant on AWS serverless infrastructure (Bedrock, Lambda, S3 Vectors, 
  DynamoDB, CDK) with LLM tool-calling/routing, hybrid retrieval, and cross-encoder reranking; 
  tested with pytest/moto for mocked AWS integration testing
- Built a RAG-based project explorer (Docker/EC2) using OpenAI API, sentence-transformers, 
  hybrid search (minsearch + PostgreSQL), and a Streamlit interface
- Built a bilingual (Russian/English) RAG chatbot with multilingual NLP, prompt engineering, 
  and conversational AI patterns, backed by PostgreSQL and Streamlit

</details>

<details>
<summary><b>LLM Evaluation & Observability</b></summary>
<br>

- Built data pipelines and agent workflows using dlt, DuckDB, and Pydantic AI, with 
  Logfire for observability/tracing
- Implemented LLM-as-judge evaluation methodology with RAG evaluation metrics and feedback 
  loop dashboards for measuring retrieval and generation quality

</details>

<details>
<summary><b>AI-Native Development & Agent Orchestration</b></summary>
<br>

- Built agent-to-agent task relay workflows exploring AI-native development patterns, on a 
  FastAPI/PostgreSQL/Kubernetes stack with Django and React/Vite frontends and CI/CD pipelines
- Implemented a private AI-DLC (AI-Driven Development Lifecycle) platform — see section below

</details>

<details>
<summary><b>Generative AI & Computer Vision</b></summary>
<br>

- Built a generative imagery SaaS product (AIPools) integrating Claude Vision, OpenAI 
  GPT-image-1, DALL·E 2, and Replicate for AI-generated before/after visualizations, on a 
  NestJS/Angular/TypeORM/PostgreSQL stack with AWS S3 and SendGrid

</details>

<details>
<summary><b>Speech ML</b></summary>
<br>

- Built a pronunciation-training application using phoneme-level GOP (Goodness of 
  Pronunciation) scoring, Faster-Whisper (speech-to-text), Kokoro TTS (text-to-speech), 
  PyTorch/torchaudio, HuggingFace Transformers, and scikit-learn-based calibration

</details>

<details>
<summary><b>Conversational AI / Voice Agents</b></summary>
<br>

- Built AI voice-agent automation (Trillet) for call scheduling, on serverless AWS 
  infrastructure (Lambda via Serverless Framework/SAM) with webhook integration and 
  Keycloak authentication

</details>

**Core AI/ML Stack:** Python, TypeScript/Node.js, FastAPI, RAG, agentic/multi-agent systems, 
LLM evaluation, vector search, prompt engineering, AWS (Bedrock, Lambda, CDK, S3, DynamoDB), 
Docker, PostgreSQL, CI/CD

## 🤖 AI-DLC Implementation

Built a private implementation of [AWS's AI-DLC](https://aws.amazon.com/blogs/devops/building-with-ai-dlc-using-amazon-q-developer/) 
methodology — a 16-stage catalog spanning inception through operations — then closed governance 
gaps against Anthropic's [AI-Native SDLC Playbook](https://claude.com/blog/the-ai-native-sdlc-playbook):

- **Skills + Hooks governance** — policy-file context auto-attached to security/compliance-relevant 
  stages, plus a deterministic post-run hook gating code-generation stages before approval
- **AI review gates** — advisory AI review extended to code-generation and build/test outputs, 
  surfaced to the human approver rather than auto-blocking
- **Regression evals** — a fixture-driven eval suite protecting stage prompts and the stage 
  catalog from silent regressions, wired into CI
- **Parallel construction** — git-worktree isolation so multiple units of work run 
  code-generation concurrently without colliding on a shared working tree
- **Closed-loop operations** — a monitoring webhook that drafts a new Intent from an alert, 
  re-entering the pipeline under the same human-approval gate as any other work

## 💻 Tech Stack

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

## ☁️ AWS Certifications

![SA](https://img.shields.io/badge/AWS-Solutions%20Architect%20Associate-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![CloudOps](https://img.shields.io/badge/AWS-CloudOps%20Engineer%20Associate-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Dev](https://img.shields.io/badge/AWS-Developer%20Associate-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![MLE](https://img.shields.io/badge/AWS-ML%20Engineer%20Associate-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![AIP](https://img.shields.io/badge/AWS-AI%20Practitioner-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![GenAI](https://img.shields.io/badge/AWS-Generative%20AI%20Developer%20Professional-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/-Dmitriy%20Trunov-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/dmitriy-trunov)](https://www.linkedin.com/in/dmitriy-trunov)
[![Twitter](https://img.shields.io/badge/-dmitriy_trunov-1DA1F2?style=flat-square&logo=twitter&logoColor=white&link=https://twitter.com/dmitriy_trunov)](https://twitter.com/dmitriy_trunov)
