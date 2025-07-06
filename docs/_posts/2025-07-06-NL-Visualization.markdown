---
layout: post
title: "🧠 NL → Visualization Assistant using Mistral, LangChain and Code Llama"
date: 2025-07-06 00:00:00 -0400
categories: generative-ai langchain llm
---

Imagine asking: _“Show me monthly sales trends by region”_ — and instantly getting a chart. That’s exactly what I built at Accure using **Mistral**, **LangChain**, and **Code Llama**.

### 💡 Objective
Allow users to query and visualize structured data using natural language, without needing a data analyst.

### 🏗️ Architecture
- Stage 1: Convert NL → SQL using Code Llama  
- Stage 2: Convert SQL → Python + Matplotlib/Vega code  
- LangChain handled prompt routing and model orchestration  
- Hosted on Streamlit for easy UI interaction

### ✅ Result
- Achieved 76% accuracy across test queries  
- Response time under 30 seconds  
- Removed human-in-the-loop from routine visual requests

In a future post, I’ll share prompt engineering techniques and how we evaluated performance using syntactic and semantic correctness.

