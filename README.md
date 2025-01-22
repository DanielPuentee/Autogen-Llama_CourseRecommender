# LangGraph + Mistral: CV Evaluator Agent System

<img title="Logo" alt="Alt text" src="/imgs/cover_page.png">

![GitHub top language](https://img.shields.io/github/languages/top/DanielPuentee/autogen-groq-multiagent-analyser)
[![Visual Studio Code](https://custom-icon-badges.demolab.com/badge/Visual%20Studio%20Code-0078d7.svg?logo=vsc&logoColor=white)](#)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#)
[![Anaconda](https://img.shields.io/badge/Anaconda-44A833?logo=anaconda&logoColor=fff)](#)
![GitHub last commit](https://img.shields.io/github/last-commit/DanielPuentee/autogen-groq-multiagent-analyser)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-000?logo=githubcopilot&logoColor=fff)](#)

> Author: [Daniel Puente Viejo](https://www.linkedin.com/in/danielpuenteviejo/)

## Description
This repository demonstrates how to build and execute a multi-agent system using **Autogen** and free LLMs with **Groq**. It serves as a step-by-step tutorial to help users understand the basics of multi-agent systems, tool integration, and hybrid agent selection methods.

---

## Features
- **Multi-Agent Setup**: Includes agents for analyzing CVs, extracting skills, recommending courses, and verifying task completion.
- **Hybrid Agent Selection**: Implements a custom method for dynamically selecting the next agent based on the task flow.
- **Tool Integration**: Demonstrates how to use external tools for processing tasks.
- **Custom Configuration**: Allows experimentation with LLM configurations like `llama31` and `gemma2` for optimized performance.

---

## Requirements
- Python used version: **3.10.15**
- Dependencies listed in `requirements.txt`
- API Key for **Groq**
- `.env` file with the following variable:
  ```plaintext
  GROQ_API_KEY=<your_api_key>
    ```

```python
pip install -r requirements.txt
```

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
