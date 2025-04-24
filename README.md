# 🎨 Image Colorization with GAN 

This project implements a **Generative Adversarial Network (GAN)** for automatic image colorization. The model takes grayscale images as input and generates a colorized versions using a U-Net-based generator trained on a wide range of natural images.

## 🚀 Demo

You can try the model live using the interactive interface below:

➡️ **[Launch on Hugging Face Spaces](https://huggingface.co/spaces/maripau22/coloring)**  


## 🧠 About the Model

This project uses a pre-trained GAN model optimized to work with the full RGB color spectrum. The model architecture is based on a U-Net generator trained to map luminance (grayscale) input images to colored outputs.

### Features:
- Converts any uploaded image to grayscale, then colorizes it.
- Two model options:
  - **All Colors Model** (`unet_generator.pt`): Produces detailed, full-color results.
  - **20 Colors Model** (`20color_generator.pt`): A reduced-color version for comparison or performance-limited environments.
- Easy-to-use web interface built with Gradio.

## 📓 Notebooks

This repository includes two notebooks that explain and demonstrate the use of the models:

- `coloring_entregable.ipynb`: Notebook for the **All Colors Model**.
- `20colors_version.ipynb`: Notebook for the **20 Colors Model**.

These notebooks walk through the loading of the model, preprocessing steps, inference, and visualization.


## Weight & Biases

You can see more specifications about this model in the following report:

➡️ **[Weight and Biases Report ](https://api.wandb.ai/links/perezromomariapaula-iteso/ptlt6ih8 )**  

Made with ❤️ by Maria Paula
