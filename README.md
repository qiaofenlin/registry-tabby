# 🧑‍🔬 Tabby Registry

## Completion models (`--model`)

We recommend using

* For **1B to 3B models**, it's advisable to have at least **NVIDIA T4, 10 Series, or 20 Series GPUs**, or **Apple Silicon** like the M1.
* For **7B to 13B models**, we recommend using **NVIDIA V100, A100, 30 Series, or 40 Series GPUs**.

We have published benchmarks for these models on https://leaderboard.tabbyml.com for Tabby's users to consider when making trade-offs between quality, licensing, and model size.

| Model ID | License |
| -------- | ------- |
| [StarCoder-1B](https://huggingface.co/bigcode/starcoderbase-1b) | [BigCode-OpenRAIL-M](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement) |
| [StarCoder-3B](https://huggingface.co/bigcode/starcoderbase-3b) | [BigCode-OpenRAIL-M](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement) |
| [StarCoder-7B](https://huggingface.co/bigcode/starcoderbase-7b) | [BigCode-OpenRAIL-M](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement) |
| [StarCoder2-3B](https://huggingface.co/bigcode/starcoder2-3b) | [BigCode-OpenRAIL-M](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement) |
| [StarCoder2-7B](https://huggingface.co/bigcode/starcoder2-7b) | [BigCode-OpenRAIL-M](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement) |
| [CodeLlama-7B](https://huggingface.co/codellama/CodeLlama-7b-hf) | [Llama 2](https://github.com/facebookresearch/llama/blob/main/LICENSE) |
| [CodeLlama-13B](https://huggingface.co/codellama/CodeLlama-13b-hf) | [Llama 2](https://github.com/facebookresearch/llama/blob/main/LICENSE) |
| [DeepSeekCoder-1.3B](https://huggingface.co/deepseek-ai/deepseek-coder-1.3b-base) | [Deepseek License](https://github.com/deepseek-ai/deepseek-coder/blob/main/LICENSE-MODEL) |
| [DeepSeekCoder-6.7B](https://huggingface.co/deepseek-ai/deepseek-coder-6.7b-base) | [Deepseek License](https://github.com/deepseek-ai/deepseek-coder/blob/main/LICENSE-MODEL) |
| [CodeGemma-2B](https://huggingface.co/google/codegemma-2b) | [Gemma License](https://ai.google.dev/gemma/terms) |
| [CodeGemma-7B](https://huggingface.co/google/codegemma-7b) | [Gemma License](https://ai.google.dev/gemma/terms) |
| [CodeQwen-7B](https://huggingface.co/Qwen/CodeQwen1.5-7B-Chat) | [Tongyi Qianwen License](https://github.com/QwenLM/Qwen/blob/main/Tongyi%20Qianwen%20LICENSE%20AGREEMENT) |
| [Qwen2.5-Coder-0.5B](https://huggingface.co/Qwen/Qwen2.5-Coder-0.5B) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Qwen2.5-Coder-1.5B](https://huggingface.co/Qwen/Qwen2.5-Coder-1.5B) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Qwen2.5-Coder-3B](https://huggingface.co/Qwen/Qwen2.5-Coder-3B) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Qwen2.5-Coder-7B](https://huggingface.co/Qwen/Qwen2.5-Coder-7B) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Qwen2.5-Coder-14B](https://huggingface.co/Qwen/Qwen2.5-Coder-14B) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Codestral-22B](https://huggingface.co/mistralai/Codestral-22B-v0.1) | [Mistral AI Non-Production License](https://mistral.ai/licenses/MNPL-0.1.md) |
| [DeepSeek-Coder-V2-Lite](https://huggingface.co/deepseek-ai/DeepSeek-Coder-V2-Lite-Base) | [Deepseek License](https://github.com/deepseek-ai/deepseek-coder/blob/main/LICENSE-MODEL) |


## Chat models (`--chat-model`)

To ensure optimal response quality, and given that latency requirements are not stringent in this scenario, we recommend using a model with at least 1B parameters.

| Model ID | License |
| -------- | ------- |
| [Mistral-7B](https://huggingface.co/mistralai/Mistral-7B-v0.1) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [CodeGemma-7B-Instruct](https://huggingface.co/google/codegemma-7b-it) | [Gemma License](https://ai.google.dev/gemma/terms) |
| [CodeQwen-7B-Chat](https://huggingface.co/Qwen/CodeQwen1.5-7B-Chat) | [Tongyi Qianwen License](https://github.com/QwenLM/Qwen/blob/main/Tongyi%20Qianwen%20LICENSE%20AGREEMENT) |
| [Qwen2.5-Coder-0.5B-Instruct](https://huggingface.co/Qwen/Qwen2.5-Coder-0.5B-Instruct-GGUF) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Qwen2.5-Coder-1.5B-Instruct](https://huggingface.co/Qwen/Qwen2.5-Coder-1.5B-Instruct-GGUF) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Qwen2.5-Coder-7B-Instruct](https://huggingface.co/Qwen/Qwen2.5-Coder-7B-Instruct-GGUF) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Qwen2.5-Coder-14B-Instruct](https://huggingface.co/Qwen/Qwen2.5-Coder-14B-Instruct-GGUF) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Qwen2.5-Coder-32B-Instruct](https://huggingface.co/Qwen/Qwen2.5-Coder-32B-Instruct-GGUF) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Qwen2-1.5B-Instruct](https://huggingface.co/Qwen/Qwen2-1.5B) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Codestral-22B](https://huggingface.co/mistralai/Codestral-22B-v0.1) | [Mistral AI Non-Production License](https://mistral.ai/licenses/MNPL-0.1.md) |
| [Yi-Coder-9B-Chat](https://huggingface.co/01-ai/Yi-Coder-9B-Chat) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |


## Embedding models

| Model ID | License |
| -------- | ------- |
| [Nomic-Embed-Text](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5-GGUF) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Jina-Embeddings-V2-Code](https://huggingface.co/jinaai/jina-embeddings-v2-base-code) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
