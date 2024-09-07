# Stable Diffusion From Scratch

## Introduction
This repository provides a step-by-step guide on how to build a Stable Diffusion model from scratch using PyTorch. Stable Diffusion is a powerful text-to-image generation model that can create realistic images based on textual descriptions. By building the model from scratch, it allows for a deeper understanding of the underlying architecture and training process.

## Prerequisites
- Python 3.7 or higher
- PyTorch 1.10.0 or higher
- NumPy
- Pillow
- tqdm

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/sidd2305/Stable_Diffusion-From-Scratch.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Stable_Diffusion-From-Scratch
   ```


## Usage
Make sure you modify the correct weight paths and output image paths in demo.py and type in the prompt you require(for image generation).Download pretrained stable diffusion weights and place them in the "Data folder".Link to pre trained stable diffusion weights-https://huggingface.co/Envvi/Inkpunk-Diffusion/blob/main/inkpunk-diffusion-v1.ckpt.
Once this is completed,you can run demo.py for image generation.


The Stable Diffusion model was originally developed by Stability AI and Anthropic.  
This implementation uses the PyTorch library for deep learning.

It was developed with code from the [YouTube tutorial](https://www.youtube.com/watch?v=ZBKpAp_6TGI).

## License
This project is licensed under the MIT License.
