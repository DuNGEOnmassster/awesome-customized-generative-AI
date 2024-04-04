# awesome-customized-generative-AI
Papers and codes collection for customize, personalized and editable generative models in 2D and 3D domains.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Introduction
Artificial Intelligence Generated Content (AIGC) has become ubiquitous, demonstrating the power of generating mesmerizing results of random portraits. However, users generally show greater interest in personalized information (for example, faces from familiar people or celebrities) in these generated results than in generic faces. This tendency toward customization in AIGC arouses attention to customized, personalized, and editable generative AI. 

This repo mainly focuses on visual generative models (leaving out LLMs), including 2D image-to-image, 2D text-to-image, and text-guided 3D generation/manipulation, collecting customized, personalized, and editable works in these specific domains. For any addition about other 2D/3D AIGC domains or bugs report, please open an issue, pull requests, or e-mail me at `normanzheng6606@gmail.com` for better communication.

Frequantly updating, please stay tuned!

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

- FreeControl: Training-Free Spatial Control of Any Text-to-Image Diffusion Model with Any Condition `CVPR2024` [{Paper}](https://arxiv.org/abs/2312.07536) [{Code}](https://github.com/genforce/freecontrol.git) [{Webpage}](https://genforce.github.io/freecontrol/?utm_source=catalyzex.com) <details><summary>Details</summary><p align="center">  <img width="100%" src="figures/Customized-2D-Image-to-Image/image-prompted-generation/FreeControl/freecontrol.png"/> </p></details>

- Face2Diffusion for Fast and Editable Face Personalization `CVPR2024` [{Paper}](https://arxiv.org/abs/2403.05094) [{Code}](https://github.com/mapooon/face2diffusion) [{Webpage}](https://mapooon.github.io/Face2DiffusionPage/)<details><summary>Details</summary><p align="center">  <img width="100%" src="figures/Customized-2D-Image-to-Image/image-prompted-generation/Face2Diffusion/face2diffusion.png"/> </p></details>

- InstantID: Zero-shot Identity-Preserving Generation in Seconds `arxiv` [{Paper}](https://arxiv.org/abs/2401.07519) [{Code}](https://github.com/InstantID/InstantID.git) [{Webpage}](https://instantid.github.io/)<details><summary>Details</summary></summary><p align="center">
  <img width="100%" src="figures/Customized-2D-Image-to-Image/image-prompted-generation/InstantID/main-figure.png"/>
</p></details>


#### 2023

- IP-Adapter: Text Compatible Image Prompt Adapter for Text-to-Image Diffusion Models `arxiv` [{Paper}](https://arxiv.org/abs/2308.06721) [{Code}](https://github.com/tencent-ailab/IP-Adapter.git) [{Webpage}](https://ip-adapter.github.io/) <details>Also suitable for [Text-guided Portrait Generation](#text-guided-portrait-generation)<summary>Details</summary><p align="center">  <img width="100%" src="figures/Customized-2D-Image-to-Image/image-prompted-generation/IP-Adapter/IP-Adapter-ipg.png"/>

- ViscoNet: Bridging and Harmonizing Visual and Textual Conditioning for ControlNet `arxiv` [{Paper}](https://arxiv.org/abs/2312.03154) [{Code}](https://github.com/soon-yau/visconet.git) [{Webpage}](https://soon-yau.github.io/visconet/) <details>Also suitable for [Text-guided Image Editing](#text-guided-image-editing) and [Portrait Style Transfer](#portrait-style-transfer)<summary>Details</summary><p align="center">  <img width="100%" src="figures/Customized-2D-Image-to-Image/image-prompted-generation/ViscoNet/visconet.png"/>
</p></details>

- When StyleGAN Meets Stable Diffusion: a 𝒲+ Adapter for Personalized Image Generation `arxiv` [{Paper}](arxiv.org/abs/2311.17461) [{Code}](https://github.com/csxmli2016/w-plus-adapter) <details><summary>Details</summary><p align="center">  <img width="100%" src="figures/Customized-2D-Image-to-Image/image-prompted-generation/W-Plus-Adapter/w-plus-adapter.png"/>
</p></details>

#### 2022

- MyStyle: A Personalized Generative Prior `{ACM} Trans. Graph.` [{Paper}](https://arxiv.org/abs/2203.17272) [{Code}](https://github.com/google/mystyle) [{Webpage}](https://mystyle-personalized-prior.github.io/?utm_source=catalyzex.com) <details><summary>Details</summary><p align="center">  <img width="100%" src="figures/Customized-2D-Image-to-Image/image-prompted-generation/MyStyle/MyStyle.png"/>

### Portrait Style Transfer

#### 2024

- InstantStyle: Free Lunch towards Style-Preserving in Text-to-Image Generation `arxiv` [{Paper}](https://arxiv.org/abs/2404.02733) [{Code}](https://github.com/InstantStyle/InstantStyle.git)<details><summary>Details</summary></summary><p align="center">
  <img width="100%" src="figures/Customized-2D-Image-to-Image/portrait-style-transfer/InstantStyle/image-based-style-transfer.png"/>
</p></details>

#### 2023

- ViscoNet: Bridging and Harmonizing Visual and Textual Conditioning for ControlNet `arxiv` [{Paper}](https://arxiv.org/abs/2312.03154) [{Code}](https://github.com/soon-yau/visconet.git) [{Webpage}](https://soon-yau.github.io/visconet/) <details>Also suitable for [Image-prompted Generation](#image-prompted-generation) and [Text-guided Image Editing](#text-guided-image-editing)<summary>Details</summary><p align="center">  <img width="100%" src="figures/Customized-2D-Image-to-Image/portrait-style-transfer/visconet/visconet.png"/>
</p></details>


### Interactive Image Editing

#### 2024

- Transparent Image Layer Diffusion using Latent Transparency `arxiv` [{Paper}](https://arxiv.org/abs/2402.17113) [{Code}](https://github.com/layerdiffusion/sd-forge-layerdiffuse.git)<details>**Powerful PhotoShop cutout replacement!**<summary>Details</summary><p align="center">  <img width="100%" src="figures/Customized-2D-Image-to-Image/interactive-image-editing/layerdiffuse/sd-forge-layerdiffuse.png"/>
</p></details>

#### 2023

- Drag Your GAN: Interactive Point-based Manipulation on the Generative Image Manifold `SIGGRAPH 2023` [{Paper}](https://arxiv.org/abs/2305.10973) [{Code}](https://github.com/XingangPan/DragGAN.git) [{Webpage}](https://vcai.mpi-inf.mpg.de/projects/DragGAN/)

- DragDiffusion: Harnessing Diffusion Models for Interactive Point-based Image Editing `CVPR2024` [{Paper}](https://arxiv.org/abs/2306.14435) [{Code}](https://github.com/Yujun-Shi/DragDiffusion.git) [{Webpage}](https://yujun-shi.github.io/projects/dragdiffusion.html)

## Customized 2D Text-to-Image


### Text-guided Portrait Generation

#### 2024

- Pick-and-Draw: Training-free Semantic Guidance for Text-to-Image Personalization `arxiv` [{Paper}](https://arxiv.org/abs/2401.16762)<details><summary>Details</summary></details>

- StableIdentity: Inserting Anybody into Anywhere at First Sight `arxiv` [{Paper}](https://arxiv.org/abs/2401.15975) [{Code}](https://github.com/qinghew/StableIdentity.git) [{Webpage}](https://qinghew.github.io/StableIdentity/)<details>Also suitable for [Image-prompted 3D Generation](#image-prompted-3d-generation)<summary>Details</summary><p align="center">  <img width="100%" src="figures/customized-3d-generationmanipulation/image-prompted-3d-generation/StableIdentity/StableIdentity.png"/>
</p></details> 

- Towards a Simultaneous and Granular Identity-Expression Control in Personalized Face Generation `arxiv` [{Paper}](https://arxiv.org/abs/2401.01207) <details><summary>Details</summary><p align="center">  <img width="100%" src="figures/customized-2d-text-to-image/text-guided-portrait-generation/Towards-Identity-Expression/Towards-Identity-Expression.png"/>
</p></details> 

#### 2023

- IP-Adapter: Text Compatible Image Prompt Adapter for Text-to-Image Diffusion Models `arxiv` [{Paper}](https://arxiv.org/abs/2308.06721) [{Code}](https://github.com/tencent-ailab/IP-Adapter.git) [{Webpage}](https://ip-adapter.github.io/) <details>Also suitable for [Image-prompted Generation](#image-prompted-generation)<summary>Details</summary><p align="center">  <img width="100%" src="figures/customized-2d-text-to-image/text-guided-portrait-generation/IP-Adapter/IP-Adapter-tgpg.png"/>



### Text-guided Image Editing

#### 2024

- BootPIG: Bootstrapping Zero-shot Personalized Image Generation Capabilities in Pretrained Diffusion Models `arxiv` [{Paper}](https://arxiv.org/abs/2401.13974) <details><summary>Details</summary><p align="center">  <img width="100%" src="figures/customized-2d-text-to-image/text-guided-image-editing/BootPig/BootPig.png"/>

#### 2023

- ViscoNet: Bridging and Harmonizing Visual and Textual Conditioning for ControlNet `arxiv` [{Paper}](https://arxiv.org/abs/2312.03154) [{Code}](https://github.com/soon-yau/visconet.git) [{Webpage}](https://soon-yau.github.io/visconet/) <details>Also suitable for [Image-prompted Generation](#image-prompted-generation)  and [Portrait Style Transfer](#portrait-style-transfer)<summary>Details</summary><p align="center">  <img width="100%" src="figures/customized-2d-text-to-image/text-guided-image-editing/visconet/visconet.png"/>
</p></details>

## Customized 3D Generation/Manipulation

### Image-prompted 3D Generation


#### 2024

- StableIdentity: Inserting Anybody into Anywhere at First Sight `arxiv` [{Paper}](https://arxiv.org/abs/2401.15975) [{Code}](https://github.com/qinghew/StableIdentity.git) [{Webpage}](https://qinghew.github.io/StableIdentity/)<details>Also suitable for [Text-guided Portrait Generation](#text-guided-portrait-generation)<summary>Details</summary><p align="center">  <img width="100%" src="figures/customized-3d-generationmanipulation/image-prompted-3d-generation/StableIdentity/StableIdentity.png"/>
</p></details> 


### Text-prompted 3D Manipulation


#### 2024



#### 2023

- Instruct-NeRF2NeRF: Editing 3D Scenes with Instructions `ICCV2023` [{Paper}](https://arxiv.org/abs/2303.12789) [{Code}](https://github.com/ayaanzhaque/instruct-nerf2nerf) <details><summary>Details</summary><p align="center">  <img width="100%" src="figures/customized-3d-generationmanipulation/text-prompted-3d-manipulation/Instruct-nerf2nerf/in2n.png"/>


### Editable-3D


#### 2024


#### 2023

- GP-VTON: Towards General Purpose Virtual Try-on via Collaborative Local-Flow Global-Parsing Learning `CVPR2023` [{Paper}](https://arxiv.org/abs/2303.13756) [{Code}](https://github.com/xiezhy6/GP-VTON.git) <details><summary>Details</summary><p align="center">  <img width="100%" src="figures/customized-3d-generationmanipulation/editable-3d/GP-VTON/GP-VTON.png"/>
</p></details>



## Other Resources

### Generic Datasets

- Flickr-Faces-HQ Dataset (FFHQ) [{Paper}](https://arxiv.org/abs/1812.04948) [{Code}](https://github.com/NVlabs/ffhq-dataset.git) [{Download}](https://drive.google.com/drive/folders/1u2xu7bSrWxrbUxk-dT-UvEJq8IjdmNTP)

- CelebAMask-HQ [{Paper}](https://arxiv.org/abs/1907.11922) [{Code}](https://github.com/switchablenorms/CelebAMask-HQ) [{Download}](https://drive.google.com/file/d/1badu11NqxGf6qM3PTTooQDJvQbejgbTv/view)

- Multi-Modal-CelebA-HQ `CVPR 2021` [{Paper}](https://arxiv.org/abs/2012.03308) [{Code}](https://github.com/MarekKowalski/Multi-Modal-CelebA-HQ) [{Download}](https://drive.google.com/drive/folders/1TxsSzPhZsJNijIXPINv05IUWhG3vBU-X)

### Generic Pre-trained Models

- SD-v1-4 [{Paper}](https://arxiv.org/abs/2112.10752) [{Code}](https://github.com/compvis/stable-diffusion) [{HuggingFace}](https://huggingface.co/CompVis/stable-diffusion-v1-4) [{Blog}](https://huggingface.co/blog/stable_diffusion) [{Download}](https://huggingface.co/runwayml/stable-diffusion-v1-4/tree/main)<details>CompVis/stable-diffusion-v1-4<summary>Details</summary></details>

- SD-1-5 [{Paper}](https://arxiv.org/abs/2112.10752) [{Code}](https://github.com/compvis/stable-diffusion) [{HuggingFace}](https://huggingface.co/runwayml/stable-diffusion-v1-5) [{Blog}](https://huggingface.co/blog/stable_diffusion) [{Download}](https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main)<details>runwayml/stable-diffusion-v1-5<summary>Details</summary></details>

- SD-2-1-base [{Paper}](https://arxiv.org/abs/2112.10752) [{Code}](https://github.com/Stability-AI/stablediffusion) [{HuggingFace}](https://huggingface.co/stabilityai/stable-diffusion-2-1-base) [{Download}](https://huggingface.co/stabilityai/stable-diffusion-2-1-base/tree/main)<details>stabilityai/stable-diffusion-2-1-base<summary>Details</summary></details>

- SD-XL: Improving Latent Diffusion Models for High-Resolution Image Synthesis [{Paper}](https://arxiv.org/abs/2307.01952) [{Code}](https://github.com/stability-ai/generative-models) [{HuggingFace}](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0) [{Download}](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/tree/main)<details>stabilityai/stable-diffusion-xl-base-1.0<summary>Details</summary></details>

- sdxl-turbo (Adversarial Diffusion Distillation) [{Paper}](https://arxiv.org/abs/2311.17042) [{Code}](https://github.com/Stability-AI/generative-models) [{HuggingFace}](https://huggingface.co/stabilityai/stable-diffusion-xl-turbo-1.0) [{Download}](https://huggingface.co/stabilityai/sdxl-turbo/tree/main) [{Demo}](http://clipdrop.co/stable-diffusion-turbo)<details>stabilityai/sdxl-turbo<summary>Details</summary></details>