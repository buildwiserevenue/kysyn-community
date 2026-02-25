# ⚖️ Open Source Attributions & Neural Engines

KYSYN is built upon the "Neural Backbone" of high-performance open-source models and libraries. We believe in the power of local-first AI and transparency.

### 🧠 Neural Engines (ONNX Optimized)
The following assets power the HyDE generation, hybrid embedding, and cross-encoder reranking within the KYSYN Pipeline.

* **HyDE Engine: Qwen2.5-Coder-1.5B (ONNX)**
    * *Optimization:* [onnx-community](https://huggingface.co/onnx-community)
    * *Base Model:* [Alibaba Qwen2.5-Coder-1.5B-Instruct](https://huggingface.co/Qwen/Qwen2.5-Coder-1.5B-Instruct)
    * *License:* **Apache 2.0**
* **Embedding Engine: BGE-M3 (Xenova)**
    * *Optimization:* [Xenova (Transformers.js)](https://huggingface.co/Xenova/bge-m3)
    * *Base Model:* [BAAI/bge-m3](https://huggingface.co/BAAI/bge-m3)
    * *License:* **MIT**
* **Reranker Engine: BGE-Reranker-v2-m3 (ONNX)**
    * *Optimization:* [onnx-community](https://huggingface.co/onnx-community)
    * *Base Model:* [BAAI/bge-reranker-v2-m3](https://huggingface.co/BAAI/bge-reranker-v2-m3)
    * *License:* **MIT**

### 🛠️ Core Libraries & Frameworks
* **Tree-sitter:** High-performance incremental parsing system for code intelligence. [MIT]
* **Onnxruntime-go:** Microsoft’s cross-platform inference engine for local execution. [MIT]
* **Optimum (Hugging Face):** Used for INT8 quantization and ONNX conversion. [Apache 2.0]

---
*Special thanks to the **Xenova** team and the **onnx-community** for their invaluable contribution to the local AI ecosystem.*
