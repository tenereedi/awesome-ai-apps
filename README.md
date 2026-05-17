# 🤖 Awesome AI Apps

> A curated collection of awesome AI-powered applications built with various frameworks and tools.

[![Lint](https://github.com/awesome-ai-apps/awesome-ai-apps/actions/workflows/lint.yml/badge.svg)](https://github.com/awesome-ai-apps/awesome-ai-apps/actions/workflows/lint.yml)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/awesome-ai-apps/awesome-ai-apps/blob/main/.github/PULL_REQUEST_TEMPLATE.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📖 Overview

This repository is a fork of [Arindam200/awesome-ai-apps](https://github.com/Arindam200/awesome-ai-apps) and contains a growing collection of AI-powered applications, demos, and examples. Each app is self-contained and demonstrates different use cases of modern AI tools and frameworks.

> **Personal note:** I'm using this fork primarily to learn LangChain and experiment with RAG pipelines. Most of my additions will live under `apps/rag/`. Currently working through the LangChain docs and porting the examples here as I go — starting with a basic PDF Q&A app.

## 🗂️ Project Structure

```
awesome-ai-apps/
├── .github/                  # GitHub templates and workflows
│   ├── ISSUE_TEMPLATE/       # Issue templates (bug, feature, question)
│   ├── workflows/            # CI/CD workflows
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── README_TEMPLATE.md
├── apps/                     # Individual AI applications
│   ├── chatbots/             # Conversational AI apps
│   ├── agents/               # Autonomous AI agents
│   ├── rag/                  # Retrieval-Augmented Generation apps
│   └── multimodal/           # Vision + language apps
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Python 3.9+
- pip or uv package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/awesome-ai-apps/awesome-ai-apps.git
   cd awesome-ai-apps
   ```

2. **Navigate to an app directory**

   ```bash
   cd apps/chatbots/my-chatbot
   ```

3. **Follow the app-specific README** for setup and running instructions.

## 📦 Apps

| App | Description | Framework | Status |
|-----|-------------|-----------|--------|
| [PDF Q&A](apps/rag/pdf-qa/) | Ask questions about a PDF using LangChain + FAISS | LangChain | 🚧 WIP |
| Coming Soon | More apps being added! | — | 🔜 |

## 🤝 Contributing

We welcome contributions! Please check out our guidelines before submitting.

1. **Fork** the repository
2. **Create** a new branch (`git checkout -b feat/my-new-app`)
3. **Add** your app following the [README template](.github/README_TEMPLATE.md)
4. **Commit** your changes
5. **Open** a Pull Request

> 📝 Each app must include its own `README.md` based on the [README template](.github/README_TEMPLATE.md).

For bugs, features, or questions, please use the appropriate [issue template](https://github.com/awesome-ai-apps/awesome-ai-apps/issues/new/choose).

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## ⭐ Ac
