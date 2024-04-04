# awesome-customized-generative-AI
Papers and codes collection for customize, personalized and editable generative models in 2D and 3D domains.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Introduction
Artificial Intelligence Generated Content (AIGC) has become ubiquitous, demonstrating the power of generating mesmerizing results of random portraits. However, users generally show greater interest in personalized information (for example, faces from familiar people or celebrities) in these generated results than in generic faces. This tendency toward customization in AIGC arouses attention to customized, personalized, and editable generative AI. 

This repo mainly focuses on visual generative models (leaving out LLMs), including 2D image-to-image, 2D text-to-image, and text-guided 3D generation/manipulation, collecting customized, personalized, and editable works in these specific domains. For any addition about other 2D/3D AIGC domains or bugs report, please open an issue, pull requests, or e-mail me at `normanzheng6606@gmail.com` for better communication.


## Table of Contents
- [Customized 2D Image-to-Image](#customized-2d-image-to-image)
  - [Image-prompted Generation](#image-prompted-generation)
  - [Portrait Style Transfer](#portrait-style-transfer)
  - [Interactive Image Editing](#interactive-image-editing)

- [Customized 2D Text-to-Image](#customized-2d-text-to-image)
  - [Text-guided Portrait Generation](#text-guided-portrait-generation)
  - [Text-guided Image Editing](#text-guided-image-editing)

- [Customized 3D Generation/Manipulation](#customized-3d-generationmanipulation)
  - [Image-prompted 3D Generation](#image-prompted-3d-generation)
  - [Text-prompted 3D Manipulation](#text-prompted-3d-manipulation)
  - [Editable-3D](#editable-3d)
- [Other Resources](#other-resources)
  - [Generic Datasets](#generic-datasets)
  - [Generic Pre-trained Models](#generic-pre-trained-models)



## Personalized 2D Image-to-Image

### Image-prompted Generation   

#### 2024

- InstantID: Zero-shot Identity-Preserving Generation in Seconds [{Paper}](https://arxiv.org/abs/2401.07519) [{Code}](https://github.com/InstantID/InstantID.git) [{Webpage}](https://instantid.github.io/)<details><summary>Details</summary></summary><p align="center">
  <img width="100%" src="figures/Customized-2D-Image-to-Image/image-prompted-generation/InstantID/main-figure.png"/>
</p></details>

### Portrait Style Transfer

#### 2024

- InstantStyle: Free Lunch towards Style-Preserving in Text-to-Image Generation [{Paper}](https://arxiv.org/abs/2404.02733) [{Code}](https://github.com/InstantStyle/InstantStyle.git)<details><summary>Details</summary></summary><p align="center">
  <img width="100%" src="figures/Customized-2D-Image-to-Image/portrait-style-transfer/InstantStyle/image-based-style-transfer.png"/>
</p></details>




### Interactive Image Editing

#### 2024



#### 2023

- Drag Your GAN: Interactive Point-based Manipulation on the Generative Image Manifold `SIGGRAPH 2023` [{Paper}](https://arxiv.org/abs/2305.10973) [{Code}](https://github.com/XingangPan/DragGAN.git) [{Webpage}](https://vcai.mpi-inf.mpg.de/projects/DragGAN/)

- DragDiffusion: Harnessing Diffusion Models for Interactive Point-based Image Editing `CVPR2024` [{Paper}](https://arxiv.org/abs/2306.14435) [{Code}](https://github.com/Yujun-Shi/DragDiffusion.git) [{Webpage}](https://yujun-shi.github.io/projects/dragdiffusion.html)

## Customized 2D Text-to-Image


### Text-guided Portrait Generation

#### 2024

- [CLIP-Guided Image Synthesis](https://arxiv.org/abs/2103.00020)
  - **Description:** CLIP-Guided Image Synthesis is a text-to-image generation model that can generate images from text descriptions using a pre-trained CLIP model. The model can produce images with complex shapes, textures, and colors, and can be fine-tuned to generate images with specific styles and attributes.
  - **Code:** https://github.com/orpatashnik/CLIP-Guided-Image-Synthesis


### Text-guided Image Editing

#### 2024

- [CLIP-Guided Image Editing](https://arxiv.org/abs/2103.00020)
  - **Description:** CLIP-Guided Image Editing is a text-to-image generation model that can generate images from text descriptions using a pre-trained CLIP model. The model can produce images with complex shapes, textures, and colors, and can be fine-tuned to generate images with specific styles and attributes.
  - **Code:** https://github.com/orpatashnik/CLIP-Guided-Image-Synthesis


## Customized 3D Generation/Manipulation

### Image-prompted 3D Generation


#### 2024

- [CLIP-Guided 3D Shape Synthesis](https://arxiv.org/abs/2103.00020)
  - **Description:** CLIP-Guided 3D Shape Synthesis is a text-to-3D shape generation model that can generate 3D shapes from text descriptions using a pre-trained CLIP model. The model can produce shapes with complex shapes, textures, and colors, and can be fine-tuned to generate shapes with specific styles and attributes.
  - **Code:** https://github.com/orpatashnik/CLIP-Guided-3D-Shape-Synthesis


### Text-prompted 3D Manipulation


#### 2024

- [CLIP-Guided 3D Shape Manipulation](https://arxiv.org/abs/2103.00020)
  - **Description:** CLIP-Guided 3D Shape Manipulation is a text-to-3D shape manipulation model that can manipulate 3D shapes from text descriptions using a pre-trained CLIP model. The model can manipulate shapes with complex shapes, textures, and colors, and can be fine-tuned to manipulate shapes with specific styles and attributes.
  - **Code:** https://github.com/orpatashnik/CLIP-Guided-3D-Shape-Manipulation


### Editable-3D


#### 2024

- [CLIP-Guided 3D Shape Manipulation](https://arxiv.org/abs/2103.00020)
  - **Description:** CLIP-Guided 3D Shape Manipulation is a text-to-3D shape manipulation model that can manipulate 3D shapes from text descriptions using a pre-trained CLIP model. The model can manipulate shapes with complex shapes, textures, and colors, and can be fine-tuned to manipulate shapes with specific styles and attributes.
  - **Code:** https://github.com/orpatashnik/CLIP-Guided-3D-Shape-Manipulation


## Other Resources

### Generic Datasets

- [FFHQ: A Free-to-use Dataset of Human Facial Images for Editing](https://github.com/NVlabs/ffhq-dataset)
  - **Description:** FFHQ is a dataset of human facial images for editing, including 10,000 images of real people with various expressions, backgrounds, and identities. The dataset is free to use and can be used for various applications such as face synthesis, image-to-image translation, and image editing.
  - **Code:** https://github.com/NVlabs/ffhq-dataset


### Generic Pre-trained Models

- [CLIP: Connecting Text and Images](https://github.com/openai/CLIP)
  - **Description:** CLIP is a pre-trained model that can be used for various tasks such as image and text-based image synthesis, image and text-based image manipulation, and text-based image retrieval.
  - **Code:** https://github.com/openai/CLIP