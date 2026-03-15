# Building Effective Agents

A comprehensive guide to designing and implementing LLM-based agentic systems — from simple augmented LLMs to fully autonomous agents.

## About

This guide synthesizes Anthropic's original "Building Effective Agents" article (December 2024) with subsequent publications on context engineering, tool design, and long-running agents, updated for the current state of the art (March 2026).

It covers workflow patterns, autonomous agent design, context engineering, tool design, MCP, security, evaluation, and common pitfalls — with practical recommendations grounded in real-world engineering experience.

## Contents

The guide is organized into 11 chapters and 3 appendices:

1. **Introduction** — audience, philosophy, key definitions
2. **The Augmented LLM** — retrieval, tools, and memory as building blocks
3. **Workflow Patterns** — prompt chaining, routing, parallelization, orchestrator-workers, evaluator-optimizer
4. **Autonomous Agents** — the agent loop, planning, error recovery, human-in-the-loop
5. **Context Engineering** — just-in-time retrieval, context rot, long-horizon techniques
6. **Designing Tools for Agents** — tool design principles, MCP, eval-driven development
7. **Long-Running Agents** — multi-session problems, state management, verification
8. **Agentic Security and Safety** — prompt injection, sandboxing, least privilege
9. **Practical Applications** — customer support, coding agents, research, business workflows
10. **Evaluation and Iteration** — designing evals, metrics, the iterative loop
11. **Common Pitfalls and Anti-Patterns**

## How This Was Made

This document was curated by [Shyam Yadati](mailto:shyam@machinedge.io) and drafted with the assistance of multiple LLMs: Claude Opus 4.6 (Anthropic), ChatGPT 5.4 Thinking (OpenAI), and Gemini 3 Thinking (Google). All factual claims should be verified against primary sources before being cited in other work.

## License

This work is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). See [LICENSE](LICENSE) for details.
