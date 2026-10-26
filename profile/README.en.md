 <div align="center">

<sub>[简体中文](README.md)</sub>

# ◉ LIGHT WITNESS LAB
### Open-source Imaging & Edge Intelligence

We start from real imaging products and explore how visual capabilities are built, verified, and deployed:<br>
cameras carry the application, model solutions deliver the capability, and inference engineering unlocks device performance.

[![Imaging](https://img.shields.io/badge/Imaging-Open%20Source-58A6FF?style=flat-square)](https://github.com/light-witness-lab/street-snap)
[![Model Solutions](https://img.shields.io/badge/Model-Engineering-8957E5?style=flat-square)](https://github.com/light-witness-lab/edge-model-solutions)
[![Edge Inference](https://img.shields.io/badge/Edge-Inference-238636?style=flat-square)](https://github.com/light-witness-lab/inference-engineering)

</div>

---

## `01` / ABOUT

Three directions, each in its own public repository:

- **Imaging** — [street-snap](https://github.com/light-witness-lab/street-snap): a mobile street camera that puts vision to work inside the real viewfinder–capture–output loop — composition advice, pose guidance, and on-device color rendering.
- **Model solutions** — [edge-model-solutions](https://github.com/light-witness-lab/edge-model-solutions): composing model checkpoints into verifiable product capabilities, keeping evaluation evidence, failure boundaries, and deployment constraints on record.
- **Inference engineering** — [inference-engineering](https://github.com/light-witness-lab/inference-engineering): breaking down inference cost from individual operators to the end-to-end pipeline, mapping device performance limits with reproducible measurements.

## `02` / PROJECTS

### ◉ [street-snap](https://github.com/light-witness-lab/street-snap)

**途帧 · Open-source Street Camera**

A mobile street camera built around one idea: capture the moment before it passes.

- **Capture** — 28 / 35 / 50mm-equivalent perspectives, fast access to shooting controls, and streamlined capture workflows
- **Color** — Film-inspired rendering, custom 3D LUTs, and independently adjustable image profiles
- **Composition** — An optional on-device composition assistant, designed to work offline without interrupting capture

An open-source Android camera for everyday street and documentary photography. Fast launch, streamlined controls, and customizable film-inspired rendering bring phone photography closer to the feel of a pocket camera — and put on-device vision to work inside the actual shooting flow.

[Explore Repository →](https://github.com/light-witness-lab/street-snap)

---

### ◈ [edge-model-solutions](https://github.com/light-witness-lab/edge-model-solutions)

**On-device Model Solutions**

From model checkpoints to usable product capabilities.

- **Model composition** — Task-oriented pipelines combining specialized models, deterministic logic, and structured outputs
- **Evaluation & evidence** — Reproducible tests, explicit verification status, and documented failure cases
- **Deployment constraints** — Runtime compatibility, quantization, memory footprint, latency, and thermal behavior
- **Artifact provenance** — Pinned model revisions, checksums, adapters, and per-model license records

For camera and multimodal products, we study how models compose into deployable on-device capabilities. From input preprocessing and model decisions to result validation and UI feedback, the whole chain is documented — including verification status and failure boundaries. Reproducible tests separate *runs*, *works*, and *product-ready*; a single successful run or an isolated benchmark score never counts as verification.

[Explore Repository →](https://github.com/light-witness-lab/edge-model-solutions)

---

### ⌘ [inference-engineering](https://github.com/light-witness-lab/inference-engineering)

**Edge Inference Engineering**

Understanding inference performance from operators to the full execution pipeline.

- **Runtime & backend** — ONNX Runtime, MNN, NCNN, ExecuTorch, LiteRT, and llama.cpp
- **Model optimization** — Quantization, operator execution, memory management, and KV-cache behavior
- **Hardware acceleration** — CPU, GPU, NPU, and heterogeneous execution
- **Performance analysis** — Stage-level latency, p50/p95, memory usage, sustained thermal performance, and energy efficiency

We focus on the real execution efficiency of models on mobile and edge hardware. Runtime comparisons, operator analysis, quantization, and memory optimization break down end-to-end inference cost and map the performance limits of model × execution backend × hardware combinations.

Every claim rests on reproducible experiments and concrete device data, with theoretical analysis, runtime verification, and real-hardware measurements kept clearly apart.

[Explore Repository →](https://github.com/light-witness-lab/inference-engineering)

## `03` / ENGINEERING PRINCIPLES

- **Product-driven** — Start with real use cases, not model capabilities in isolation.
- **Evidence-based** — Make measurements, limitations, and failures explicit.
- **Hardware-aware** — Optimize for the device, not just the benchmark.
- **Reproducible** — Pin artifacts, document configurations, and preserve test conditions.

---

<div align="center">

**CAPTURE THE WORLD. BUILD THE CAPABILITY. ENGINEER THE EXECUTION.**

<sub>LIGHT WITNESS LAB · BUILT IN THE OPEN</sub>

</div>
