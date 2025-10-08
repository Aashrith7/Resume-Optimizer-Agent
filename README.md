# Resume Optimizer Agent 🤖  

An AI-powered agent that analyzes and optimizes resumes using **Large Language Models (LLMs)** such as GPT, LangChain, and CrewAI.  
It helps users tailor their resumes to match job descriptions by enhancing keyword relevance, readability, and overall impact.

## 🚀 Overview

The **Resume Optimizer Agent** leverages the power of AI to intelligently evaluate and rewrite resumes.  
By combining **LangChain** and **CrewAI**, the system can understand a candidate’s profile and a given job description, then provide smart recommendations — ensuring your resume is **ATS-friendly**, **keyword-rich**, and **professionally phrased**.

This project demonstrates how LLMs and multi-agent systems can be applied to real-world NLP use cases like career optimization.

## ✨ Features

- 🧠 **AI-Powered Resume Optimization** – Uses LLMs to analyze and enhance resume quality.  
- 🔍 **Keyword & Skill Matching** – Aligns resumes with target job descriptions for better recruiter visibility.  
- 🗣️ **Content Rewriting** – Suggests improvements for phrasing, tone, and action verbs.  
- 📊 **ATS Compatibility Scoring** – Evaluates and scores resumes against job postings.  
- ⚙️ **Agentic Workflow** – Employs CrewAI + LangChain agents for context-based multi-step reasoning.  
- 📂 **User-Friendly Notebook Interface** – Implemented as a Jupyter Notebook for easy experimentation.

## 🏗️ Tech Stack

| Category | Technologies |
|-----------|---------------|
| **Language** | Python |
| **Frameworks & Tools** | LangChain, CrewAI |
| **Models / APIs** | OpenAI GPT, HuggingFace Models |
| **Libraries** | Pandas, NumPy, Python-dotenv, Jupyter |
| **Optional UI** | Streamlit |
| **Environment** | Jupyter Notebook |

## 🧩 Architecture

The system consists of **three key components** working together in an agentic pipeline:

1. **Resume Parser Agent**  
   - Extracts text, skills, and experience sections from uploaded resumes.  
   - Preprocesses and structures data for downstream processing.  

2. **Job Analysis Agent**  
   - Reads the target job description.  
   - Extracts role expectations, technical skills, and domain-specific requirements.  

3. **Resume Optimization Agent**  
   - Compares resume vs. job description.  
   - Rewrites bullet points, improves phrasing, and adds relevant missing keywords.  
   - Generates final recommendations with context-aware feedback.  

### 🧠 Multi-Agent Coordination

These agents communicate through **CrewAI’s orchestration layer**, ensuring task delegation and sequential reasoning.  
LangChain manages the prompt pipelines and context persistence between steps, while GPT-based LLMs handle reasoning and rewriting.




