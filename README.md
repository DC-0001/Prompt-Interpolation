# 🌀 Prompt Interpolation using Stable Diffusion & LLaMA

This project is a generative AI tool that visualizes **smooth transitions between two text prompts** (e.g., `"cat"` → `"dog"`) using **Stable Diffusion**. It creates a morphing animation by interpolating between latent representations of both prompts and generates a **GIF** to illustrate the transformation.

<br/>

## ✨ Features

- 🔁 Generates smooth visual interpolations between two prompts.
- 🎨 Uses Stable Diffusion v1.5 for high-quality image synthesis.
- ⚙️ Optimized GIF creation via frame-count and latency trade-offs.
- 🧠 Integrates LLaMA for richer embeddings.
- 🌐 Built-in Gradio UI for interactive use.
  
<br/>

## 🚀 Demo

Launch locally:

```bash
git clone https://github.com/DC-0001/Prompt-Interpolation.git
cd Prompt-Interpolation
pip install -r requirements.txt
jupyter notebook             # or `jupyter lab`
# open main.ipynb and run all cells
