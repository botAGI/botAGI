# botAGI — LLMOps / AI Platform Engineer

I build self-hosted, private LLM/RAG platforms and the tooling around them:
local inference, document ingestion, model fine-tuning, serving benchmarks,
and source-grounded agent tooling. No cloud, no vendor lock-in.

<!-- Models & Serving -->
<p align="center">
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white">
<img alt="vLLM" src="https://img.shields.io/badge/vLLM-1A1A2E?style=for-the-badge">
<img alt="llama.cpp" src="https://img.shields.io/badge/llama.cpp-000000?style=for-the-badge">
<img alt="Ollama" src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white">
<img alt="Hugging Face" src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black">
</p>
<!-- LLM Apps & Agents -->
<p align="center">
<img alt="Dify" src="https://img.shields.io/badge/Dify-1C64F2?style=for-the-badge&logo=dify&logoColor=white">
<img alt="Open WebUI" src="https://img.shields.io/badge/Open%20WebUI-1F2937?style=for-the-badge">
<img alt="RAGFlow" src="https://img.shields.io/badge/RAGFlow-FF6A00?style=for-the-badge">
<img alt="n8n" src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white">
<img alt="Pydantic" src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white">
<img alt="Phoenix" src="https://img.shields.io/badge/Phoenix-6E56CF?style=for-the-badge">
</p>
<!-- Vector & Search -->
<p align="center">
<img alt="Qdrant" src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white">
<img alt="Milvus" src="https://img.shields.io/badge/Milvus-00A1EA?style=for-the-badge&logo=milvus&logoColor=white">
<img alt="Weaviate" src="https://img.shields.io/badge/Weaviate-00B894?style=for-the-badge">
<img alt="Elasticsearch" src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white">
</p>
<!-- Backend & Storage -->
<p align="center">
<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
<img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<img alt="Redis" src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white">
<img alt="Celery" src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white">
<img alt="MinIO" src="https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white">
</p>
<!-- Platform & Ops -->
<p align="center">
<img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
<img alt="Ansible" src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white">
<img alt="Traefik" src="https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white">
<img alt="NGINX" src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white">
<img alt="Authelia" src="https://img.shields.io/badge/Authelia-113155?style=for-the-badge&logo=authelia&logoColor=white">
<img alt="Portainer" src="https://img.shields.io/badge/Portainer-13BEF9?style=for-the-badge&logo=portainer&logoColor=white">
<img alt="Prometheus" src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white">
<img alt="Grafana" src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white">
<img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
</p>
<!-- Hardware -->
<p align="center">
<img alt="NVIDIA" src="https://img.shields.io/badge/NVIDIA-76B900?style=for-the-badge&logo=nvidia&logoColor=white">
<img alt="AMD" src="https://img.shields.io/badge/AMD-ED1C24?style=for-the-badge&logo=amd&logoColor=white">
<img alt="Vulkan" src="https://img.shields.io/badge/Vulkan-A41E22?style=for-the-badge&logo=vulkan&logoColor=white">
</p>

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
- Portfolio: https://agmind.ai · https://agmind.dev
- Hugging Face: https://huggingface.co/AGmind
- Telegram: [@Agmind](https://t.me/Agmind)
