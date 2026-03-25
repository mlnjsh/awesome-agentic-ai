# Awesome Agentic AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of frameworks, papers, tools, and resources for building autonomous AI agents.

Agentic AI refers to AI systems that can autonomously plan, reason, use tools, and take actions to accomplish complex goals with minimal human intervention.

---

## Contents

- [Frameworks and Libraries](#frameworks-and-libraries)
- [Agent Architectures](#agent-architectures)
- [Multi-Agent Systems](#multi-agent-systems)
- [Tool Use and Function Calling](#tool-use-and-function-calling)
- [Memory and RAG for Agents](#memory-and-rag-for-agents)
- [Planning and Reasoning](#planning-and-reasoning)
- [Code Generation Agents](#code-generation-agents)
- [Web and Browser Agents](#web-and-browser-agents)
- [Evaluation and Benchmarks](#evaluation-and-benchmarks)
- [Safety and Alignment](#safety-and-alignment)
- [Tutorials and Courses](#tutorials-and-courses)
- [Key Papers](#key-papers)

---

## Frameworks and Libraries

| Framework | Language | Description |
|-----------|----------|-------------|
| [LangChain](https://github.com/langchain-ai/langchain) | Python/JS | Most popular framework for building LLM-powered applications and agents |
| [LangGraph](https://github.com/langchain-ai/langgraph) | Python/JS | Stateful, multi-actor agent workflows as graphs |
| [CrewAI](https://github.com/crewAIInc/crewAI) | Python | Orchestrating role-playing autonomous AI agents |
| [AutoGen](https://github.com/microsoft/autogen) | Python | Microsoft multi-agent conversation framework |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | C#/Python | Microsoft SDK for integrating LLMs with conventional programming |
| [Haystack](https://github.com/deepset-ai/haystack) | Python | End-to-end NLP/LLM framework with agent support |
| [DSPy](https://github.com/stanfordnlp/dspy) | Python | Stanford framework for programming (not prompting) LLMs |
| [Phidata](https://github.com/phidatahq/phidata) | Python | AI assistants with memory, knowledge, and tools |
| [Agency Swarm](https://github.com/VRSEN/agency-swarm) | Python | Collaborative AI agent swarms |
| [Smolagents](https://github.com/huggingface/smolagents) | Python | Hugging Face lightweight agent library |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | Python | OpenAI SDK for multi-agent workflows |
| [LlamaIndex](https://github.com/run-llama/llama_index) | Python | Data framework with agent capabilities |
| [Composio](https://github.com/ComposioHQ/composio) | Python/JS | 250+ tool integrations for AI agents |
| [BabyAGI](https://github.com/yoheinakajima/babyagi) | Python | Task-driven autonomous agent |
| [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) | Python | Open-source autonomous AI agent framework |
| [Agno](https://github.com/agno-agi/agno) | Python | Lightweight multimodal agent library |

## Agent Architectures

- [ReAct](https://arxiv.org/abs/2210.03629) - Synergizing reasoning and acting in language models. The foundational Reason+Act paradigm.
- [Plan-and-Execute](https://blog.langchain.dev/planning-agents/) - Separate planning from execution for complex tasks.
- [Tree of Thoughts (ToT)](https://arxiv.org/abs/2305.10601) - Tree-structured exploration of reasoning paths.
- [Reflexion](https://arxiv.org/abs/2303.11366) - Agents that learn from verbal self-reflection.
- [LATS](https://arxiv.org/abs/2310.04406) - Language Agent Tree Search combining planning, acting, and reasoning.
- [CoALA](https://arxiv.org/abs/2309.02427) - Cognitive Architectures for Language Agents.
- [REWOO](https://arxiv.org/abs/2305.18323) - Decoupling reasoning from observations for efficient tool use.
- [Self-Ask](https://arxiv.org/abs/2210.03350) - Decomposing complex questions into sub-questions.

## Multi-Agent Systems

- [MetaGPT](https://github.com/geekan/MetaGPT) - Multi-agent framework mimicking a software company with roles (PM, architect, engineer).
- [ChatDev](https://github.com/OpenBMB/ChatDev) - Communicative agents collaborating to build software.
- [CAMEL](https://github.com/camel-ai/camel) - Communicative Agents for Mind Exploration of LLM Society.
- [Swarm](https://github.com/openai/swarm) - OpenAI educational multi-agent orchestration framework.
- [GPT Researcher](https://github.com/assafelovic/gpt-researcher) - Autonomous agent for comprehensive online research.
- [MegaAgent](https://arxiv.org/abs/2408.09955) - Autonomous cooperation in large-scale LLM agent systems.

## Tool Use and Function Calling

- [Gorilla](https://github.com/ShishirPatil/gorilla) - LLM connected with massive APIs.
- [ToolLLM](https://arxiv.org/abs/2307.16789) - LLMs mastering 16000+ real-world APIs.
- [Toolformer](https://arxiv.org/abs/2302.04761) - Language models that teach themselves to use tools.
- [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) - Anthropic open standard for connecting AI to tools.
- [TaskWeaver](https://github.com/microsoft/TaskWeaver) - Code-first agent framework for data analytics.
- [AnyTool](https://arxiv.org/abs/2402.04253) - Self-reflective agent for utilizing 16,000+ APIs.

## Memory and RAG for Agents

- [MemGPT / Letta](https://github.com/letta-ai/letta) - LLMs with self-editing memory for unbounded context.
- [Mem0](https://github.com/mem0ai/mem0) - Self-improving memory layer for LLM applications.
- [ChromaDB](https://github.com/chroma-core/chroma) - Open-source embedding database.
- [Weaviate](https://github.com/weaviate/weaviate) - Vector database for semantic search.
- [FAISS](https://github.com/facebookresearch/faiss) - Efficient similarity search library by Meta.
- [RAGFlow](https://github.com/infiniflow/ragflow) - RAG engine with deep document understanding.
- [Cognee](https://github.com/topoteretes/cognee) - Memory management using knowledge graphs.

## Planning and Reasoning

- [Chain-of-Thought](https://arxiv.org/abs/2201.11903) - Step-by-step reasoning in LLMs.
- [Self-Consistency](https://arxiv.org/abs/2203.11171) - Multiple reasoning paths with majority vote.
- [Graph of Thoughts](https://arxiv.org/abs/2308.09687) - Reasoning as arbitrary graph structures.
- [Algorithm of Thoughts](https://arxiv.org/abs/2308.10379) - Enhanced idea exploration in LLMs.
- [Reasoning via Planning (RAP)](https://arxiv.org/abs/2305.14992) - LLMs as world model and reasoning agent.

## Code Generation Agents

- [SWE-Agent](https://github.com/princeton-nlp/SWE-agent) - Autonomous coding agent for GitHub issues.
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - Open-source AI software development agents.
- [Aider](https://github.com/paul-gauthier/aider) - AI pair programmer in the terminal.
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - Anthropic agentic coding tool.
- [GPT Engineer](https://github.com/gpt-engineer-org/gpt-engineer) - Specify what you want, AI builds it.

## Web and Browser Agents

- [WebArena](https://github.com/web-arena-x/webarena) - Realistic web environment for autonomous agents.
- [BrowserGym](https://github.com/ServiceNow/BrowserGym) - Gym environment for web task automation.
- [LaVague](https://github.com/lavague-ai/LaVague) - Large action model framework for web automation.
- [WebVoyager](https://arxiv.org/abs/2401.13919) - End-to-end web agent with large multimodal models.
- [Mind2Web](https://arxiv.org/abs/2306.06070) - Generalist agent for the web.

## Evaluation and Benchmarks

- [AgentBench](https://github.com/THUDM/AgentBench) - Evaluating LLMs as agents across 8 environments.
- [SWE-bench](https://github.com/princeton-nlp/SWE-bench) - Real-world software engineering evaluation.
- [GAIA](https://arxiv.org/abs/2311.12983) - General AI assistant benchmark.
- [ToolBench](https://github.com/OpenBMB/ToolBench) - Tool-using LLM evaluation framework.
- [Tau-Bench](https://github.com/sierra-research/tau-bench) - Tool-agent-user interaction benchmark.
- [HumanEval](https://github.com/openai/human-eval) - Code generation benchmark.

## Safety and Alignment

- [Constitutional AI](https://arxiv.org/abs/2212.08073) - Training harmless AI through self-improvement.
- [Guardrails AI](https://github.com/guardrails-ai/guardrails) - Adding guardrails to LLM outputs.
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) - NVIDIA toolkit for controllable AI.
- [LLM Guard](https://github.com/protectai/llm-guard) - Security toolkit for LLM interactions.
- [Toolemu](https://arxiv.org/abs/2309.15817) - Identifying risks of LM agents.

## Tutorials and Courses

- [LangChain Academy](https://academy.langchain.com/) - Free courses on LangChain and LangGraph.
- [Hugging Face Agents Course](https://huggingface.co/learn/agents-course) - Free course on building AI agents.
- [LLM Agents MOOC (Berkeley)](https://llmagents-learning.org/f24) - UC Berkeley LLM agents course.
- [DeepLearning.AI Multi-AI Agent Systems](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/) - CrewAI short course.
- [Anthropic Agent Guide](https://docs.anthropic.com/en/docs/build-with-claude/agentic) - Official guide for Claude agents.

## Key Papers

### 2025
- [Building Effective Agents (Anthropic)](https://www.anthropic.com/research/building-effective-agents) - Practical guide to effective LLM agents.

### 2024
- [Agent-as-a-Judge](https://arxiv.org/abs/2410.10934) - Using agentic systems to evaluate agentic systems.
- [AgentCoder](https://arxiv.org/abs/2312.13010) - Multi-agent code generation with iterative testing.
- [ADAS](https://arxiv.org/abs/2408.08435) - Automated design of agentic systems.

### 2023
- [ReAct](https://arxiv.org/abs/2210.03629) - Synergizing reasoning and acting in LLMs.
- [Reflexion](https://arxiv.org/abs/2303.11366) - Verbal reinforcement learning for agents.
- [Toolformer](https://arxiv.org/abs/2302.04761) - Self-taught tool use.
- [Voyager](https://arxiv.org/abs/2305.16291) - Open-ended embodied agent with LLMs.
- [Generative Agents](https://arxiv.org/abs/2304.03442) - Interactive simulacra of human behavior.
- [MetaGPT](https://arxiv.org/abs/2308.00352) - Meta programming for multi-agent collaboration.
- [MemGPT](https://arxiv.org/abs/2310.08560) - Towards LLMs as operating systems.

---

## Contributing

Contributions welcome! Please submit a PR. Add new entries at the end of the relevant section using format: `[Name](URL) - Brief description.`

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)


---

## Contributors & Domain Experts

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/mlnjsh">
        <img src="https://github.com/mlnjsh.png" width="80px;" alt="Milan Amrut Joshi"/><br />
        <sub><b>Milan Amrut Joshi</b></sub>
      </a><br />
      <sub>Project Author</sub>
    </td>
    <td align="center">
      <a href="https://github.com/e2b-dev">
        <img src="https://github.com/e2b-dev.png" width="80px;" alt="E2B"/><br />
        <sub><b>E2B</b></sub>
      </a><br />
      <sub>Code execution for AI agents</sub>
    </td>
    <td align="center">
      <a href="https://github.com/crewAIInc">
        <img src="https://github.com/crewAIInc.png" width="80px;" alt="CrewAI"/><br />
        <sub><b>CrewAI</b></sub>
      </a><br />
      <sub>Multi-agent AI framework</sub>
    </td>
  </tr>
</table>
