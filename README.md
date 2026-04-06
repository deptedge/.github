# deptedge

**Domain-tuned CV models and MCP tools that let AI agents understand video — offline, on cheap hardware, without the cloud.**

## What we do

We benchmark, quantize, and fine-tune computer vision models for edge deployment. Our focus: making action recognition, depth estimation, and object detection run fast on devices like Raspberry Pi 5 and Apple Silicon — then exposing them as MCP tools for AI agents.

## Repos

| Repo | Description |
|------|-------------|
| [edge-cv-benchmark](https://github.com/deptedge/edge-cv-benchmark) | Benchmark harness for 7+ CV models on M1 Max and Pi 5 — latency, RAM, FPS |

## Benchmark Results — M1 Max (MPS)

| Model | Latency | FPS | License |
|-------|---------|-----|---------|
| YOLOv10n | 14ms | 69 | AGPL-3.0 |
| DepthAnything V2 Small | 43ms | 23 | Apache 2.0 |
| VideoMAE Small | 93ms | 11 | CC-BY-NC |
| SlowFast R50 | 149ms | 7 | Apache 2.0 |

## Tech Stack

PyTorch 2.x · ONNX Runtime · Apple MPS · INT8 Quantization · MCP Protocol · HuggingFace

## Links

- [HuggingFace](https://huggingface.co/deptedge)
- [X / Twitter](https://x.com/deptedge_ai)
