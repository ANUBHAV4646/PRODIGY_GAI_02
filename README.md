# PRODIGY_GAI_02
This repository demonstrates how to generate images from natural language prompts using Stable Diffusion, a powerful pre-trained generative AI model.

**Project Description**

Stable Diffusion is a latent text-to-image diffusion model capable of generating photorealistic images given any input text. This project allows users to experiment with the model by providing prompts and viewing or saving the generated outputs.

**Features**

-Generate high-quality images from simple or complex text prompts

-Automatically detects and utilizes GPU (CUDA) if available

-Easy-to-run in Google Colab

-Prompt-driven, customizable results

**Key Concepts**

**-Latent Diffusion:** The model operates in a lower-dimensional latent space, which speeds up generation and reduces computational costs.

**-CLIP Text Encoder:** Converts the input prompt into embeddings that guide image generation.

**-Denoising Process:** The model refines a noise image step-by-step into a meaningful visual.

**-Prompt Engineering:** The quality and specificity of your prompt directly affect the image output.


**Runtime Settings**

✅ GPU is recommended for optimal performance.

-Change Runtime in Google Colab:
-Click Runtime → Change runtime type

-Select GPU under "Hardware accelerator"

-Click Save

-The script will automatically detect the hardware:

Uses GPU (CUDA) if available

Falls back to CPU if not (slower and may crash with large models)

**📥 Input**

Users provide a natural language prompt describing the image they want to generate.

Examples:

"a robot reading a book under the stars"

"a majestic lion in watercolor style"

**🖼️ Output**

-The model returns a high-resolution image based on the text prompt.

-Images can be viewed directly or saved locally.

**Getting Started***

This project is designed to run in Google Colab for ease of setup.

-Open the Colab notebook

-Set runtime to GPU

-Run the cells step-by-step

Enter your prompt and view the result

