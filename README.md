# Image Generation and Background Replacement using Stable Diffusion 3.5
This project showcases how to utilize Stable Diffusion 3.5 for image generation, background replacement, and enhancement using LoRA adapters and other techniques. The notebook demonstrates a streamlined workflow for generating AI-based images and customizing them using quantized models and auto-generated masks.
# Table of Contents
1. Overview
2. Features
3. Requirments
4. Setup Instruction
5. project structure
6. Key Code Highlights
7. Results
8. Acknowledgement

# 1. Overview
This project focuses on the following tasks:
1. Generating images from text prompts using Stable Diffusion 3.5.
2. Enhancing image generation capabilities by fusing LoRA adapters.
3. Implementing background/object replacement in images using automatically generated masks.
4. Optimizing the model for efficiency with memory management techniques.
5. The project is built using PyTorch and HuggingFace Diffusers library.

# 2. Feautures
1. Text-to-Image Generation: Generate high-quality images from textual descriptions.
2. LoRA Adapter Fusion: Enhance image generation with specific styles or fine-tuning using LoRA adapters.
3. Background Replacement: Replace the background or objects in images using auto-generated masks.
4. GPU Memory Optimization: Ensure smooth execution with CUDA configurations like attention slicing and memory fraction control.

# 3. Requirements
Ensure you have the following libraries and tools installed:

* Python >= 3.8
* PyTorch >= 2.0
* HuggingFace Diffusers
* Transformers
* CUDA (for GPU support)
* Matplotlib
* Torchvision
  
You can install all dependencies using the following command:

!. pip install torch torchvision diffusers transformers matplotlib


