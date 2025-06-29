# llm-prompt-strategy-evaluation
Comparative analysis of prompt strategies on LLMs (GPT-4o, Grok 3, Claude Sonnet 4, DeepSeek V3)

# 🧠 LLM Prompt Strategy Evaluation

This repository contains the source files and results of my undergraduate thesis titled:

**"Farklı Prompt Stratejilerinin Performanslarının Büyük Dil Modellerinde Karşılaştırmalı Analizi"**  
(*"Comparative Analysis of Prompt Strategies in Large Language Models"*)

📍 _Istanbul Aydın University – Department of Management Information Systems_  
📅 _June 2025_  
👩‍🎓 _Author: Elifnur Şirin_

---

## 🎯 Project Objective

The study evaluates how different prompt engineering strategies affect the performance of modern large language models (LLMs) like GPT-4o, Claude Sonnet 4, Grok 3, and DeepSeek V3.

Each strategy-model combination is tested on:
- ✅ Accuracy
- 💬 Q&A response quality
- 🧠 Summarization performance
- 🧑‍💻 Code generation quality

---

## 🚀 Prompt Strategies Compared

- **Zero-shot prompting**
- **One-shot prompting**
- **Few-shot prompting**
- **Chain-of-thought (CoT) prompting**
- **Direct prompting**
- **Indirect prompting**

Each model was tested with all strategies on the same set of tasks using standardized prompts and a 0–100 scoring scale.

---

## 📊 Evaluation Criteria

Each LLM output was scored based on:

| Criterion            | Description                                       |
|----------------------|---------------------------------------------------|
| 🔎 Accuracy           | Is the response factually correct?               |
| ✍️ Clarity            | Is the response understandable and well-written? |
| 📚 Detail Level       | Does it provide enough context and explanation?  |
| 🎯 Relevance          | Does it match the question and context?          |

---

## 🏁 Key Findings

- **Chain-of-Thought** and **Indirect Prompting** strategies yielded the highest quality outputs across most tasks.
- **Few-shot** and **One-shot** strategies often suffered from limited depth due to overly simplified examples.

---

## 📁 Project Structure

```bash
llm-prompt-strategy-evaluation/
│── Prompt_Strategy_Thesis_Report.pdf        # Full report (in Turkish)
│
├── charts/
│   └── accuracy-metric.pdf
|   └── code-generation-meteric.pdf
|   └── q&a-metric.pdf
|   └── summarizing-metric.pdf
├── results/
│   └── accuracy_analysis.py
|   └── code-generation_analysis.py
|   └── q&a_analysis.py
|   └── summarizing_analysis.py
|   └── model_points.csv
