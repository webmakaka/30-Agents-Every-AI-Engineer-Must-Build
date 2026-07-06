# Chapter 01: Foundations of Agent Engineering

## Overview

This repository is the executable companion to **Chapter 1** of _AI Agents_. It transforms the chapter's theoretical foundations into runnable Python code, covering the cognitive loop, agent brain patterns, interoperability protocols, interaction paradigms, the Agentic AI Progression Framework, and real-world business case studies.

Every code cell runs **without an API key** in Simulation Mode, powered by a `MockLLM` engine that returns chapter-derived responses. When an API key is provided (OpenAI, Anthropic, or Google) or Ollama is running locally, the notebook seamlessly switches to Live Mode. Each provider has its own pre-executed notebook variant.

## Quickstart

```bash
# 1. Clone the repository
$ git clone https://github.com/webmakaka/30-Agents-Every-AI-Engineer-Must-Build.git
$ cd ./30-Agents-Every-AI-Engineer-Must-Build/
$ cd 01.\ Foundations\ of\ Agent\ Engineering/


# 2. Create a virtual environment (recommended)
$ uv venv
$ source .venv/bin/activate   # Linux/Mac

# 3. Install dependencies
$ uv pip install -r requirements.txt
$ uv pip install -r requirements-openai.txt    # For OpenAI GPT-4o

# 5. Launch the notebook
# $ uv run jupyter notebook ch01_foundations_of_agent_engineering__RUN_OPENAI_GPT4o.ipynb
```
