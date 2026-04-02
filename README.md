
<!--
**asingleneuron/asingleneuron** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# 👋 Hi, I'm Shobhit Upadhyaya  
**Principal Data Scientist | LLM / RAG / Conversational AI**

📍 Bangalore, India  
📧 sho.upadhyaya@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/shobhit-upadhyaya)  
🔗 [YouTube](https://youtube.com/asingleneuron)  

---

## 🚀 About Me

Principal Data Scientist with **16+ years of experience (9+ in ML/AI)** specializing in:

- LLM-powered conversational systems  
- Retrieval-Augmented Generation (RAG)  
- Multi-turn reasoning & ambiguity resolution  

Built production AI systems serving:

- 👥 **~148K users**  
- ⚡ **~4K queries/day**  
- 📚 **~5K internal knowledge documents**  

👉 Improved system deflection from **26% → ~50%**

---

# 🧠 AI Service Desk — LLM + RAG Conversational System

Enterprise-scale conversational AI system designed to handle ambiguous user queries using **LLMs, RAG, multi-turn reasoning, and retrieval optimization**.

---

## 🚀 Overview

This system powers an **AI Service Desk (AISD)** used by **~148K employees**, handling:

- ⚡ ~4,000 queries/day  
- 📚 ~5,000 internal knowledge documents  

👉 Improved automation/deflection from **26% → ~50%**

---

## 🧩 Problem Statement

Users frequently submit **vague and ambiguous queries**, such as:

- “I need help”
- “Unable to login”
- “Reset password”

### Key Challenges:
- Missing context in user queries  
- Over-specific refined queries causing LLM failures  
- Poor UX (long, unstructured responses)  
- Scaling ambiguity resolution across topics  

---

## 🏗️ System Architecture
User Query
↓
Query Understanding (Rephrase + Context)
↓
Semantic Retrieval (OpenSearch - Top 100)
↓
Reranking (Cohere - Top K)
↓
LLM Reasoning Layer
↓
Answer Generation
↓
Structured Response (UX Layer)

---

## 🔧 Key Innovations

### 1. 🧩 Multi-Turn Conversational Intelligence
- Transitioned from single-turn → context-aware system  
- Maintains conversation history for better reasoning  

---

### 2. 🌲 Dialogue Model (Rule-Guided)
- Decision-tree-based disambiguation
- Handles structured flows for known topics
- Example flow:
  - Reset password
  → Ask OS (Windows/Mac)
  → Ask login status
  → Provide resolution

👉 Improved deflection: **26% → 40%**

---

### 3. 🤝 Mutual Understanding Model (LLM-Based)
- Handles **unconfigured / scalable scenarios**
- Uses **top-k retrieved documents** to generate follow-ups  

👉 Impact: **+10% deflection**
---

### 4. 🔄 Query Simplification (Failure Recovery)

**Problem:**  
Refined queries became **too specific**, causing LLM to fail (~10%)

**Solution:**  
- Generate **multiple simplified queries**  
- Remove unnecessary constraints  
- Retry retrieval + generation  

👉 Results:
- +10% answer coverage  
- +5–6% deflection  

---

### 5. 🧾 Wall of Text → Structured UX

**Problem:**
- Long LLM responses reduce readability in Slack  

**Solution:**
- Structured output:
  - 🚀 Quick Solution  
  - Step-by-step instructions  
  - Notes / context  

👉 Impact:
- +2–3% deflection  
- Improved user engagement  

---

## 📊 Final Impact

| Component | Improvement |
|----------|------------|
| Multi-turn baseline | 26% |
| Dialogue Model | +11% |
| Mutual Understanding | +10% |
| Query Simplification | +5–6% |
| UX Optimization | +2–3% |
| **Final Deflection** | **~50%** |

---

## 🛠️ Tech Stack

- **LLMs:** LLaMA (llama4.scout)  
- **Architecture:** RAG, Multi-turn reasoning  
- **Search:** OpenSearch (semantic retrieval)  
- **Ranking:** Cohere rerank  
- **Cloud:** Oracle Cloud Infrastructure (OCI)  
- **Data:** ATP DB  
- **Languages:** Python, SQL  

---

## 🧠 Key Learnings

- Ambiguity handling is critical in real-world AI systems  
- Retrieval quality directly impacts LLM performance  
- Over-specific queries can degrade answerability  
- UX design is as important as model performance  

---

## 🎯 Future Improvements

- Adaptive retrieval strategies (dynamic top-k)  
- Better query intent classification  
- Reinforcement learning from user feedback  
- Latency optimization for real-time interaction  

---

## 🏆 Achievements (Top 1%)

- 🥈 Ericsson ML Challenge — 2nd / 4120  
- 🥉 USAID Forecasting Challenge — 3rd  
- 🥉 MakeMyTrip — 3rd / 3556  
- 🏆 BrainWaves (SocGen) — Finalist (4926)  

---

## 🎯 What I Focus On

- Building **production-grade LLM systems**  
- Solving **ambiguity in real-world AI systems**  
- Improving **retrieval + reasoning + UX together**  

---

## 📬 Let’s Connect

If you're working on:
- LLM systems  
- RAG architectures  
- Conversational AI  

Feel free to connect or collaborate!
