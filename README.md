# Hi, I'm 小粑 (`@xiaoba17`) 👋

I build **AI systems and developer tools**, with a current focus on LLM inference,
heterogeneous runtimes, performance engineering, and reliable engineering workflows.

我主要关注大模型推理系统、异构计算后端、性能工程，以及让研发流程更可靠的开发者工具。

## What I'm working on

- **LLM inference & serving** — scheduling, KV-cache correctness, distributed execution,
  and high-performance serving paths in vLLM and InfiniLM.
- **AI runtimes from first principles** — tensors, operators, C APIs, and Qwen2 inference
  across CPU, NVIDIA, and CoreX backends.
- **JVM performance & observability** — in-HotSpot runtime telemetry, Arm PMU event
  collection, and reliable performance-analysis workflows for future tuning systems.
- **Agentic developer tools** — repository-aware CI generation and evidence-backed deep
  research over large code and documentation trees.

## Selected projects

| Project | What it does | Stack |
| --- | --- | --- |
| [RepoFlow](https://github.com/xiaoba17/repoflow) | Detects a repository's language, framework, package manager, and commands, then generates a conservative GitHub Actions workflow. Supports Node.js, Python, and Go projects. | TypeScript, Node.js, GitHub Actions |
| [Ancoder Deep Research](https://github.com/AncoderAI/Ancoder_DeepResearch_CLI) | Searches code repositories and document trees using dynamic skill generation, multi-round cross-validation, and a test-driven optimization loop. | TypeScript, Node.js, agentic workflows |
| [Auto Trader Demo](https://github.com/xiaoba17/auto_trader_demo) | A research-oriented A-share backtesting toolkit with market constraints, risk controls, parameter search, walk-forward validation, and live screening. | Python, BaoStock, quantitative research |
| [LLAISYS](https://github.com/xiaoba17/llaisys) | Builds an educational AI runtime from tensors and CPU operators through Qwen2 inference, with NVIDIA and CoreX backends. | C++, Python, CUDA/CoreX, XMake |
| [JVM Runtime Telemetry](https://gitcode.com/openeuler/bishengjdk-17) | An in-HotSpot observability foundation for JVM tuning: periodic snapshots, Unified Logging, Linux `perf_event_open`, and Arm PMU event-group rotation. | HotSpot, C++, Linux perf, Arm PMU |

## Recent systems work

- **[vLLM](https://github.com/xiaoba17/vllm)** — fixed DFlash draft KV-cache group
  annotations and improved executor shutdown behavior during collective RPC.
- **[InfiniLM](https://github.com/xiaoba17/InfiniLM)** — implemented priority-aware
  request scheduling for the inference engine.
- **[BiSheng JDK 17](https://gitcode.com/openeuler/bishengjdk-17)** — built a runtime
  telemetry framework inside HotSpot, covering provider lifecycle, periodic snapshots,
  Unified Logging, Linux `perf_event_open`, optional Arm-native PMU counters, and rotating
  pipeline/cache event groups to reduce multiplexing. Validated with jtreg and long-running
  workloads on Linux AArch64, providing reliable input for future dynamic tuning.
- **[LLAISYS](https://github.com/xiaoba17/llaisys)** — implemented tensor operations,
  CPU operators, Qwen2 inference, and NVIDIA/CoreX runtime backends.

## Toolbox

`C++` · `Python` · `TypeScript` · `Rust` · `Java` · `CUDA` · `Linux` · `GitHub Actions`

I enjoy working close to the boundary between models and machines: turning scheduling,
memory, kernels, and observability into systems that are easier to understand and operate.

---

Explore my repositories below, or start with **[RepoFlow](https://github.com/xiaoba17/repoflow)**
for a compact example of how I approach developer experience and reliable automation.
