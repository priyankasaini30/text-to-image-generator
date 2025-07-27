# 🖼️ Text-to-Image Generator using Stable Diffusion

This is a web-based app that turns your **text prompts into AI-generated images** using the powerful `runwayml/stable-diffusion-v1-5` model from Hugging Face. Built using 🤗 Diffusers, PyTorch, and Gradio.

---

## 🚀 Features

- 🧠 Based on Stable Diffusion v1.5
- 🔧 Adjustable **Guidance Scale** and optional **Random Seed**
- 🎨 Interactive **Gradio Web UI**
- 💡 Auto-detects GPU if available
- 🔐 Keeps your Hugging Face token private using `getpass`


## ⚙️ How to Use

### 📍 On Google Colab

1. Click the badge below to open the notebook in Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/text-to-image-generator/blob/main/text_to_image.ipynb)

2. Make sure to:
   - Go to `Runtime > Change runtime type` and set **GPU**
   - Run all cells in order

3. When prompted, **enter your Hugging Face access token** safely.

> If you don't have a token, create one [here](https://huggingface.co/settings/tokens) with **Read** access.

---

## 🖥️ Libraries Used

- `diffusers`
- `transformers`
- `accelerate`
- `safetensors`
- `torch`
- `gradio`
- `PIL`

Install dependencies in Colab:

```bash
!pip install diffusers transformers accelerate safetensors gradio --quiet
