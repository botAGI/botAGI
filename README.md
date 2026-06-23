# botAGI — LLMOps / AI Platform Engineer

I build self-hosted, private LLM/RAG platforms and the tooling around them:
local inference, document ingestion, model fine-tuning, serving benchmarks,
and source-grounded agent tooling. No cloud, no vendor lock-in.

## Focus
- **LLM serving**: vLLM, llama.cpp, Ollama — on NVIDIA GB10 (DGX Spark) and AMD Strix Halo
- **RAG**: vector DBs (Qdrant/Weaviate/Milvus), document parsing (Docling), chunking, reranking, evaluation
- **AI platform**: Docker Compose, k3s/Ansible, monitoring (Prometheus/Grafana/Loki), security hardening, Day-2 ops
- **ML lifecycle**: distillation, PEFT/LoRA, GGUF quantization, local deployment, evaluation
- **Backend**: Python, FastAPI, PostgreSQL, Redis, Celery

## Selected projects
| Project | What it proves | Stack |
|---|---|---|
| [morpheus-ai](https://github.com/botAGI/morpheus-ai) | Source-grounded truth layer for agents: compile state, verify claims, sign receipts | Python, ed25519, MCP, FastAPI, 678 tests |
| [AGmind](https://github.com/botAGI/AGmind) | One-command private LLM/RAG platform, validated on DGX Spark GB10 | Docker Compose, vLLM, Dify, RAGFlow, monitoring |
| [AGmind-ML](https://github.com/botAGI/AGmind-ML) | Full RAG-model lifecycle: distill → LoRA → GGUF → llama.cpp | PEFT, GGUF, Vulkan, eval, Hugging Face |
| [AGmind64](https://github.com/botAGI/AGmind64) | Self-hosted LLM/RAG on AMD Strix Halo / x86_64 | llama.cpp Vulkan/ROCm, Qdrant, Dify |

<!-- M2: add local-llm-serving-bench + doc-ingestion-rag-pipeline here once they ship -->

## Writing
- Habr technical series on self-hosted LLM inference (DGX Spark / GB10): https://habr.com/ru/users/AGmind/

## How I work with AI
I use AI as a force multiplier. I own architecture, security, and deployment
decisions, and I verify everything against real hardware and real data —
including the parts AI can't reason about (driver regressions, hardware memory
behavior, network topology).

## Links
- Portfolio: https://agmind.ai · https://prem.agmind.dev
- Hugging Face: https://huggingface.co/AGmind
- Telegram: [@Agmind](https://t.me/Agmind)
