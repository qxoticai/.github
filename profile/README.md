<div align="center">

# Quixotic AI

**AI sovereignty for the world's most trusted runtime.**

</div>

The JVM runs global finance, telecommunications, and critical infrastructure. It deserves an AI stack built to the same standard. We're building **Jota**, the tensor engine that brings native-speed inference to Java without sacrificing the portability and reliability the platform is famous for.

---

### 🧬 Jota Tensor Engine

At the heart of Quixotic is **Jota** (JVM Open Tensor Accelerator), a multi-backend tensor engine designed from first principles for the JVM.

---

### 🏗️ The Stack

**qxotic** is a modular AI stack, it provides the following standalone components:

| Module | Purpose |
|--------|---------|
| [**jota**](https://github.com/qxoticai/qxotic/tree/main/jota) | Multi-backend tensor engine (Panama, C, CUDA, HIP, Metal, OpenCL, Mojo) |
| [**gguf**](https://github.com/qxoticai/qxotic/tree/main/gguf) | Native read/write for llama.cpp's GGUF model format |
| [**safetensors**](https://github.com/qxoticai/qxotic/tree/main/safetensors) | Native read/write for HuggingFace's Safetensors format |
| [**tokenizers**](https://github.com/qxoticai/qxotic/tree/main/tokenizers) | TikToken, BPE, and common tokenization algorithms |

**Jota** provides the computational foundation, abstracts hardware complexity behind a unified Tensor API. Write once, accelerate everywhere, from embedded devices to data center GPUs, without leaving the safety of the JVM.

First-class support for **GraalVM's Native Image**. On JVM, Jota's host backend defaults to Panama,
on Native Image it uses the C backend instead. Except for Panama, all backends are supported
out-of-the-box on Native Image with minimal footprint overhead e.g. a simple Mandelbrot demo with ALL backends
included is just ~22MB. 

---

Quixotic AI is the evolution/realization of **[llama4j](https://llama4j.com)** a complete set of standalone JVM components for AI.

---

### ⚡ Current Status

**Experimental. Evolving. Under heavy development.**

---

### 🌍 Connect

- 🌐 [qxotic.ai](https://qxotic.ai)
- 🐦 [@qxoticai](https://x.com/qxoticai)
- 🦋 [@qxotic.ai](https://bsky.app/profile/qxotic.ai)

---

*Built in Switzerland. Accele
rating (on) the JVM.*
