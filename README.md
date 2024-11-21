# Awesome Autoregressive Visual Generation Models [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <!-- omit in toc -->
A curated list of recent autoregressive models for image/video generation, editing, restoration, etc (only focusing on next-set prediction paradigm).

<p align="center">
<img src="visual.png"/>  
</p>

## Table of Contents <!-- omit in toc -->
- [Video Generation](#video-generation)
- [Long Video / Film Generation](#long-video--film-generation)
- [Image Generation](#image-generation)
- [Controllable Image Generation](#controllable-image-generation)
- [Multimodal Generation](#multimodal-generation)
- [Survey](#Survey)
- [Others](#Others)

### Video Generation 
+ [LARP: Tokenizing Videos with a Learned Autoregressive Generative Prior](https://arxiv.org/abs/2410.21264) (28 Oct 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.21264)
  [![Star](https://img.shields.io/github/stars/hywang66/LARP.svg?style=social&label=Star)](https://github.com/hywang66/LARP)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hywang66.github.io/larp/)

+ [ACDC: Autoregressive Coherent Multimodal Generation using Diffusion Correction](https://arxiv.org/abs/2410.04721)(7 Oct 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.04721)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://acdc2025.github.io/)

+ [VideoPoet: A Large Language Model for Zero-Shot Video Generation](https://arxiv.org/abs/2312.14125) (21 Dec 2023 & ICML 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.14125)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.research.google/videopoet/)

+ [Mirasol3B: A Multimodal Autoregressive model for time-aligned and contextual modalities](https://arxiv.org/abs/2311.05698) (9 Nov 2023 & CVPR 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.05698)
  [![Star](https://img.shields.io/github/stars/kyegomez/Mirasol.svg?style=social&label=Star)](https://github.com/kyegomez/Mirasol)

+ [Language Model Beats Diffusion -- Tokenizer is Key to Visual Generation](https://arxiv.org/abs/2310.05737v3) (9 Oct 2023 & ICLR 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.05737v3)

+ [MOSO: Decomposing MOtion, Scene and Object for Video Prediction](https://arxiv.org/abs/2303.03684) (7 Mar 2023 & CVPR 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.03684)
  [![Star](https://img.shields.io/github/stars/iva-mzsun/MOSO.svg?style=social&label=Star)](https://github.com/iva-mzsun/MOSO)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://iva-mzsun.github.io/MOSO)

+ [MaskViT: Masked Visual Pre-Training for Video Prediction](https://arxiv.org/abs/2206.11894) (23 Jun 2022)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2206.11894)
  [![Star](https://img.shields.io/github/stars/agrimgupta92/maskvit.svg?style=social&label=Star)](https://github.com/agrimgupta92/maskvit)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://maskedvit.github.io/)

+ [Tell Me What Happened: Unifying Text-guided Video Completion via Multimodal Masked Video Generation](https://arxiv.org/abs/2211.12824) (23 Nov 2022 & CVPR 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.12824)

+ [CogVideo: Large-scale Pretraining for Text-to-Video Generation via Transformers](https://arxiv.org/abs/2205.15868) (29 May 2022 & ICLR 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2205.15868)
  [![Star](https://img.shields.io/github/stars/THUDM/CogVideo.svg?style=social&label=Star)](https://github.com/THUDM/CogVideo)


+ [VideoGPT: Video Generation using VQ-VAE and Transformers](https://arxiv.org/abs/2104.10157) (20 Apr 2021)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2104.10157)
  [![Star](https://img.shields.io/github/stars/wilson1yan/VideoGPT.svg?style=social&label=Star)](https://github.com/wilson1yan/VideoGPT)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wilsonyan.com/videogpt/index.html)


### Long Video / Film Generation
+ [M-VAR: Decoupled Scale-wise Autoregressive Modeling for High-Quality Image Generation](https://arxiv.org/abs/2411.10433) (15 Nov 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.10433)
  [![Star](https://img.shields.io/github/stars/wilson1yan/VideoGPT.svg?style=social&label=Star)](https://github.com/OliverRensu/MVAR)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://oliverrensu.github.io/project/MVAR/mvar)

+ [ARLON: Boosting Diffusion Transformers with Autoregressive Models for Long Video Generation](https://arxiv.org/abs/2410.20502) (27 Oct 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.20502)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://arlont2v.github.io/)

+ [Loong: Generating Minute-level Long Videos with Autoregressive Language Models](https://arxiv.org/abs/2410.02757) (3 Oct 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.02757)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://epiphqny.github.io/Loong-video/)

+ [Phenaki: Variable length video generation from open domain textual descriptions](https://arxiv.org/abs/2210.02399) (5 Oct 2022 & ICLR 2022)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.02399)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.research.google/videopoet/)

+ [Long Video Generation with Time-Agnostic VQGAN and Time-Sensitive Transformer](https://arxiv.org/abs/2204.03638) (7 Apr 2022 & ECCV 2022)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2204.03638)
  [![Star](https://img.shields.io/github/stars/SongweiGe/TATS.svg?style=social&label=Star)](https://github.com/SongweiGe/TATS)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://songweige.github.io/projects/tats/index.html)

### Image Generation
+ [Randomized Autoregressive Visual Generation](https://arxiv.org/abs/2411.00776) (1 Nov 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.00776)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yucornetto.github.io/projects/rar.html)

+ [Where Am I and What Will I See: An Auto-Regressive Model for Spatial Localization and View Prediction](https://arxiv.org/abs/2410.18962) (24 Oct 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.18962)
  [![Star](https://img.shields.io/github/stars/SOTAMak1r/GST.svg?style=social&label=Star)](https://github.com/SOTAMak1r/GST)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sotamak1r.github.io/gst/)

+ [Elucidating the design space of language models for image generation](https://arxiv.org/abs/2410.16257)  (21 Oct 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.16257)
  [![Star](https://img.shields.io/github/stars/Pepper-lll/LMforImageGeneration.svg?style=social&label=Star)](https://github.com/Pepper-lll/LMforImageGeneration)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pepper-lll.github.io/LMforImageGeneration/)

+ [BiGR: Harnessing Binary Latent Codes for Image Generation and Improved Visual Representation Capabilities](https://arxiv.org/abs/2410.14672)  (18 Oct 2024)  
[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.14672)
[![Star](https://img.shields.io/github/stars/haoosz/BiGR.svg?style=social&label=Star)](https://github.com/haoosz/BiGR)
[![Website](https://img.shields.io/badge/Website-9cf)](https://haoosz.github.io/BiGR/)

+ [Fluid: Scaling Autoregressive Text-to-image Generative Models with Continuous Tokens](https://arxiv.org/abs/2410.13863)  (17 Oct 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.13863)

+ [Unlocking the Capabilities of Masked Generative Models for Image Synthesis via Self-Guidance](https://arxiv.org/abs/2410.13136)  (17 Oct 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.13136)
  [![Star](https://img.shields.io/github/stars/mit-han-lab/hart.svg?style=social&label=Star)](https://github.com/JiwanHur/UnlockMGM)

+ [Stabilize the Latent Space for Image Autoregressive Modeling: A Unified Perspective](https://arxiv.org/abs/2410.12490) (16 Oct 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.12490)
  [![Star](https://img.shields.io/github/stars/mit-han-lab/hart.svg?style=social&label=Star)](https://github.com/DAMO-NLP-SG/DiGIT)

+ [HART: Efficient Visual Generation with Hybrid Autoregressive Transformer](https://arxiv.org/abs/2410.10812) (14 Oct 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.08159v1)
  [![Star](https://img.shields.io/github/stars/mit-han-lab/hart.svg?style=social&label=Star)](https://github.com/mit-han-lab/hart)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hanlab.mit.edu/projects/hart)

+ [DART: Denoising Autoregressive Transformer for Scalable Text-to-Image Generation](https://arxiv.org/abs/2410.08159v1) (10 Oct 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.08159v1)

+ [LANTERN: Accelerating Visual Autoregressive Models with Relaxed Speculative Decoding](https://arxiv.org/abs/2410.03355) (4 Oct 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.03355)

+ [Accelerating Auto-regressive Text-to-Image Generation with Training-free Speculative Jacobi Decoding](https://arxiv.org/abs/2410.01699) (2 Oct 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.01699)

+ [AiM: Scalable Autoregressive Image Generation with Mamba](https://arxiv.org/abs/2408.12245) (22 Aug 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.12245)
  [![Star](https://img.shields.io/github/stars/hp-l33/AiM.svg?style=social&label=Star)](https://github.com/hp-l33/AiM)

+ [Lumina-mGPT: Illuminate Flexible Photorealistic Text-to-Image Generation with Multimodal Generative Pretraining](https://arxiv.org/abs/2408.02657) (5 Aug 2024)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.02657)
  [![Star](https://img.shields.io/github/stars/hp-l33/AiM.svg?style=social&label=Star)](https://github.com/Alpha-VLLM/Lumina-mGPT)

+ [VAR-CLIP: Text-to-Image Generator with Visual Auto-Regressive Modeling](https://arxiv.org/abs/2408.01181) (2 Aug 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.01181)
  [![Star](https://img.shields.io/github/stars/daixiangzi/VAR-CLIP.svg?style=social&label=Star)](https://github.com/daixiangzi/VAR-CLIP)

+ [MARS:Mixture of Auto-Regressive Models for Fine-grained Text-to-image Synthesis](https://arxiv.org/abs/2407.07614) (10 Jul 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.07614)
  [![Star](https://img.shields.io/github/stars/fusiming3/MARS.svg?style=social&label=Star)](https://github.com/fusiming3/MARS)

+ [Autoregressive Image Generation without Vector Quantization](https://arxiv.org/abs/2406.11838) (17 Jun 2024 & NeurIPS 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.11838)
  [![Star](https://img.shields.io/github/stars/LTH14/mar.svg?style=social&label=Star)](https://github.com/LTH14/mar)

+ [Autoregressive Model Beats Diffusion: Llama for Scalable Image Generation](https://arxiv.org/abs/2406.06525) (10 Jun 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.06525)
  [![Star](https://img.shields.io/github/stars/FoundationVision/LlamaGen.svg?style=social&label=Star)](https://github.com/FoundationVision/LlamaGen)

+ [Visual Autoregressive Modeling: Scalable Image Generation via Next-Scale Prediction](https://arxiv.org/abs/2404.02905) (3 Apr 2024 & NeurIPS 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.02905)
  [![Star](https://img.shields.io/github/stars/FoundationVision/VAR.svg?style=social&label=Star)](https://github.com/FoundationVision/VAR)

+ [Towards End-to-End Generative Modeling of Long Videos with Memory-Efficient Bidirectional Transformers](https://arxiv.org/abs/2303.11251) (20 May 2023 & CVPR 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.11251)
  [![Star](https://img.shields.io/github/stars/Ugness/MeBT.svg?style=social&label=Star)](https://github.com/Ugness/MeBT)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/mebt-cvpr2023)

+ [Muse: Text-to-image generation via masked generative transformers](https://arxiv.org/abs/2301.00704) (2 Jan 2023 & ICML 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2202.04200)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://muse-model.github.io/)

+ [Rethinking the Objectives of Vector-Quantized Tokenizers for Image Synthesis](https://arxiv.org/abs/2212.03185) (6 Dec 2022 & CVPR 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.03185)

+ [Vector-quantized Image Modeling with Improved VQGAN](https://arxiv.org/abs/2110.04627v3) (9 Oct 2022 & ICLR 2022)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2110.04627v3)

+ [MoVQ: Modulating Quantized Vectors for High-Fidelity Image Generation](https://arxiv.org/abs/2209.09002) (19 Seq 2022 & NeurIPS 2022)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.09002)

+ [Scaling Autoregressive Models for Content-Rich Text-to-Image Generation](https://arxiv.org/abs/2206.10789) (22 Jun 2022 & ICLR 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2206.10789)

+ [Autoregressive Image Generation using Residual Quantization](https://arxiv.org/abs/2203.01941) (3 Mar 2022 & CVPR 2022)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.01941)
  [![Star](https://img.shields.io/github/stars/kakaobrain/rq-vae-transformer.svg?style=social&label=Star)](https://github.com/kakaobrain/rq-vae-transformer)

+ [MaskGIT: Masked Generative Image Transformer](https://arxiv.org/abs/2202.04200) (8 Feb  2022 & CVPR 2022)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.00704)

+ [Draft-and-Revise: Effective Image Generation with Contextual RQ-Transformer](https://arxiv.org/abs/2206.04452) (9 Jun 2022 & NeurIPS 2022)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2206.04452)

+ [ImageBART: Bidirectional Context with Multinomial Diffusion for Autoregressive Image Synthesis](https://arxiv.org/abs/2108.08827) (19 Aug 2021 & NeurIPS 2021)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2108.08827)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://compvis.github.io/imagebart/)

+ [Zero-Shot Text-to-Image Generation](https://arxiv.org/abs/2102.12092) (24 Feb 2021 & ICML 2021)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2102.12092)

+ [Taming Transformers for High-Resolution Image Synthesis](https://arxiv.org/abs/2012.09841) (17 Dec 2020 & CVPR 2021)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2012.09841)
  [![Star](https://img.shields.io/github/stars/CompVis/taming-transformers.svg?style=social&label=Star)](https://github.com/CompVis/taming-transformers)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://compvis.github.io/taming-transformers/)

### Controllable Image Generation
+ [CAR: Controllable Autoregressive Modeling for Visual Generation](https://arxiv.org/abs/2410.04671v1) (7 Oct 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2102.12092))
  [![Star](https://img.shields.io/github/stars/MiracleDance/CAR.svg?style=social&label=Star)](https://github.com/MiracleDance/CAR)

+ [ControlAR: Controllable Image Generation with Autoregressive Models](https://arxiv.org/abs/2410.02705) (3 Oct 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.02705))
  [![Star](https://img.shields.io/github/stars/hustvl/ControlAR.svg?style=social&label=Star)](https://github.com/hustvl/ControlAR)

### Multimodal Visual Generation
+ [JanusFlow: Harmonizing Autoregression and Rectified Flow for Unified Multimodal Understanding and Generation]  (12 Nov 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.07975))
  [![Star](https://img.shields.io/github/stars/deepseek-ai/Janus.svg?style=social&label=Star)](https://github.com/deepseek-ai/Janus)

+ [Janus: Decoupling Visual Encoding for Unified Multimodal Understanding and Generation](https://arxiv.org/abs/2410.13848) (17 Oct 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.13848))
  [![Star](https://img.shields.io/github/stars/baaivision/Emu3.svg?style=social&label=Star)](https://github.com/deepseek-ai/Janus)

+ [PUMA: Empowering Unified MLLM with Multi-granular Visual Generation](https://arxiv.org/abs/2410.13861) (17 Oct 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.13861))
  [![Star](https://img.shields.io/github/stars/baaivision/Emu3.svg?style=social&label=Star)](https://github.com/rongyaofang/PUMA)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://rongyaofang.github.io/puma/)

+ [Emu3: Next-Token Prediction is All You Need](https://arxiv.org/abs/2409.18869) (27 Sep 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.18869))
  [![Star](https://img.shields.io/github/stars/baaivision/Emu3.svg?style=social&label=Star)](https://github.com/baaivision/Emu3)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://emu.baai.ac.cn/)

+ [MIO: A Foundation Model on Multimodal Tokens](https://arxiv.org/abs/2409.17692) (26 Sep 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.17692))

+ [MonoFormer: One Transformer for Both Diffusion and Autoregression](https://arxiv.org/abs/2409.16280) (24 Sep 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.16280))
  [![Star](https://img.shields.io/github/stars/MonoFormer/MonoFormer.svg?style=social&label=Star)](https://github.com/MonoFormer/MonoFormer)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://monoformer.github.io/)

+ [VILA-U: a Unified Foundation Model Integrating Visual Understanding and Generation](https://arxiv.org/abs/2409.04429) (6 Sep 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.04429))

+ [Transfusion: Predict the Next Token and Diffuse Images with One Multi-Modal Model](https://www.arxiv.org/abs/2408.11039) (20 Aug 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.11039))

+ [Show-o: One Single Transformer to Unify Multimodal Understanding and Generation](https://arxiv.org/abs/2408.12528) (22 Aug 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09985))
  [![Star](https://img.shields.io/github/stars/showlab/Show-o.svg?style=social&label=Star)](https://github.com/showlab/Show-o)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/Show-o/)

+ [ANOLE: An Open, Autoregressive, Native Large Multimodal Models for Interleaved Image-Text Generation](https://arxiv.org/abs/2407.06135) (8 Jul 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.06135))
  [![Star](https://img.shields.io/github/stars/GAIR-NLP/anole.svg?style=social&label=Star)](https://github.com/GAIR-NLP/anole)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://gair-nlp.github.io/anole)

+ [X-VILA: Cross-Modality Alignment for Large Language Model](https://arxiv.org/abs/2405.19335) (29 May 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.19335))

+ [Chameleon: Mixed-Modal Early-Fusion Foundation Models](https://arxiv.org/abs/2405.09818) (16 May 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.09818))
  [![Star](https://img.shields.io/github/stars/facebookresearch/chameleon.svg?style=social&label=Star)](https://github.com/facebookresearch/chameleon)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ai.meta.com/blog/meta-fair-research-new-releases/) 

+ [SEED-X: Multimodal Models with Unified Multi-granularity Comprehension and Generation](https://arxiv.org/abs/2404.14396) (22 Apr 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.14396)
  [![Star](https://img.shields.io/github/stars/AILab-CVC/SEED-X.svg?style=social&label=Star)](https://github.com/AILab-CVC/SEED-X)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://arc.tencent.com/en/ai-demos/multimodal)

+ [Mini-Gemini: Mining the Potential of Multi-modality Vision Language Models](https://arxiv.org/abs/2403.18814) (27 Mar 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.18814)
  [![Star](https://img.shields.io/github/stars/dvlab-research/MGM.svg?style=social&label=Star)](https://github.com/dvlab-research/MGM)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mini-gemini.github.io/) 

+ [AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling](https://arxiv.org/abs/2402.12226) (19 Feb 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.12226)
  [![Star](https://img.shields.io/github/stars/OpenMOSS/AnyGPT.svg?style=social&label=Star)](https://github.com/OpenMOSS/AnyGPT)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://junzhan2000.github.io/AnyGPT.github.io/) 

+ [World Model on Million-Length Video And Language With Blockwise RingAttention](https://arxiv.org/abs/2402.08268) (13 Feb 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.08268)
  [![Star](https://img.shields.io/github/stars/LargeWorldModel/LWM.svg?style=social&label=Star)](https://github.com/LargeWorldModel/LWM)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://largeworldmodel.github.io/) 

+ [Video-LaVIT: Unified Video-Language Pre-training with Decoupled Visual-Motional Tokenization](https://arxiv.org/abs/2402.03161) (5 Feb 2024 & ICML 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03161)
  [![Star](https://img.shields.io/github/stars/jy0205/LaVIT.svg?style=social&label=Star)](https://github.com/jy0205/LaVIT)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-lavit.github.io/) 

+ [WorldDreamer: Towards General World Models for Video Generation via Predicting Masked Tokens](https://arxiv.org/abs/2401.09985) (18 Jan 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09985))
  [![Star](https://img.shields.io/github/stars/JeffWang987/WorldDreamer.svg?style=social&label=Star)](https://github.com/JeffWang987/WorldDreamer)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://world-dreamer.github.io/)

+ [MM-Interleaved: Interleaved Image-Text Generative Modeling via Multi-modal Feature Synchronizer](https://arxiv.org/abs/2401.10208) (18 Jan 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.10208)
  [![Star](https://img.shields.io/github/stars/OpenGVLab/MM-Interleaved.svg?style=social&label=Star)](https://github.com/OpenGVLab/MM-Interleaved)

+ [Unified-IO 2: Scaling Autoregressive Multimodal Models with Vision, Language, Audio, and Action](https://arxiv.org/abs/2312.17172) (28 Dec 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.17172)
  [![Star](https://img.shields.io/github/stars/allenai/unified-io-2.svg?style=social&label=Star)](https://github.com/allenai/unified-io-2)

+ [Emu2: Generative Multimodal Models are In-Context Learners](https://arxiv.org/abs/2312.13286) (20 Dec 2023 & CVPR 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.13286)
  [![Star](https://img.shields.io/github/stars/baaivision/Emu.svg?style=social&label=Star)](https://github.com/baaivision/Emu)

+ [Gemini: A Family of Highly Capable Multimodal Models](https://arxiv.org/abs/2312.11805) (19 Dec 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.11805)

+ [VL-GPT: A Generative Pre-trained Transformer for Vision and Language Understanding and Generation](https://arxiv.org/abs/2312.09251) (14 Dec 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.09251)
  [![Star](https://img.shields.io/github/stars/AILab-CVC/VL-GPT.svg?style=social&label=Star)](https://github.com/AILab-CVC/VL-GPT)

+ [DreamLLM: Synergistic Multimodal Comprehension and Creation](https://arxiv.org/abs/2309.11499) (26 Sep 2023 & ICLR 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.11499)
  [![Star](https://img.shields.io/github/stars/RunpeiDong/DreamLLM.svg?style=social&label=Star)](https://github.com/RunpeiDong/DreamLLM)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamllm.github.io/) 

+ [NExT-GPT: Any-to-Any Multimodal LLM](https://arxiv.org/abs/2309.05519) (11 Sep 2023 & ICML 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.05519)
  [![Star](https://img.shields.io/github/stars/NExT-GPT/NExT-GPT.svg?style=social&label=Star)](https://github.com/NExT-GPT/NExT-GPT)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://next-gpt.github.io/) 

+ [LaVIT: Unified Language-Vision Pretraining in LLM with Dynamic Discrete Visual Tokenization](https://arxiv.org/abs/2309.04669) (9 Sep 2023 & ICLR 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.04669)
  [![Star](https://img.shields.io/github/stars/jy0205/LaVIT.svg?style=social&label=Star)](https://github.com/jy0205/LaVIT)

+ [Emu: Generative Pretraining in Multimodality](https://arxiv.org/abs/2307.05222) (11 Jul 2023 & ICLR 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.05222)
  [![Star](https://img.shields.io/github/stars/baaivision/Emu.svg?style=social&label=Star)](https://github.com/baaivision/Emu)

+ [CoDi: Any-to-Any Generation via Composable Diffusion](https://arxiv.org/abs/2305.11846) (19 May 2023 & NeurIPS 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11846)
  [![Star](https://img.shields.io/github/stars/microsoft/i-Code.svg?style=social&label=Star)](https://github.com/microsoft/i-Code/tree/main/i-Code-V3)

### Survey
+ [A Survey on Vision Autoregressive Model] (13 Nov 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.08666)

+ [Autoregressive Models in Vision: A Survey] (8 Nov 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.05902)

### Others
+ [Bailando: 3D Dance Generation by Actor-Critic GPT with Choreographic Memory](https://arxiv.org/abs/2203.13055) (Mar 2022 & CVPR 2022)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.13055))
  [![Star](https://img.shields.io/github/stars/lisiyao21/Bailando.svg?style=social&label=Star)](https://github.com/lisiyao21/Bailando)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.mmlab-ntu.com/project/bailando/index.html)