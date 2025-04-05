# 🖼️ Text to Image Generation App

This is a simple Text-to-Image generation app using Hugging Face's Stable Diffusion model with a Gradio UI.

## 🚀 Features

- Generate stunning images from any text prompt.
- Uses the `stabilityai/stable-diffusion-2-1-base` model.
- Clean and interactive UI using Gradio.
- Easy setup with Hugging Face and Python packages.

---

## 📋 Step-by-Step Setup Guide

### 1️⃣ Login to Hugging Face

- Visit: [https://huggingface.co](https://huggingface.co)
- Sign in to your account or create a new one.

### 2️⃣ Create Access Token

- Go to your **Profile** → **Settings** → **Access Tokens**
- Click on **New Token**
- Give it a name (e.g., `text2image-token`)
- Set permission to `Read`
- Click **Create Token**
- Copy the generated token

### 3️⃣ Install Required Python Packages

Run the following command in your terminal:

 pip install diffusers transformers accelerate scipy safetensors

### 3️⃣ Run This Command
    !huggingface-cli login

### 3️⃣ Run pipeline Code

### Pip Install Gradio
    Run the user interface file                
