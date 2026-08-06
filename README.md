<p align="center"><img src=".github/hero.svg" alt="Hanzo-MLX" width="880"></p>

# Hanzo-MLX

**Apple Silicon acceleration for the Hanzo ecosystem**

Part of [Hanzo Painter](https://github.com/hanzoai/painter) - AI-powered watermark removal and video inpainting platform.

[![Upstream](https://img.shields.io/badge/upstream-thoddnn%2FComfyUI--MLX-blue)](https://github.com/thoddnn/ComfyUI-MLX)
[![Hanzo AI](https://img.shields.io/badge/Hanzo-AI-orange)](https://hanzo.ai)

## About

Hanzo-MLX is a Hanzo-maintained fork of ComfyUI-MLX, providing native Apple Silicon (M1/M2/M3/M4) acceleration using Apple's MLX framework.

### Performance Benefits

- 🚀 **70% faster model loading**
- ⚡ **35% faster inference**
- 💾 **30% lower memory usage**

## Installation

### As Part of Hanzo Painter (Recommended)

```bash
git clone git@github.com:hanzoai/painter.git
cd painter
make install-mlx  # Installs Hanzo-MLX with dependencies
```

### Standalone Installation

```bash
cd ComfyUI/custom_nodes
git clone git@github.com:hanzoai/Hanzo-MLX.git
cd Hanzo-MLX
pip install -r requirements.txt
```

## Hanzo ComfyUI Ecosystem

Part of the curated Hanzo ComfyUI stack. See all nodes at [github.com/hanzoai](https://github.com/hanzoai).

## Upstream


**Note**: Currently optimized for Flux models. SD 1.5 support coming soon.

---

Made with ❤️ by [Hanzo AI](https://hanzo.ai)
