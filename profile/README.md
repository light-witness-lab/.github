 <div align="center">

# ◉ LIGHT WITNESS LAB
### 光证实验室 · Open-source Imaging & Edge Intelligence

[![Imaging](https://img.shields.io/badge/Imaging-Open%20Source-58A6FF?style=flat-square)](https://github.com/light-witness-lab/street-snap)
[![Model Solutions](https://img.shields.io/badge/Model-Engineering-8957E5?style=flat-square)](https://github.com/light-witness-lab/edge-model-solutions)
[![Edge Inference](https://img.shields.io/badge/Edge-Inference-238636?style=flat-square)](https://github.com/light-witness-lab/inference-engineering)

</div>

---

## `01` / ABOUT

Light Witness Lab is an open-source initiative exploring documentary imaging and on-device intelligence.

我们从真实的影像产品出发，探索视觉能力的构建、验证与部署：以相机承载应用，以模型方案实现能力，以推理工程释放设备性能。

## `02` / PROJECTS

### ◉ [street-snap](https://github.com/light-witness-lab/street-snap)

**途帧 · Open-source Street Camera**

A mobile street camera built around one idea: capture the moment before it passes.

- **Capture** — 28 / 35 / 50mm-equivalent perspectives, fast access to shooting controls, and streamlined capture workflows
- **Color** — Film-inspired rendering, custom 3D LUTs, and independently adjustable image profiles
- **Composition** — An optional on-device composition assistant, designed to work offline without interrupting capture

面向日常街拍与人文纪实的开源 Android 相机。以快速启动、简洁操作和可定制影调为核心，让手机摄影更接近随身相机的拍摄体验，并探索端侧视觉能力在实际拍摄流程中的应用。

[Explore Repository →](https://github.com/light-witness-lab/street-snap)

---

### ◈ [edge-model-solutions](https://github.com/light-witness-lab/edge-model-solutions)

**On-device Model Solutions · 端侧模型方案**

From model checkpoints to usable product capabilities.

- **Model composition** — Task-oriented pipelines combining specialized models, deterministic logic, and structured outputs
- **Evaluation & evidence** — Reproducible tests, explicit verification status, and documented failure cases
- **Deployment constraints** — Runtime compatibility, quantization, memory footprint, latency, and thermal behavior
- **Artifact provenance** — Pinned model revisions, checksums, adapters, and per-model license records

围绕相机与多模态产品，研究如何将模型组合为可落地的端侧能力。从输入预处理、模型决策到结果校验与界面反馈，记录完整链路、验证状态与失效边界。以可复现的测试区分模型能够运行、功能有效与产品可用，而不是以单次跑通或孤立跑分代替验证。

[Explore Repository →](https://github.com/light-witness-lab/edge-model-solutions)

---

### ⌘ [inference-engineering](https://github.com/light-witness-lab/inference-engineering)

**Edge Inference Engineering · 端侧推理工程**

Understanding inference performance from operators to the full execution pipeline.

- **Runtime & backend** — ONNX Runtime, MNN, NCNN, ExecuTorch, LiteRT, and llama.cpp
- **Model optimization** — Quantization, operator execution, memory management, and KV-cache behavior
- **Hardware acceleration** — CPU, GPU, NPU, and heterogeneous execution
- **Performance analysis** — Stage-level latency, p50/p95, memory usage, sustained thermal performance, and energy efficiency

聚焦模型在移动设备与边缘硬件上的实际执行效率。通过运行时对比、算子分析、量化与内存优化，拆解端到端推理开销，验证不同模型、执行后端与硬件组合的性能边界。

研究以可复现实验和具体设备数据为依据，区分理论分析、运行验证与真实硬件实测。

[Explore Repository →](https://github.com/light-witness-lab/inference-engineering)

## `03` / ENGINEERING PRINCIPLES

- **Product-driven** — Start with real use cases, not model capabilities in isolation.
- **Evidence-based** — Make measurements, limitations, and failures explicit.
- **Hardware-aware** — Optimize for the device, not just the benchmark.
- **Reproducible** — Pin artifacts, document configurations, and preserve test conditions.

---

<div align="center">

**CAPTURE THE WORLD. BUILD THE CAPABILITY. ENGINEER THE EXECUTION.**

记录真实 · 构建能力 · 优化执行

<sub>LIGHT WITNESS LAB · BUILT IN THE OPEN</sub>

</div>
