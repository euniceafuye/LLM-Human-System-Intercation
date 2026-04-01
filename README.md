# Comparative Analysis of Large Language Models (LLMs): Evaluation via the Hound Protocol

![LLM](https://img.shields.io/badge/Focus-Large%20Language%20Models-red?style=for-the-badge&logo=openai)
![NLP](https://img.shields.io/badge/Tech-NLP%20%26%20Text%20Analysis-blue?style=for-the-badge)
![Compliance](https://img.shields.io/badge/Ethics-EU%20AI%20Act-green?style=for-the-badge)

## 🎯 Project Scope
This research provides a deep dive into the behavioral and functional differences between the world's leading **Large Language Models (LLMs)**. By simulating complex human-AI interactions, we evaluated how different transformer-based architectures handle the role of a "Mentor" under the **Hound Protocol** framework.

### State-of-the-Art Models Analyzed:
* **GPT-4o (ChatGPT)**: Analyzing balanced reinforcement learning from human feedback (RLHF).
* **Claude 3.5 Sonnet (Anthropic)**: Focused on Constitutional AI and safety-first responses.
* **Gemini Pro (Google)**: Testing multimodal integration and expansive reasoning.
* **Copilot (Microsoft)**: Evaluating task-oriented efficiency and search-augmented generation.

---

## 🔬 LLM Benchmarking Methodology
Unlike standard accuracy benchmarks (like MMLU), this project focuses on **Interaction Quality (IQ)** and **Weighted Utility (wU)**:

1.  **Prompt Engineering & Scaffolding**: Testing the models' ability to provide pedagogical support without direct answer-spitting (Reflective Scaffolding).
2.  **Linguistic Fingerprinting**: Using Python-based NLP tools to extract the "personality" of each LLM through:
    * **Sentiment & Polarity Analysis**: How "empathetic" is the model?
    * **Lexical Density**: Analyzing verbosity vs. information density (Claude's detail vs. Copilot's brevity).
    * **Noun/Verb Frequency**: Identifying the operational focus of the AI.
3.  **SWOT Analysis for LLMs**: Mapping intrinsic model strengths (e.g., reasoning) against emergent threats (e.g., over-verbosity or sycophancy).

---

## 🛠️ Computational Analysis (The Code)
I developed 4 dedicated Python pipelines to process the conversation logs of each model:
* **`Text_Analysis_ChatGPT.ipynb`**: Focuses on response consistency.
* **`Text_Analysis_Claude.ipynb`**: Analyzes the high-verbosity and "safe" tone of Anthropic’s model.
* **`Text_Analysis_Gemini.ipynb`**: Evaluates the reasoning flow of Google’s LLM.
* **`TextAnalysis_Copilot.ipynb`**: Investigates the shift toward productivity-centric outputs.

**Key Libraries**: `TextBlob` for NLP, `WordCloud` for thematic extraction, `Matplotlib` for comparative visualization.

---

## 📈 Key Insights for AI Experts
* **The "Alignment Gap"**: We identified where LLMs struggle to align with human-defined SWOT categories, often confusing intrinsic qualities with situational behaviors.
* **Weighted Utility (wU)**: Our results show that higher "Accuracy" doesn't always correlate with higher "Utility." A model that acts as a mentor (scaffolding) provides more long-term value than one that simply solves the task.
* **EU AI Act Compliance**: Evaluation of **Article 13 (Transparency)**, ensuring that the system's capabilities and limitations are clearly communicated to the user.

---

## 📂 Repository Structure
* **/Notebooks**: Individual `.ipynb` files for each LLM's linguistic analysis.
* **/Reports**: `HSI Project Mod.1.pdf` - The full 130+ page deep-dive into LLM interaction logic.
* **/Logs**: Raw human-AI conversation data.

---
**Authors**: Sara Di Franco, Lucrezia Bernini, Eunice Abike Omolayo Afuye, Emir Cinar.
*Developed for the Human-System Interaction Course (BSc in Artificial Intelligence).*
