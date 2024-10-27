<p align="center">
  <img src="https://raw.githubusercontent.com/Sunwood-ai-labs/swarm-sample-box/refs/heads/main/docs/swarm-sample-box.png" width="100%">
  <h1 align="center">🌟 swarm-sample-box 🌟</h1>
</p>

<p align="center">
  <a href="https://github.com/Sunwood-ai-labs/swarm-sample-box">
    <img alt="GitHub Repo" src="https://img.shields.io/badge/github-swarm__sample__box-blue?logo=github">
  </a>
  <a href="https://github.com/Sunwood-ai-labs/swarm-sample-box/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/github/license/Sunwood-ai-labs/swarm-sample-box?color=green">
  </a>
  <a href="https://github.com/Sunwood-ai-labs/swarm-sample-box/stargazers">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/Sunwood-ai-labs/swarm-sample-box?style=social">
  </a>
  <a href="https://github.com/Sunwood-ai-labs/swarm-sample-box/releases">
    <img alt="GitHub release" src="https://img.shields.io/github/v/release/Sunwood-ai-labs/swarm-sample-box?include_prereleases&style=flat-square">
  </a>
  <a href="https://github.com/Sunwood-ai-labs/swarm-sample-box/graphs/commit-activity">
    <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/Sunwood-ai-labs/swarm-sample-box">
  </a>
  <a href="https://github.com/Sunwood-ai-labs/swarm-sample-box/pulls">
    <img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square">
  </a>
  <!-- Keep all badges -->
</p>

<h2 align="center">
  ～ Experimental Playground for AI Agent Orchestration ～

  <a href="https://github.com/Sunwood-ai-labs/swarm-sample-box/blob/main/README.md"><img src="https://img.shields.io/badge/ドキュメント-日本語-white.svg" alt="JA doc"/></a>
  <a href="https://github.com/Sunwood-ai-labs/swarm-sample-box/blob/main/docs/README.en.md"><img src="https://img.shields.io/badge/english-document-white.svg" alt="EN doc"></a>
</h2>

> [!IMPORTANT]
>  swarm-sample-box is a template repository developed using [cline (formerly Claude Dev)](https://github.com/clinebot/cline), [SourceSage](https://github.com/Sunwood-ai-labs/SourceSage), and [claude.ai](https://claude.ai/). Most of the release notes, README, and commit messages are generated using the latest AI technology.


## 🚀 Project Overview

Swarm Sample Box is an AI agent experimental repository that utilizes [Swarm, an experimental multi-agent orchestration framework developed by OpenAI](https://github.com/openai/swarm). This repository provides a lightweight and flexible solution for efficiently coordinating multiple AI agents to perform complex tasks, supporting developers' research and experimentation. Version: v1.7.0

## ✨ Main Features

1. Diverse Agent Samples: Provides implementation examples of various AI agents, from basic dialogue to complex task processing.
2. Flexible Customization: Each sample can be easily extended and modified to adapt to your own use cases.
3. Integrated Experimental Environment: Provides a practical experimental environment, including Docker environment and integration with vector databases (Qdrant).
4. Automated Evaluation Function: Some samples include automated evaluation scripts to measure agent performance.
5. Swarm Framework Requirements Definition Prompt: `docs/SWARM_REQUIREMENTS_DEFINITION_PROMPT_V1.md` provides a prompt to assist in building AI agent systems.

## 🔧 Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Sunwood-ai-labs/swarm-sample-box.git
   cd swarm-sample-box
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Linux/macOS
   .venv\Scripts\activate  # Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set the OpenAI API key:
   ```bash
   export OPENAI_API_KEY="your-api-key"
   ```

5. Run a specific sample:
   ```bash
   cd examples/<sample name>
   python main.py # or run.py
   ```


## 📦 Installation Instructions

Refer to the "Usage" section for instructions on how to install and use swarm-sample-box.


## 🆕 What's New

- Added a structured requirements definition prompt to assist in building AI agent systems using the Swarm framework. (`docs/SWARM_REQUIREMENTS_DEFINITION_PROMPT_V1.md`)
- Improved existing sample code and README.


## 📚 Sample List


### Official Samples (Translated to Japanese)

(The number of 🔥 represents the relative complexity and learning curve of each sample.)

1. [Basic](https://github.com/Sunwood-ai-labs/swarm-sample-box/tree/main/examples/basic) 🔥: A minimal implementation example that introduces the basic functions of Swarm.

2. [Weather Agent](https://github.com/Sunwood-ai-labs/swarm-sample-box/tree/main/examples/weather_agent) 🔥🔥: An implementation example of a simple agent that retrieves weather information and performs related tasks.

3. [Triage Agent](https://github.com/Sunwood-ai-labs/swarm-sample-box/tree/main/examples/triage_agent) 🔥🔥: An implementation example of a triage agent that directs user requests to the appropriate agent.

4. [Personal Shopper](https://github.com/Sunwood-ai-labs/swarm-sample-box/tree/main/examples/personal_shopper) 🔥🔥🔥: An implementation example of a personal shopping assistant agent.

5. [Airline](https://github.com/Sunwood-ai-labs/swarm-sample-box/tree/main/examples/airline) 🔥🔥🔥🔥: A multi-agent setup simulating an airline's customer service.

6. [Support Bot](https://github.com/Sunwood-ai-labs/swarm-sample-box/tree/main/examples/support_bot) 🔥🔥🔥🔥🔥: An implementation example of a customer support bot, including document search functionality using Qdrant.

7. [Experimental??: Customer Service Streaming](https://github.com/Sunwood-ai-labs/swarm-sample-box/tree/main/examples/customer_service_streaming) 🔥🔥🔥🔥🔥: A sample simulating customer service in a streaming format.


### Original Samples

This section will introduce originally developed samples.  Currently under preparation, so please wait for future updates.

- [In preparation] New original sample 1: Details coming soon
- [In preparation] New original sample 2: Details coming soon

## 🚀 Swarm Official Sample Tutorial

<!-- Tutorial section unchanged -->

## 🧪 Evaluation Method

Some samples include automated evaluation scripts. To run the evaluation, execute the following command in the sample directory:

```bash
pytest evals.py
```


## 📄 License

Swarm Sample Box is released under the [MIT License](LICENSE).

## 🙏 Acknowledgements

This project is based on the Swarm framework developed by OpenAI. We deeply appreciate the developers of Swarm. Contributors to this release: Maki, iris-s-coon


---

Start developing and experimenting with innovative AI agent systems using Swarm Sample Box!  For detailed usage instructions and explanations of each sample, please refer to the README file in the corresponding directory.
```