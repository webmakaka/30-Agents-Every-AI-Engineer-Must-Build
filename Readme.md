# [Book][Imran Ahmad] 30 Agents Every AI Engineer Must Build [ENG, 2026]

**Build production-ready agent systems using proven architectures and patterns**

<img src="img/30-Agents-Every-AI-Engineer-Must-Build.jpg" alt="30 Agents Every AI Engineer Must Build" width="300" align="right" />

<br/>

**Original Repo:**  
https://github.com/PacktPublishing/30-Agents-Every-AI-Engineer-Must-Build

---

## About This Book

The AI landscape is shifting from passive, reactive systems to autonomous, goal-directed intelligent agents—systems that perceive their environment, make decisions, and take actions with minimal human intervention. This book presents **30 essential agent architectures** that every AI engineer must master to build effective, production-ready systems.

Raw LLMs alone are not enough. The key to building transformative AI systems lies in understanding how to architect agents that decompose complex tasks, connect to external tools and data sources, maintain memory across interactions, collaborate with humans and other agents, learn from experience, and make ethical decisions aligned with human values.

Each chapter includes **working code**, **formal architectural patterns**, **real-world case studies**, and guidance on avoiding common implementation pitfalls. Every pattern has been tested against the production realities of latency, cost, reliability, and security that define real-world deployments.

## Who This Book Is For

This book is for **AI engineers**, **software developers**, **ML researchers**, and **technical leads** building intelligent systems. It's ideal for those deploying LLM-powered applications or transitioning from traditional ML to agentic frameworks. Python experience and basic ML knowledge are recommended.

---

Foundation and Tools (Chapters 1-4)

We begin with the essential groundwork that every agent engineer must understand:

    • Chapter 1: Foundations of Agent Engineering introduces core concepts, terminology, and architectural patterns that underpin all intelligent agent systems.
    • Chapter 2: The Agent Engineer's Toolkit surveys the frameworks, models, and development tools you'll need to efficiently build agent systems.
    • Chapter 3: The Art of Agent Prompting explores advanced prompt engineering techniques specifically tailored for agent development.
    • Chapter 4: Agent Deployment and Responsible Development addresses the practical considerations of scaling, securing, and ensuring ethical behavior in production agent systems.

Core Agent Architectures (Chapters 5-12)

Next, we explore the fundamental agent types that serve as building blocks for more complex systems:

    • Chapter 5: Foundational Cognitive Architectures covers the basic decision-making, planning, and memory systems that form the core of intelligent agents.
    • Chapter 6: Information Retrieval & Knowledge Agents explores how agents interact with external knowledge sources.
    • Chapter 7: Tool Manipulation & Orchestration Agents examines systems that coordinate tools, functions, and other agents.
    • Chapter 8: Data Analysis & Reasoning Agents focuses on agents that process information and draw insights.
    • Chapter 9: Software Development Agents covers systems that assist in code creation and maintenance.
    • Chapter 10: Conversational & Content Creation Agents explores agents that generate and manage different forms of content.
    • Chapter 11: Multi-Modal Perception Agents examines agents that process multiple forms of input data.
    • Chapter 12: Ethical & Explainable Agents focuses on systems designed with transparency and values alignment.

Domain-Specific Applications (Chapters 13-16)

Finally, we apply these core architectures to transform specific domains:

    • Chapter 13: Healthcare & Scientific Agents explores applications in medical care and scientific research.
    • Chapter 14: Financial & Legal Domain Agents examines systems for regulated industries.
    • Chapter 15: Education & Knowledge Agents covers applications in learning and knowledge transfer.
    • Chapter 16: Embodied & Physical World Agents focuses on systems that bridge digital intelligence with physical environments.

---

### Software and Hardware Requirements

| Requirement  | Details                                                                                                                                                                                    |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **OS**       | macOS, Windows, or Linux                                                                                                                                                                   |
| **RAM**      | 8 GB minimum; 16 GB recommended                                                                                                                                                            |
| **Python**   | 3.10 or later                                                                                                                                                                              |
| **GPU**      | NVIDIA GPU with CUDA 12+ (recommended, not required)                                                                                                                                       |
| **Tools**    | git, terminal, virtual environment tool (venv, conda, or uv)                                                                                                                               |
| **API Keys** | **None required** — every chapter runs in Simulation Mode with built-in MockLLM responses. Optional: OpenAI, Anthropic, or Google API key unlocks Live Mode. Local Ollama requires no key. |
| **Ollama**   | Optional — for local LLM mode: [install Ollama](https://ollama.com), then `ollama pull deepseek-v2:16b` and `ollama pull llama3.1:8b`. 16 GB+ RAM recommended.                             |

<br/>

## OpenAI Compatible URLs

<br/>

```python
ANTHROPIC_BASE_URL = "https://api.anthropic.com/v1/"
DEEPSEEK_BASE_URL = "https://api.deepseek.com/v1"
GEMINI_BASE_URL = "https://generativelanguage.googleapis.com/v1beta/openai/"
GITHUB_BASE_URL = "https://models.github.ai/inference"
GROQ_BASE_URL = "https://api.groq.com/openai/v1"
GROK_BASE_URL = "https://api.x.ai/v1"
OPENROUTER_BASE_URL = "https://openrouter.ai/api/v1"
OLLAMA_BASE_URL = "http://localhost:11434/v1"
```

<br/>

```python
BASE_URL_GITHUB = "https://models.github.ai/inference"
BASE_URL = BASE_URL_GITHUB
MODEL_GPT_4o_MINI = "gpt-4o-mini"
MODEL_LLAMA = "Llama-3.3-70B-Instruct"
MODEL_NAME = MODEL_GPT_4o_MINI
API_KEY = "github_pat_"
```

<br/>

## GitHub Models

https://github.com/marketplace/models

---

## The 30 Agents at a Glance

|  #  | Agent                                                                                         | Chapter                                         |
| :-: | --------------------------------------------------------------------------------------------- | ----------------------------------------------- |
|  1  | [The Autonomous Decision-Making Agent](chapter05/ch05_foundational_architectures.ipynb)       | Ch 5: Foundational Cognitive Architectures      |
|  2  | [The Planning Agent](chapter05/ch05_foundational_architectures.ipynb)                         | Ch 5: Foundational Cognitive Architectures      |
|  3  | [The Memory-Augmented Agent](chapter05/ch05_foundational_architectures.ipynb)                 | Ch 5: Foundational Cognitive Architectures      |
|  4  | [The Knowledge Retrieval Agent](chapter06/ch06_knowledge_agents.ipynb)                        | Ch 6: Information Retrieval & Knowledge Agents  |
|  5  | [The Document Intelligence Agent](chapter06/ch06_knowledge_agents.ipynb)                      | Ch 6: Information Retrieval & Knowledge Agents  |
|  6  | [The Scientific Research Agent](chapter06/ch06_knowledge_agents.ipynb)                        | Ch 6: Information Retrieval & Knowledge Agents  |
|  7  | [The Tool-Using Agent](chapter07/ch07_tool_orchestration.ipynb)                               | Ch 7: Tool Manipulation & Orchestration Agents  |
|  8  | [The Chain-of-Agents Orchestrator](chapter07/ch07_tool_orchestration.ipynb)                   | Ch 7: Tool Manipulation & Orchestration Agents  |
|  9  | [The Agentic Workflow System](chapter07/ch07_tool_orchestration.ipynb)                        | Ch 7: Tool Manipulation & Orchestration Agents  |
| 10  | [The Data Analysis Agent](chapter08/ch08_data_analysis_reasoning_agents.ipynb)                | Ch 8: Data Analysis & Reasoning Agents          |
| 11  | [The Verification and Validation Agent](chapter08/ch08_data_analysis_reasoning_agents.ipynb)  | Ch 8: Data Analysis & Reasoning Agents          |
| 12  | [The General Problem Solver](chapter08/ch08_data_analysis_reasoning_agents.ipynb)             | Ch 8: Data Analysis & Reasoning Agents          |
| 13  | [The Code-Generation Agent](chapter09/ch09_software_dev_agents.ipynb)                         | Ch 9: Software Development Agents               |
| 14  | [The Security-Hardened Agent](chapter09/ch09_software_dev_agents.ipynb)                       | Ch 9: Software Development Agents               |
| 15  | [The Self-Improving Agent](chapter09/ch09_software_dev_agents.ipynb)                          | Ch 9: Software Development Agents               |
| 16  | [The Conversational Agent](chapter10/ch10_conversational_and_content_creation_agents.ipynb)   | Ch 10: Conversational & Content Creation Agents |
| 17  | [The Content Creation Agent](chapter10/ch10_conversational_and_content_creation_agents.ipynb) | Ch 10: Conversational & Content Creation Agents |
| 18  | [The Recommendation Agent](chapter10/ch10_conversational_and_content_creation_agents.ipynb)   | Ch 10: Conversational & Content Creation Agents |
| 19  | [The Vision-Language Agent](chapter11/ch11_multimodal_agents.ipynb)                           | Ch 11: Multi-Modal Perception Agents            |
| 20  | [The Audio Processing Agent](chapter11/ch11_multimodal_agents.ipynb)                          | Ch 11: Multi-Modal Perception Agents            |
| 21  | [The Physical World Sensing Agent](chapter11/ch11_multimodal_agents.ipynb)                    | Ch 11: Multi-Modal Perception Agents            |
| 22  | [The Ethical Reasoning Agent](chapter12/ch12_01_ethical_reasoning_agent.ipynb)                | Ch 12: Ethical & Explainable Agents             |
| 23  | [The Explainable Agent](chapter12/ch12_02_explainable_agent.ipynb)                            | Ch 12: Ethical & Explainable Agents             |
| 24  | [The Healthcare Intelligence Agent](chapter13/ch13_healthcare_scientific_agents.ipynb)        | Ch 13: Healthcare & Scientific Agents           |
| 25  | [The Scientific Discovery Agent](chapter13/ch13_healthcare_scientific_agents.ipynb)           | Ch 13: Healthcare & Scientific Agents           |
| 26  | [The Financial Advisory Agent](chapter14/ch14_financial_legal_agents.ipynb)                   | Ch 14: Financial & Legal Domain Agents          |
| 27  | [The Legal Intelligence Agent](chapter14/ch14_financial_legal_agents.ipynb)                   | Ch 14: Financial & Legal Domain Agents          |
| 28  | [The Education Intelligence Agent](chapter15/ch15_education_and_knowledge_agents.ipynb)       | Ch 15: Education & Knowledge Agents             |
| 29  | [The Collective Intelligence Agent](chapter15/ch15_education_and_knowledge_agents.ipynb)      | Ch 15: Education & Knowledge Agents             |
| 30  | [The Embodied Intelligence Agent](chapter16/ch16_embodied_agents.ipynb)                       | Ch 16: Embodied & Physical World Agents         |
