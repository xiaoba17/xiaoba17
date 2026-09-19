# Hi, I'm 小粑 (`@xiaoba17`) 👋

I build **AI systems and developer tools**, with a current focus on LLM inference,
heterogeneous runtimes, performance engineering, and reliable engineering workflows.

我主要关注大模型推理系统、异构计算后端、性能工程，以及让研发流程更可靠的开发者工具。

<p>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

> **Currently:** Exploring LLM scheduling, KV-cache correctness, and heterogeneous inference.

## What I'm working on

- **LLM inference & serving** — scheduling, KV-cache correctness, distributed execution,
  and high-performance serving paths in vLLM and InfiniLM.
- **AI runtimes from first principles** — tensors, operators, C APIs, and Qwen2 inference
  across CPU, NVIDIA, and CoreX backends.
- **Performance & observability** — hardware PMU-based runtime telemetry for the JVM and
  practical performance-analysis workflows.
- **Agentic developer tools** — repository-aware CI generation and evidence-backed deep
  research over large code and documentation trees.

## Selected projects

| Project | What it does | Stack |
| --- | --- | --- |
| [RepoFlow](https://github.com/xiaoba17/repoflow) | Detects a repository's language, framework, package manager, and commands, then generates a conservative GitHub Actions workflow. Supports Node.js, Python, and Go projects. | TypeScript, Node.js, GitHub Actions |
| [Ancoder Deep Research](https://github.com/AncoderAI/Ancoder_DeepResearch_CLI) | Searches code repositories and document trees using dynamic skill generation, multi-round cross-validation, and a test-driven optimization loop. | TypeScript, Node.js, agentic workflows |
| [Auto Trader Demo](https://github.com/xiaoba17/auto_trader_demo) | A research-oriented A-share backtesting toolkit with market constraints, risk controls, parameter search, walk-forward validation, and live screening. | Python, BaoStock, quantitative research |
| [LLAISYS](https://github.com/xiaoba17/llaisys) | Builds an educational AI runtime from tensors and CPU operators through Qwen2 inference, with NVIDIA and CoreX backends. | C++, Python, CUDA/CoreX, XMake |

## Recent systems work

- **[vLLM](https://github.com/xiaoba17/vllm)** — fixed DFlash draft KV-cache group
  annotations and improved executor shutdown behavior during collective RPC.
- **[InfiniLM](https://github.com/xiaoba17/InfiniLM)** — implemented priority-aware
  request scheduling for the inference engine.
- **[BiSheng JDK 17](https://gitcode.com/openeuler/bishengjdk-17)** — developed runtime
  telemetry for Arm PMU events, including optional counters and event-group rotation.
- **[LLAISYS](https://github.com/xiaoba17/llaisys)** — implemented tensor operations,
  CPU operators, Qwen2 inference, and NVIDIA/CoreX runtime backends.
