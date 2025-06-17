# 🚗 LANE DETECTION using Hugging Face Transformers

This project performs **lane detection** on road images and videos using a pretrained model [`bricklerex/lane-detect-jds`](https://huggingface.co/bricklerex/lane-detect-jds) from Hugging Face. It uses `transformers`, `PyTorch`, and either `Gradio` (for UI testing) or `MoviePy` (for video processing).

> 🔗 Hosted on GitHub: [github.com/vichruth/LANE-DETECTION](https://github.com/vichruth/LANE-DETECTION)

---

## 🔥 Features

- ✅ Pretrained lane segmentation model from Hugging Face
- 🎞️ Full video inference with frame-by-frame overlay
- 🖼️ Gradio-based UI for testing on custom images
- 🔧 Pure Python — no need for OpenCV (unless preferred)
- 🧠 Clean and lightweight implementation

---

## 📦 Installation

Install the required packages:

```bash
pip install transformers torch moviepy gradio pillow
