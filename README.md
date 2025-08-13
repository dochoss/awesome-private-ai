# Awesome Private AI 

> Curated list of tools, frameworks, and resources for running, building, and deploying AI **privately** — on-prem, air-gapped, or self-hosted.

Private AI enables you to keep your data, models, and infrastructure **under your control**, avoiding unnecessary exposure to third parties. This list covers inference runtimes, model management, privacy tools, and more.

## **Contents**

- [Awesome Private AI](#awesome-private-ai)
  - [**Contents**](#contents)
  - [Inference Runtimes \& Backends](#inference-runtimes--backends)
  - [Model Management \& Serving](#model-management--serving)
  - [Fine-Tuning \& Adapters](#fine-tuning--adapters)
  - [Vector Databases \& Embeddings](#vector-databases--embeddings)
  - [Agents \& Orchestration](#agents--orchestration)
  - [VS Code Plugins \& Extensions](#vs-code-plugins--extensions)
  - [Privacy, Security \& Governance](#privacy-security--governance)
  - [Models for Private Deployment](#models-for-private-deployment)
  - [UI \& Interaction Layers](#ui--interaction-layers)
  - [Datasets \& Data Prep](#datasets--data-prep)
  - [Learning Resources \& Research](#learning-resources--research)
  - [AI Routers \& API Aggregators](#ai-routers--api-aggregators)
  - [Contributing](#contributing)
  - [License](#license)







## Inference Runtimes & Backends
> Engines and frameworks to run LLMs, vision, and multimodal models locally.

- [vLLM](https://github.com/vllm-project/vllm) - High-throughput, low-latency inference engine for LLMs.
- [mlx-lm](https://github.com/ml-explore/mlx-lm) - Fast, Apple Silicon-optimized LLM inference engine for running models locally and privately.
- [Jan](https://jan.ai/) - Privacy-first, offline AI assistant and LLM runtime for local, secure inference.
- [LM Studio](https://lmstudio.ai/) - Cross-platform desktop app for running local LLMs with an easy-to-use interface.
- [LLM-D](https://llm-d.ai/) - Privacy-first, distributed LLM inference engine for scalable, local deployments.
- [Ollama](https://ollama.com) - Local LLM runner with model packaging.
- [llama.cpp](https://github.com/ggerganov/llama.cpp) - Portable, CPU/GPU-friendly LLaMA inference.
- [text-generation-inference](https://github.com/huggingface/text-generation-inference) - Optimized serving stack from Hugging Face.
- [GPT4All](https://gpt4all.io) - Local desktop model runner.




## Model Management & Serving
> Tools for hosting, scaling, and versioning AI models privately.

- [Ray Serve](https://docs.ray.io/en/latest/serve/index.html) - Scalable Python model serving.
- [Seldon Core](https://github.com/SeldonIO/seldon-core) - Kubernetes-native model deployment.
- [KServe](https://kserve.github.io/website/) - Serverless model inference on Kubernetes.
- [BentoML](https://www.bentoml.com/) - Model packaging & serving framework.
- [vLLM Production Stack](https://github.com/vllm-project/production-stack) - End-to-end stack for deploying vLLM in production, including orchestration, monitoring, autoscaling, and best practices for private LLM serving.
- [OME (Open Model Engine)](https://docs.sglang.ai/ome/) - Unified, open-source engine for serving, managing, and scaling LLMs and multimodal models privately. Supports sglang, vLLM, and more.



## Fine-Tuning & Adapters
> Private workflows for adapting models to your needs.

- [LoRA](https://arxiv.org/abs/2106.09685) - Low-rank adaptation technique.
- [PEFT](https://github.com/huggingface/peft) - Parameter-efficient fine-tuning.
- [QLoRA](https://arxiv.org/abs/2305.14314) - Memory-efficient LoRA on quantized models.



## Vector Databases & Embeddings
> Private semantic search & retrieval-augmented generation.

- [Milvus](https://milvus.io) - Scalable vector database.
- [Weaviate](https://weaviate.io) - Open-source semantic search engine.
- [Chroma](https://www.trychroma.com/) - Local-first vector database.
- [FAISS](https://github.com/facebookresearch/faiss) - Facebook AI Similarity Search.










## Agents & Orchestration
> Frameworks for chaining private AI tools & agents.

- [LangChain](https://www.langchain.com/) - Agent and LLM orchestration framework.
- [Haystack](https://haystack.deepset.ai) - End-to-end RAG pipelines.
- [Flowise](https://github.com/FlowiseAI/Flowise) - No-code LangChain UI.
- [LlamaIndex](https://www.llamaindex.ai) - Data framework for LLM apps.
- [Trae Agent](https://github.com/bytedance/trae-agent) - Privacy-friendly agent framework for orchestrating LLMs and tools, designed for secure, local, and scalable AI workflows.
- [Qwen-Agent](https://github.com/QwenLM/Qwen-Agent) - Open-source, privacy-friendly agent framework for orchestrating LLMs and tools, designed for secure, local, and scalable AI workflows.
- [Crush](https://github.com/charmbracelet/crush) - Privacy-first, open-source agentic coding and automation platform for local AI workflows.
- [OpenCode AI](https://opencode.ai/) - Open-source agentic coding platform for private, local, and secure AI-powered development workflows. 

## VS Code Plugins & Extensions
> Privacy-first, open-source agentic coding plugins and extensions for VS Code and other editors.


- [Roo Code](https://github.com/RooCodeInc/Roo-Code) - Privacy-first, open-source agentic coding platform for secure, local AI development (VS Code extension).
- [cline](https://github.com/cline/cline) - Privacy-first, open-source agentic coding platform for local AI workflows and automation (VS Code extension).




## Privacy, Security & Governance
> Keep AI deployments secure and compliant.

- [BlindAI](https://github.com/mithril-security/blindai) - Confidential AI inference using TEEs.
- [OpenFL](https://github.com/IntelLabs/openfl) - Federated learning framework.
- [Flower](https://flower.dev) - Federated learning at scale.
- [Concrete](https://github.com/zama-ai/concrete) - Fully homomorphic encryption for AI.




## Models for Private Deployment
> Open-weight models and model libraries you can self-host.

- [LLaMA](https://ai.meta.com/llama/) - Meta’s open-weight language models.
- [Mistral](https://docs.mistral.ai/#free-models) - Open source models by Mistral AI.
- [Phi](https://github.com/microsoft/PhiCookBook/blob/main/md/01.Introduction/01/01.PhiFamily.md) - Small, high-quality models from Microsoft.
- [Mixtral](https://mistral.ai/news/mixtral-of-experts/) - Mixture-of-experts model.
- [Falcon](https://falconllm.tii.ae) - Open-source model from TII.
- [MLX Community](https://huggingface.co/mlx-community) - Community-driven Hugging Face page for open MLX models, optimized for Apple Silicon and private deployment.


## UI & Interaction Layers
> Self-hosted chat & AI frontends.

- [Chatbot UI](https://github.com/mckaywrigley/chatbot-ui) - Open-source ChatGPT clone.
- [LibreChat](https://github.com/danny-avila/LibreChat) - Enhanced web UI for LLMs.
- [AnythingLLM](https://anythingllm.com/) - Full-stack private LLM workspace.



## Datasets & Data Prep
> Create and manage private training corpora.

- [OpenWebText](https://skylion007.github.io/OpenWebTextCorpus/) - Open dataset similar to GPT training data.
- [RedPajama](https://www.together.xyz/blog/redpajama) - Open LLM training dataset.
- [Datamixers](https://github.com/datamixers) - Privacy-focused data preprocessing tools.


## Learning Resources & Research
> Guides, papers, and tutorials on private AI.

#TODO 

## AI Routers & API Aggregators
> Centralized routers and proxy layers for aggregating, governing, and securing your private AI stack. These tools simplify connections to multiple model servers, optimize LLM routing, and provide observability, security, and compliance.

- [Nexus](https://github.com/grafbase/nexus) - Open-source AI router to aggregate Model Context Protocol (MCP) servers, intelligently route requests to the best LLMs, and provide security, governance, observability, and simplified architecture for private AI deployments. [Blog](https://nexusrouter.com/blog/introducing-nexus-the-open-source-ai-router)


## Contributing

Contributions welcome! Provide a pull request. You can suggest a new software or section. 


## License

This list is under the CC BY-SA 4.0. Terms of the license are summarized [here](https://creativecommons.org/licenses/by-sa/4.0/).