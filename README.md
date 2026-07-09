# Awesome LangGraph Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of production-ready AI agents built with [LangGraph](https://www.langchain.com/langgraph).

## Contents

- [Knowledge & RAG](#knowledge--rag)
- [Research & Search](#research--search)
- [Data & Databases](#data--databases)
- [Documents & Content](#documents--content)
- [Developer Tools](#developer-tools)
- [Browser & Automation](#browser--automation)
- [Integrations](#integrations)
- [Utilities](#utilities)
- [What is langgraph?](#what-is-langgraph)
- [Contributing](#contributing)
- [Code of Conduct](#code-of-conduct)

## Knowledge & RAG

- **[Chat with PDF Agent](https://agentcn.run/docs/agents/langgraph/chat-with-pdf)** — Agent that indexes a PDF into a vector store and answers questions over it with page-cited retrieval.
- **[Company Knowledge Agent](https://agentcn.run/docs/agents/langgraph/company-knowledge)** — Agent that indexes internal documents into a vector store and answers questions over them, with a scheduled re-index workflow and PII redaction.
- **[Docs Chatbot Agent](https://agentcn.run/docs/agents/langgraph/docs-chatbot)** — Agent that answers questions about a library's functions by looking up structured documentation.

## Research & Search

- **[Deep Search Agent](https://agentcn.run/docs/agents/langgraph/deep-search)** — Agent that fans research out to searcher and evaluator subagents, iterating through a bounded workflow until the answer is cited and complete.
- **[Docs Expert Agent](https://agentcn.run/docs/agents/langgraph/docs-expert)** — Agent that answers questions about libraries and APIs by searching the live web and citing sources.
- **[AI SEO Audit Agent](https://agentcn.run/docs/agents/langgraph/ai-seo-audit)** — Agent that fetches a page and scores its readability to AI answer engines across six categories, returning failing checks and an agent-ready fix prompt.

## Data & Databases

- **[Chat with Database Agent](https://agentcn.run/docs/agents/langgraph/text-to-sql)** — Agent that introspects a database schema, converts questions to SQL, and runs read-only queries.
- **[CSV to Questions Agent](https://agentcn.run/docs/agents/langgraph/csv-to-questions)** — Agent that chains a summarizer and a question-generator through a workflow to turn a CSV into analytical questions.
- **[Google Sheets Analysis Agent](https://agentcn.run/docs/agents/langgraph/google-sheets)** — Agent that reads, analyzes, and edits Google Sheets via the Sheets API.

## Documents & Content

- **[Meeting Notes Agent](https://agentcn.run/docs/agents/langgraph/meeting-notes)** — Agent that runs a transcript through a workflow to return a structured summary, decisions, and action items.
- **[Customer Feedback Summary Agent](https://agentcn.run/docs/agents/langgraph/feedback-summary)** — Agent that retrieves, categorizes, and summarizes customer feedback into an executive report with recommendations.
- **[Flash Cards from PDF Agent](https://agentcn.run/docs/agents/langgraph/flashcards-pdf)** — Agent that turns a PDF into study flash cards through a workflow, with optional AI-generated images per concept.
- **[Chat with YouTube Agent](https://agentcn.run/docs/agents/langgraph/chat-with-youtube)** — Agent that fetches a video's metadata and transcript, then answers questions with clickable timestamp citations.
- **[Extract DESIGN.md Agent](https://agentcn.run/docs/agents/langgraph/extract-design-md)** — Agent that pulls a site's design tokens, brand assets, screenshot, and page Markdown and composes a self-contained DESIGN.md design-system document.

## Developer Tools

- **[GitHub PR Code Review Agent](https://agentcn.run/docs/agents/langgraph/github-review)** — Agent that fetches a GitHub pull request and returns adaptive review feedback, with a workflow that emits a typed review.

## Browser & Automation

- **[Browser Agent](https://agentcn.run/docs/agents/langgraph/browser-agent)** — Agent that drives a real browser with Playwright using a snapshot-and-selector pattern to complete web tasks.
- **[Claw Autonomous Assistant](https://agentcn.run/docs/agents/langgraph/claw)** — Agent that operates a sandboxed workspace — read/write files and run shell commands — to finish multi-step tasks.

## Integrations

- **[Slack Agent](https://agentcn.run/docs/agents/langgraph/slack-agent)** — Agent that replies to Slack mentions and DMs, threaded, via the Slack Web API.

## Utilities

- **[Weather Agent](https://agentcn.run/docs/agents/langgraph/weather)** — Agent that looks up current weather for a location via the Open-Meteo API.

## What is LangGraph?

LangGraph is a low-level orchestration framework for building controllable agents as graphs. It provides customizable architectures, long-term memory, and human-in-the-loop to reliably handle complex tasks.

Learn more at [langchain.com/langgraph](https://www.langchain.com/langgraph).

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold it.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the authors have waived all copyright and related or neighboring rights to this work.
