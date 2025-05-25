# 🧠 Multi-Agent Article Generator using CrewAI

This project showcases a **Multi-Agent System** built using [CrewAI](https://docs.crewai.com/) that automatically generates articles on given topics using autonomous agents like **Researchers** and **Writers**. Each agent has specific goals and tools, working collaboratively to produce human-like content.

---

## 🚀 Features

- ✍️ Autonomous article writing using CrewAI agents
- 🧠 Agent-based task delegation (Researcher, Writer)
- 🔗 Built on top of `langchain`, `crewai`, and other AI libraries

---

## 📁 Project Structure

- `Article.ipynb`: Jupyter notebook implementing the agent pipeline
- Agents:
  - **Researcher**: Search the Web to find relevant information
  - **Writer**: Composes the final article using collected research
  - **Editor**: Proof-reading the generated content and make sure it doesn't have grammatical issues

---

## 🛠️ Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/Vanshdugar/Article-Writer.git
cd Article-Writer
pip install -r requirements.txt
```


```bash
pip install crewai crewai_tools langchain_community
