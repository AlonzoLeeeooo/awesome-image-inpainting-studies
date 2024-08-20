<p align="center">
  <h1 align="center">A Collection of Image Inpainting Studies</h1>

This GitHub repository summarizes papers and resources related to the image inpainting task. 

If you have any suggestions about this repository, please feel free to [start a new issue](https://github.com/AlonzoLeeeooo/awesome-image-inpainting-studies/issues/new) or [pull requests](https://github.com/AlonzoLeeeooo/awesome-image-inpainting-studies/pulls).

<!-- omit in toc -->
# 🔥News
- [May 17th] Our paper titled ["Towards Interactive Image Inpainting via Robust Sketch Refinement"](https://ieeexplore.ieee.org/document/10533842) is accepted by TMM 2024! 
- [Mar. 7th] **CVPR 2024, AAAI 2024, ICLR 2024 papers are updated.** PDFs and references will be updated as soon as they are released. [May 29th] Papers with "⚠" are updated.

<!-- omit in toc -->
# <span id="contents">Contents</span>
- [To-Do Lists](#to-do-lists)
- [Papers](#papers) _(Mainly Deep Learning-Based)_
  - [🔥Text-Guided Image Inpainting](#🔥-text-guided-image-inpainting)
    - [Year 2024](#text-year-2024)
    - [Year 2023](#text-year-2023)
    - [Year 2022](#text-year-2022)
    - [Year 2021](#text-year-2021)
    - [Year 2020](#text-year-2020)
  - [Vanilla Image Inpainting](#vanilla-image-inpainting)
    - [Year 2024](#vanilla-year-2024)
    - [Year 2023](#vanilla-year-2023)
    - [Year 2022](#vanilla-year-2022)
    - [Year 2021](#vanilla-year-2021)
    - [Year 2020](#vanilla-year-2020)
    - [Year 2019](#vanilla-year-2019)
    - [Year 2018](#vanilla-year-2018)
    - [Year 2017](#vanilla-year-2017)
    - [Year 2016](#vanilla-year-2016)
  - [Blind Image Inpainting](#blind-image-inpainting)
    - [Year 2023](#blind-year-2023)
    - [Year 2022](#blind-year-2022)
    - [Year 2020](#blind-year-2020)
  - [Edge-Based Image Inpainting](#edge-based-image-inpainting)
    - [Year 2023](#edge-year-2023)
    - [Year 2022](#edge-year-2022)
    - [Year 2021](#edge-year-2021)
    - [Year 2019](#edge-year-2019)
  - [Sketch-Guided Image Inpainting](#sketch-guided-image-inpainting)
    - [Year 2024](#sketch-year-2024)
    - [Year 2023](#sketch-year-2023)
    - [Year 2022](#sketch-year-2022)
    - [Year 2021](#sketch-year-2021)
    - [Year 2019](#sketch-year-2019)
  - [Face Image Inpainting](#face-image-inpainting)
    - [Year 2023](#face-year-2023)
    - [Year 2021](#face-year-2021)
    - [Year 2020](#face-year-2020)
    - [Year 2017](#face-year-2017)
  - [Fashion Image Inpainting](#fashion-image-inpainting)
    - [Year 2020](#fashion-year-2020)
    - [Year 2019](#fashion-year-2019)
  - [Conventional Methods](#conventional-methods) _(Non Deep Learning-Based)_
      - [Year 2024](#conventional-year-2024)
      - [Year 2020](#conventional-year-2020)
      - [Year 2019](#conventional-year-2019)
      - [Year 2018](#conventional-year-2018)
      - [Year 2016](#conventional-year-2016)
      - [Year 2011](#conventional-year-2011)
      - [Year 2005](#conventional-year-2005)
      - [Year 2004](#conventional-year-2004)
      - [Year 2000](#conventional-year-2000)
- [Survey Papers](#survey-papers)
- [Datasets](#datasets)
- [Q&A](#qa)
- [References](#references)
- [Star History](#star-history)

<!-- omit in toc -->
# To-Do Lists
- Recent Papers
  - [ ] Update ECCV 2024 Papers
  - [x] Update CVPR 2024 Papers
  - [x] Update AAAI 2024 Papers
    - [x] Update PDFs and References
  - [x] Update ICLR 2024 Papers
  - [ ] Update NeurIPS 2024 Papers
  - Regular Maintenance of Preprint arXiv Papers and Missed Papers
- Previous Papers
  - Published Papers on Conferences
    - [x] Update CVPR papers
    - [x] Update CVPRW papers
    - [x] Update ICCV papers
    - [x] Update ICCVW papers
    - [x] Update ECCV papers
    - [x] Update AAAI papers
    - [x] Update IJCAI papers
    - [x] Update ACM MM papers
    - [x] Update WACV papers
    - [x] Update NeurIPS papers
    - [x] Update ICLR papers
  - Published Papers on Journals
    - [x] Update TMM papers
    - [x] Update TIP papers 
    - [x] Update TPAMI papers
    - [x] Update TCSVT papers

[<u><small><🎯Back to Top></small></u>](#contents)


<!-- omit in toc -->
# Papers

<!-- omit in toc -->
## 🔥 Text-Guided Image Inpainting
- <span id="text-year-2024">**Year 2024**</span>
  - **ECCV**
    - A Task is Worth One Word: Learning with Task Prompts for High-Quality Versatile Image Inpainting [[Paper]](https://arxiv.org/pdf/2312.03594) [[Code]](https://powerpaint.github.io/) [[Project]](https://powerpaint.github.io/)
  - **ICLR**
    - ***MaGIC:*** Multi-modality Guided Image Completion [[Paper]](https://openreview.net/pdf?id=o7x0XVlCpX) [[Code]](https://github.com/yeates/MaGIC)
  - **SIGGRAPH**
    - ***RealFill:*** Reference-Driven Generation for Authentic Image Completion [[Paper]](https://arxiv.org/html/2309.16668v2) [[Code]](https://github.com/thuanz123/realfill) [[Project]](https://realfill.github.io/)
  - **arXiv**
    - Outline-Guided Object Inpainting with Diffusion Models [[Paper]](https://arxiv.org/pdf/2402.16421.pdf)
    - ***DesignEdit:*** Multi-Layered Latent Decomposition and Fusion for Unified & Accurate Image Editing [[Paper]](https://arxiv.org/pdf/2403.14487.pdf) [[Code]](https://github.com/design-edit/DesignEdit) [[Project]](https://design-edit.github.io/)
    - ***BrushNet:*** A Plug-and-Play Image Inpainting Model with Decomposed Dual-Branch Diffusion [[Paper]](https://arxiv.org/pdf/2403.06976) [[Code]](https://github.com/TencentARC/BrushNet) [[Project]](https://tencentarc.github.io/BrushNet/) [[Demo]](https://huggingface.co/spaces/TencentARC/BrushNet) [[Video]](https://drive.google.com/file/d/1IkEBWcd2Fui2WHcckap4QFPcCI0gkHBh/view?usp=sharing)
    - ***Anywhere:*** A Multi-Agent Framework for Reliable and Diverse Foreground-Conditioned Image Inpainting [[Paper]](https://arxiv.org/abs/2404.18598) [[Code]](https://github.com/Sealical/anywhere-multi-agent) [[Project]](https://anywheremultiagent.github.io/)
- <span id="text-year-2023">**Year 2023**</span> 
  - **CVPR**
    - ***NÜWA-LIP:*** Language-guided Image Inpainting with Defect-free VQGAN [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Ni_NUWA-LIP_Language-Guided_Image_Inpainting_With_Defect-Free_VQGAN_CVPR_2023_paper.pdf) [[Code]](https://github.com/kodenii/NUWA-LIP)
    - ***Imagen Editor and EditBench:*** Advancing and Evaluating Text-Guided Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Imagen_Editor_and_EditBench_Advancing_and_Evaluating_Text-Guided_Image_Inpainting_CVPR_2023_paper.pdf)
    - ***SmartBrush:*** Text and Shape Guided Object Inpainting with Diffusion Model [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Xie_SmartBrush_Text_and_Shape_Guided_Object_Inpainting_With_Diffusion_Model_CVPR_2023_paper.pdf)
    - ***Paint by Example:*** Exemplar-based Image Editing with Diffusion Models [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Yang_Paint_by_Example_Exemplar-Based_Image_Editing_With_Diffusion_Models_CVPR_2023_paper.pdf) [[Code]](https://github.com/Fantasy-Studio/Paint-by-Example) [[Demo]](https://huggingface.co/spaces/Fantasy-Studio/Paint-by-Example)
  - **CVPRW**
    - Scene Graph Driven Text-Prompt Generation for Image Inpainting
[[Paper]](https://openaccess.thecvf.com/content/CVPR2023W/GCV/papers/Shukla_Scene_Graph_Driven_Text-Prompt_Generation_for_Image_Inpainting_CVPRW_2023_paper.pdf)
  - **ACM MM**
    - ***Uni-paint:*** A Unified Framework for Multimodal Image Inpainting with Pretrained Diffusion Model [[Paper]](https://dl.acm.org/doi/abs/10.1145/3581783.3612200) [[Code]](https://github.com/ysy31415/unipaint)
  - **SIGGRAPH**
    - Blended Latent Diffusion [[Paper]](https://omriavrahami.com/blended-latent-diffusion-page/static/paper/Blended_Latent_Diffusion_Paper.pdf) [[Code]](https://github.com/omriav/blended-diffusion?tab=readme-ov-file) [[Project]](https://omriavrahami.com/blended-latent-diffusion-page/)
  - **WACV**
    - An Unified Framework for Language Guided Image Completion [[Paper]](https://openaccess.thecvf.com/content/WACV2023/papers/Kim_An_Unified_Framework_for_Language_Guided_Image_Completion_WACV_2023_paper.pdf)
    - Interactive Image Manipulation with Complex Text Instructions [[Paper]](https://openaccess.thecvf.com/content/WACV2023/papers/Morita_Interactive_Image_Manipulation_With_Complex_Text_Instructions_WACV_2023_paper.pdf)
- <span id="text-year-2022">**Year 2022**</span> 
  - **CVPR**
    - Blended Diffusion for Text-driven Editing of Natural Images [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Avrahami_Blended_Diffusion_for_Text-Driven_Editing_of_Natural_Images_CVPR_2022_paper.pdf) [[Code]](https://github.com/omriav/blended-diffusion)
- <span id="text-year-2021">**Year 2021**</span> 
  - **CVPRW**
    - Grounded, Controllable and Debiased Image Completion With Lexical Semantics [[Paper]](https://openaccess.thecvf.com/content/CVPR2021W/CiV/papers/Zhang_Grounded_Controllable_and_Debiased_Image_Completion_With_Lexical_Semantics_CVPRW_2021_paper.pdf)
  - **ACM MM**
    - Adversarial Learning with Mask Reconstruction for Text-Guided Image Inpainting [[Paper]](https://dl.acm.org/doi/abs/10.1145/3474085.3475506)
- <span id="text-year-2020">**Year 2020**</span> 
  - **ACM MM**
    - ***MMFL:*** Multimodal Fusion Learning for Text-Guided Image Inpainting [[Paper]](https://dl.acm.org/doi/10.1145/3394171.3413982) [[Code]](https://github.com/AliceQLin/MMFL-Inpainting)
    - Text-Guided Neural Image Inpainting [[Paper]](https://arxiv.org/pdf/2004.03212.pdf) [[Code]](https://github.com/idealwhite/TDANet)
    - Text-Guided Image Inpainting [[Paper]](https://doi.org/10.1145/3394171.3413939)

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
## Vanilla Image Inpainting
- <span id="vanilla-year-2024">**Year 2024**</span> 
  - **CVPR**
    - ***Structure Matters:*** Tackling the Semantic Discrepancy in Diffusion Models for Image Inpainting [[Paper]](https://arxiv.org/abs/2403.19898) [[Code]](https://github.com/htyjers/StrDiffusion)
    - Don't Look into the Dark: Latent Codes for Pluralistic Image Inpainting [[Paper]](https://arxiv.org/pdf/2403.18186) 
  - **WACV**
    - Efficient Layout-Guided Image Inpainting for Mobile Use [[Paper]](https://openaccess.thecvf.com/content/WACV2024/papers/Li_Efficient_Layout-Guided_Image_Inpainting_for_Mobile_Use_WACV_2024_paper.pdf)
  - **AAAI**
    - Text Image Inpainting via Global Structure-Guided Diffusion Models [[Paper]](https://arxiv.org/pdf/2401.14832.pdf) [[Code]](https://github.com/blackprotoss/GSDM)
    - ***SyFormer:*** Structure-Guided Synergism Transformer for Large-Portion Image Inpainting [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/28417) [[Code]](https://github.com/ZhengJianwei2/SyFormer)
    - Large Occluded Human Image Completion via Image-Prior Cooperating [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/28578) [[Code]](https://github.com/ZhaoHengrun/LOHC)
  - **ICLR**
    - Image Inpainting via Tractable Steering of Diffusion Models [[Paper]](https://openreview.net/attachment?id=NSIVHTbZBR&name=pdf)
    - Image Inpainting via Iteratively Decoupled Probabilistic Modeling [[Paper]](https://openreview.net/attachment?id=rUf9G9k2im&name=pdf) [[Code]](https://github.com/fenglinglwb/PSM)
  - **TMM**
    - Mutual Dual-Task Generator With Adaptive Attention Fusion for Image Inpainting [[Paper]](https://ieeexplore.ieee.org/document/10143682)
  - **TCSVT**
    - Transformer-Based Image Inpainting Detection via Label Decoupling and Constrained Adversarial Training [[Paper]](https://ieeexplore.ieee.org/document/10196329)
  - **arXiv**
    - ***HINT:*** High-quality INPainting Transformer with Mask-Aware Encoding and Enhanced Attention [[Paper]](https://arxiv.org/pdf/2402.14185.pdf)
    - Rethinking Referring Object Removal [[Paper]](https://arxiv.org/pdf/2403.09128.pdf)

 [<u><small><🎯Back to Top></small></u>](#contents)

- <span id="vanilla-year-2023">**Year 2023**</span> 
  - **CVPRW**
    - Image Inpainting with Hypergraphs for Resolution Improvement in Scanning Acoustic Microscopy [[Paper]](https://openaccess.thecvf.com/content/CVPR2023W/DL-UIA/papers/Somani_Image_Inpainting_With_Hypergraphs_for_Resolution_Improvement_in_Scanning_Acoustic_CVPRW_2023_paper.pdf)
    - Internal Diverse Image Completion [[Paper]](https://openaccess.thecvf.com/content/CVPR2023W/GCV/papers/Alkobi_Internal_Diverse_Image_Completion_CVPRW_2023_paper.pdf) [[Code]](https://github.com/NoaAlkobi/IDC)
  - **ICCVW**
    - ***TransInpaint:*** Transformer-based Image Inpainting with Context Adaptation [[Paper]](https://openaccess.thecvf.com/content/ICCV2023W/NIVT/papers/Shamsolmoali_TransInpaint_Transformer-Based_Image_Inpainting_with_Context_Adaptation_ICCVW_2023_paper.pdf)
  - **AAAI**
    - ***CoordFill:*** Efficient High-Resolution Image Inpainting via Parameterized Coordinate Querying [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/25263/25035) [[Code]](https://github.com/NiFangBaAGe/CoordFill)
    - Generative Image Inpainting with Segmentation Confusion Adversarial Training and Contrastive Learning [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/25502/25274) [[Code]](https://github.com/zzw-zjgsu/Generative-Image-Inpainting)
  - **WACV**
    - Keys to Better Image Inpainting: Structure and Texture Go Hand in Hand [[Paper]](https://openaccess.thecvf.com/content/WACV2023/papers/Jain_Keys_To_Better_Image_Inpainting_Structure_and_Texture_Go_Hand_WACV_2023_paper.pdf) [[Code]](https://github.com/SHI-Labs/FcF-Inpainting)
    - ***GeoFill:*** Reference-Based Image Inpainting with Better Geometric Understanding [[Paper]](https://openaccess.thecvf.com/content/WACV2023/papers/Zhao_GeoFill_Reference-Based_Image_Inpainting_With_Better_Geometric_Understanding_WACV_2023_paper.pdf)
    - Image Completion with Heterogeneously Filtered Spectral Hints [[Paper]](https://openaccess.thecvf.com/content/WACV2023/papers/Xu_Image_Completion_With_Heterogeneously_Filtered_Spectral_Hints_WACV_2023_paper.pdf) [[Code]](https://github.com/SHI-Labs/SH-GAN)
  - **TMM**
    - Learning Adaptive Patch Generators for Mask-Robust Image Inpainting [[Paper]](https://ieeexplore.ieee.org/document/9773024)
    - ***W-Net:*** Structure and Texture Interaction for Image Inpainting [[Paper]](https://ieeexplore.ieee.org/document/9939091) [[Code]](https://github.com/Evergrow/W-Net)
  - **TIP**
    - Progressive Contextual Aggregation Empowered by Pixel-Wise Confidence Scoring for Image Inpainting [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10038694)
    - ***MagConv:*** Mask-Guided Convolution for Image Inpainting [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10197350)
    - Context Adaptive Network for Image Inpainting [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10197333)
  - **TPAMI**
    - Partial Convolution for Padding, Inpainting, and Image Synthesis [[Paper]](https://repository.bilkent.edu.tr/bitstream/handle/11693/111449/Partial_Convolution_for_Padding_Inpainting_and_Image_Synthesis.pdf?sequence=1) [[Code]](https://github.com/XingangPan/deep-generative-prior)
  - **TCSVT**
    - Deep Image Inpainting With Enhanced Normalization and Contextual Attention [[Paper]](https://ieeexplore.ieee.org/document/9775085)

 [<u><small><🎯Back to Top></small></u>](#contents)

- <span id="vanilla-year-2022">**Year 2022**</span>
  - **CVPR**
    - ***MISF:*** Multi-level Interactive Siamese Filtering for High-Fidelity Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_MISF_Multi-Level_Interactive_Siamese_Filtering_for_High-Fidelity_Image_Inpainting_CVPR_2022_paper.pdf) [[Code]](https://github.com/tsingqguo/misf)
    - ***MAT:*** Mask-Aware Transformer for Large Hole Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_MAT_Mask-Aware_Transformer_for_Large_Hole_Image_Inpainting_CVPR_2022_paper.pdf) [[Code]](https://github.com/fenglinglwb/MAT)
    - Reduce Information Loss in Transformers for Pluralistic Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Reduce_Information_Loss_in_Transformers_for_Pluralistic_Image_Inpainting_CVPR_2022_paper.pdf) [[Code]](https://github.com/liuqk3/PUT)
    - Dual-path Image Inpainting with Auxiliary GAN Inversion [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Dual-Path_Image_Inpainting_With_Auxiliary_GAN_Inversion_CVPR_2022_paper.pdf)
    - ***RePaint:*** Inpainting using Denoising Diffusion Probabilistic Models [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Lugmayr_RePaint_Inpainting_Using_Denoising_Diffusion_Probabilistic_Models_CVPR_2022_paper.pdf) [[Code]](https://github.com/andreas128/RePaint)
    - ***TFill:*** Bridging Global Context Interactions for High-Fidelity Image Completion [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zheng_Bridging_Global_Context_Interactions_for_High-Fidelity_Image_Completion_CVPR_2022_paper.pdf) [[Code]](https://github.com/lyndonzheng/TFill) [[Project]](https://chuanxiaz.com/tfill/) [[Video]](https://www.youtube.com/embed/efB1fw0jiLs)
  - **CVPRW**
    - ***Zoom-to-Inpaint:*** Image Inpainting with High-Frequency Details [[Paper]](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Kim_Zoom-to-Inpaint_Image_Inpainting_With_High-Frequency_Details_CVPRW_2022_paper.pdf) [[Code]](https://github.com/google/zoom-to-inpaint)
    - Boundary-aware Image Inpainting with Multiple Auxiliary Cues [[Paper]](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Yamashita_Boundary-Aware_Image_Inpainting_With_Multiple_Auxiliary_Cues_CVPRW_2022_paper.pdf) [[Code]](https://github.com/rain58/Boundary-aware-Image-Inpainting)
    - Comparison of CoModGANs, LaMa and GLIDE for Art Inpainting Completing M.C Escher's Print Gallery [[Paper]](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Cipolina-Kun_Comparison_of_CoModGans_LaMa_and_GLIDE_for_Art_Inpainting_Completing_CVPRW_2022_paper.pdf)
    - Image Multi-Inpainting via Progressive Generative Adversarial Networks [[Paper]](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Cai_Image_Multi-Inpainting_via_Progressive_Generative_Adversarial_Networks_CVPRW_2022_paper.pdf)
    - NTIRE 2022 Image Inpainting Challenge: Report [[Paper]](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Romero_NTIRE_2022_Image_Inpainting_Challenge_Report_CVPRW_2022_paper.pdf) [[Code]](https://github.com/affromero/NTIRE22_Inpainting)
    - ***GLaMa:*** Joint Spatial and Frequency Loss for General Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Lu_GLaMa_Joint_Spatial_and_Frequency_Loss_for_General_Image_Inpainting_CVPRW_2022_paper.pdf)
    - ***PersonGONE:*** Image Inpainting for Automated Checkout Solution [[Paper]](https://openaccess.thecvf.com/content/CVPR2022W/AICity/papers/Bartl_PersonGONE_Image_Inpainting_for_Automated_Checkout_Solution_CVPRW_2022_paper.pdf) [[Code]](https://github.com/BUT-GRAPH-at-FIT/PersonGONE)
  - **ECCV**
    - ***MAE-FAR:*** Learning Prior Feature and Attention Enhanced Image Inpainting [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136750303.pdf) [[Code]](https://github.com/ewrfcas/MAE-FAR) 
    - ***InvertFill:*** High-Fidelity Image Inpainting with GAN Inversion [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136760228.pdf) [[Code]](https://github.com/yeates/InvertFill)
    - ***CM-GAN:*** Image Inpainting with Cascaded Modulation GAN and Object-Aware Training [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136760263.pdf) [[Code]](https://github.com/htzheng/CM-GAN-Inpainting)
    - Unbiased Multi-Modality Guidance for Image Inpainting [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136760645.pdf) [[Code]](https://github.com/yeates/MMT)
    - Inpainting at Modern Camera Resolution by Guided PatchMatch with Auto-Curation [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136770051.pdf) [[Code]](https://github.com/owenzlz/SuperCAF)
    - Hourglass Attention Network for Image Inpainting [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136780474.pdf) [[Code]](https://github.com/dengyecode/hourglassattention)
    - Diverse Image Inpainting with Normalizing Flow [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136830053.pdf)
    - Perceptual Artifacts Localization for Inpainting [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136890145.pdf) [[Code]](https://github.com/owenzlz/PAL4Inpaint)
    - Iterative Geometry-Aware Cross Guidance Network for Stereo Image Inpainting [[Paper]](https://www.ijcai.org/proceedings/2022/0147.pdf)
  - **ACM MM**
    - Delving Globally into Texture and Structure for Image Inpainting [[Paper]](https://dl.acm.org/doi/abs/10.1145/3503161.3548265) [[Code]](https://github.com/htyjers/DGTS-Inpainting)
    - Atrous Pyramid Transformer with Spectral Convolution for Image Inpainting [[Paper]](https://dl.acm.org/doi/abs/10.1145/3503161.3548348)
    - Deep Multi-Resolution Mutual Learning for Image Inpainting [[Paper]](https://dl.acm.org/doi/abs/10.1145/3503161.3548030)
    - ***T-former:*** An Efficient Transformer for Image Inpainting [[Paper]](https://dl.acm.org/doi/abs/10.1145/3503161.3548446) [[Code]](https://github.com/dengyecode/T-former_image_inpainting)
  - **WACV**
    - ***LaMa:*** Resolution-robust Large Mask Inpainting with Fourier Convolutions [[Paper]](https://openaccess.thecvf.com/content/WACV2022/papers/Suvorov_Resolution-Robust_Large_Mask_Inpainting_With_Fourier_Convolutions_WACV_2022_paper.pdf) [[Code]](https://github.com/advimman/lama)
  - **NeurIPS**
    - Cross-Image Context for Single Image Inpainting [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/09b6e009612875dd0a7291d5f4fd8b49-Paper-Conference.pdf)
  - **TMM**
    - Deep Generative Model for Image Inpainting With Local Binary Pattern Learning and Spatial Attention [[Paper]](https://ieeexplore.ieee.org/document/9537606/) [[Code]](https://github.com/HighwayWu/ImageInpainting)
  - **TIP**
    - Image Inpainting With Local and Global Refinement [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9730792)
    - Pseudo Decoder Guided Light-Weight Architecture for Image Inpainting [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9920660)
  - **TPAMI**
    - Exploiting Deep Generative Prior for Versatile Image Restoration and Manipulation [[Paper]](https://doi.org/10.1109/TPAMI.2021.3115428) [[Code]](https://github.com/XingangPan/deep-generative-prior) [[Video]](https://www.youtube.com/watch?v=p7ToqtwfVko&feature=youtu.be)
  - **TCSVT** 
    - Dual-Pyramidal Image Inpainting With Dynamic Normalization [[Paper]](https://ieeexplore.ieee.org/document/9751095)
  - **arXiv**
    - ***GRIG:*** Few-Shot Generative Residual Image Inpainting [[Paper]](https://arxiv.org/abs/2304.12035) [[Code]](https://github.com/LonglongaaaGo/GRIG_few_shot_inpainting) [[Project]](https://longlongaaago.github.io/GRIG_few_shot_inpainting/)

 [<u><small><🎯Back to Top></small></u>](#contents)

- <span id="vanilla-year-2021">**Year 2021**</span>
  - **CVPR**
    - ***TransFill:*** Reference-Guided Image Inpainting by Merging Multiple Color and Spatial Transformations [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhou_TransFill_Reference-Guided_Image_Inpainting_by_Merging_Multiple_Color_and_Spatial_CVPR_2021_paper.pdf) [[Code]](https://github.com/yzhouas/TransFill-Reference-Inpainting)
    - Image Inpainting With External-Internal Learning and Monochromic Bottleneck [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_Image_Inpainting_With_External-Internal_Learning_and_Monochromic_Bottleneck_CVPR_2021_paper.pdf) [[Code]](https://github.com/Tengfei-Wang/external-internal-inpainting)
    - Image Inpainting Guided by Coherence Priors of Semantics and Textures [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Liao_Image_Inpainting_Guided_by_Coherence_Priors_of_Semantics_and_Textures_CVPR_2021_paper.pdf)
    - ***PD-GAN:*** Probabilistic Diverse GAN for Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_PD-GAN_Probabilistic_Diverse_GAN_for_Image_Inpainting_CVPR_2021_paper.pdf) [[Code]](https://github.com/KumapowerLIU/PD-GAN)
    - Generating Diverse Structure for Image Inpainting With Hierarchical VQ-VAE [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Peng_Generating_Diverse_Structure_for_Image_Inpainting_With_Hierarchical_VQ-VAE_CVPR_2021_paper.pdf) [[Code]](https://github.com/USTC-JialunPeng/Diverse-Structure-Inpainting)
  - **ICCV**
    - Distillation-guided Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Suin_Distillation-Guided_Image_Inpainting_ICCV_2021_paper.pdf)
    - ***WaveFill:*** A Wavelet-based Generation Network for Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Yu_WaveFill_A_Wavelet-Based_Generation_Network_for_Image_Inpainting_ICCV_2021_paper.pdf) [[Code]](https://github.com/yingchen001/WaveFill)
    - ***CR-Fill:*** Generative Image Inpainting with Auxiliary Contextual Reconstruction [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Zeng_CR-Fill_Generative_Image_Inpainting_With_Auxiliary_Contextual_Reconstruction_ICCV_2021_paper.pdf) [[Code]](https://github.com/zengxianyu/crfill)
    - Parallel Multi-Resolution Fusion Network for Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Parallel_Multi-Resolution_Fusion_Network_for_Image_Inpainting_ICCV_2021_paper.pdf)
    - ***ICT:*** High-Fidelity Pluralistic Image Completion with Transformers [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wan_High-Fidelity_Pluralistic_Image_Completion_With_Transformers_ICCV_2021_paper.pdf) [[Code]](https://github.com/raywzy/ICT) [[Project]](http://raywzy.com/ICT/)
  - **IJCAI**
    - Context-Aware Image Inpainting with Learned Semantic Priors [[Paper]](https://www.ijcai.org/proceedings/2021/0183.pdf) [[Code]](https://github.com/WendongZh/SPL)
  - **ACM MM**
    - ***BAT-Fill:*** Diverse Image Inpainting with Bidirectional and Autoregressive Transformers [[Paper]](https://dl.acm.org/doi/10.1145/3474085.3475436) [[Code]](https://github.com/yingchen001/BAT-Fill)
    - ***JPGNet:*** Joint Predictive Filtering and Generative Network for Image Inpainting [[Paper]](https://dl.acm.org/doi/10.1145/3474085.3475170) [[Code]](https://github.com/tsingqguo/jpgnet)
    - Learning Contextual Transformer Network for Image Inpainting [[Paper]](https://dl.acm.org/doi/abs/10.1145/3474085.3475426)
    - ***GCM-Net:*** Towards Effective Global Context Modeling for Image Inpainting [[Paper]](https://dl.acm.org/doi/10.1145/3474085.3475433) [[Code]](https://github.com/Ian0926/GCM-Net)
    - An Adaptive Iterative Inpainting Method with More Information Exploration [[Paper]](https://dl.acm.org/doi/10.1145/3474085.3475475)
    - Large Scale Image Completion via Co-Modulated Generative Adversarial Networks [[Paper]](Large Scale Image Completion via Co-Modulated Generative Adversarial Networks) [[Code]](https://github.com/zsyzzsoft/co-mod-gan)
  - **WACV**
    - ***R-MNet:*** A Perceptual Adversarial Network for Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/WACV2021/papers/Jam_R-MNet_A_Perceptual_Adversarial_Network_for_Image_Inpainting_WACV_2021_paper.pdf) [[Code]](https://github.com/Jireh-Jam/R-MNet-Inpainting-keras)
    - Multi-Level Generative Chaotic Recurrent Network for Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/WACV2021/papers/Chen_Multi-Level_Generative_Chaotic_Recurrent_Network_for_Image_Inpainting_WACV_2021_paper.pdf) 
    - Hyperrealistic Image Inpainting with Hypergraphs [[Paper]](https://openaccess.thecvf.com/content/WACV2021/papers/Wadhwa_Hyperrealistic_Image_Inpainting_With_Hypergraphs_WACV_2021_paper.pdf) [[Code]](https://github.com/GouravWadhwa/Hypergraphs-Image-Inpainting)
  - **TIP**
    - Dynamic Selection Network for Image Inpainting [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9318551) [[Code]](https://github.com/wangning-001/DSNet)
    - Thanka Mural Inpainting Based on Multi-Scale Adaptive Partial Convolution and Stroke-Like Mask [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9376641)
    - Image Inpainting by End-to-End Cascaded Refinement With Mask Awareness [[Paper]](https://ieeexplore.ieee.org/document/9423556) [[Code]](https://github.com/MADF-inpainting/Pytorch-MADF)
    - Texture Memory-Augmented Deep Patch-Based Image Inpainting [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9597484)
  - **TCSVT**
    - Reference-Guided Landmark Image Inpainting With Deep Feature Matching [[Paper]](https://ieeexplore.ieee.org/document/9840396) [[Project]](http://home.ustc.edu.cn/~jclee/publication/2022-07-26-TCSVT-RefMatch.html)
    - Generative Memory-Guided Semantic Reasoning Model for Image Inpainting [[Paper]](https://arxiv.org/pdf/2110.00261.pdf)

 [<u><small><🎯Back to Top></small></u>](#contents)

- <span id="vanilla-year-2020">**Year 2020**</span>
  - **CVPR**
    - ***UCTGAN:*** Diverse Image Inpainting Based on Unsupervised Cross-Space Translation [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhao_UCTGAN_Diverse_Image_Inpainting_Based_on_Unsupervised_Cross-Space_Translation_CVPR_2020_paper.pdf)
    - Contextual Residual Aggregation for Ultra High-Resolution Image Inpainting [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yi_Contextual_Residual_Aggregation_for_Ultra_High-Resolution_Image_Inpainting_CVPR_2020_paper.pdf) [[Code]](https://github.com/Atlas200dk/sample-imageinpainting-HiFill)
    - ***RFR-Net:*** Recurrent Feature Reasoning for Image Inpainting [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Recurrent_Feature_Reasoning_for_Image_Inpainting_CVPR_2020_paper.pdf) [[Code]](https://github.com/jingyuanli001/RFR-Inpainting)
    - Prior Guided GAN Based Semantic Inpainting [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Lahiri_Prior_Guided_GAN_Based_Semantic_Inpainting_CVPR_2020_paper.pdf)
    - Semantic Image Manipulation Using Scene Graph [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Dhamo_Semantic_Image_Manipulation_Using_Scene_Graphs_CVPR_2020_paper.pdf) [[Code]](https://github.com/he-dhamo/simsg)
  - **ECCV**
    - ***MEDFE:*** Rethinking Image Inpainting via a Mutual Encoder-Decoder with Feature Equalizations [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470715.pdf) [[Code]](https://github.com/KumapowerLIU/Rethinking-Inpainting-MEDFE)
    - High-Resolution Image Inpainting with Iterative Confidence Feedback and Guided Upsampling [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123640001.pdf)
    - ***Guidance and Evaluation:*** Semantic-Aware Image Inpainting for Mixed Scenes [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123720681.pdf)
    - ***Deep Generative Prior:*** Exploiting Deep Generative Prior for Versatile Image Restoration and Manipulation [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470256.pdf) [[Code]](https://github.com/XingangPan/deep-generative-prior) [[Video]](https://www.youtube.com/watch?v=p7ToqtwfVko&feature=youtu.be)
  - **AAAI**
    - Learning to Incorporate Structure Knowledge for Image Inpainting [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6951/6805) [[Code]](https://github.com/YoungGod/sturcture-inpainting)
    - Region Normalization for Image Inpainting [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6967/6821) [[Code]](https://github.com/geekyutao/RN)
    - The Missing Data Encoder: Cross-Channel Image Completion with Hide-and-Seek Adversarial Network [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6696/6550) [[Code]](https://gitlab.com/adapo/themissingdataencoder/-/tree/master)
  - **ACM MM**
    - Image Inpainting Based on Multi-frequency Probabilistic Inference Model [[Paper]](https://dl.acm.org/doi/10.1145/3394171.3413891)

 [<u><small><🎯Back to Top></small></u>](#contents)

- <span id="vanilla-year-2019">**Year 2019**</span>
  - **CVPR**
    - Learning Pyramid-Context Encoder Network for High-Quality Image Inpainting [[Paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zeng_Learning_Pyramid-Context_Encoder_Network_for_High-Quality_Image_Inpainting_CVPR_2019_paper.pdf) [[Code]](https://github.com/researchmm/PEN-Net-for-Inpainting)
    - Foreground-Aware Image Inpainting [[Paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Xiong_Foreground-Aware_Image_Inpainting_CVPR_2019_paper.pdf)
    - ***PEPSI:*** Fast Image Inpainting With Parallel Decoding Network [[Paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Sagong_PEPSI__Fast_Image_Inpainting_With_Parallel_Decoding_Network_CVPR_2019_paper.pdf) [[Code]](https://github.com/Forty-lock/PEPSI-Fast_image_inpainting_with_parallel_decoding_network)
    - Pluralistic Image Completion [[Paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zheng_Pluralistic_Image_Completion_CVPR_2019_paper.pdf) [[Code]](https://github.com/lyndonzheng/Pluralistic-Inpainting)
  - **ICCV**
    - ***StructureFlow:*** Image Inpainting via Structure-Aware Appearance Flow [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Ren_StructureFlow_Image_Inpainting_via_Structure-Aware_Appearance_Flow_ICCV_2019_paper.pdf) [[Code]](https://github.com/RenYurui/StructureFlow)
    - Coherent Semantic Attention for Image Inpainting [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Liu_Coherent_Semantic_Attention_for_Image_Inpainting_ICCV_2019_paper.pdf) [[Code]](https://github.com/KumapowerLIU/CSA-inpainting)
    - ***LBAM:*** Image Inpainting With Learnable Bidirectional Attention Maps [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Xie_Image_Inpainting_With_Learnable_Bidirectional_Attention_Maps_ICCV_2019_paper.pdf) [[Code]](https://github.com/Vious/LBAM_inpainting)
  - **ICCVW**
    - ***Deep Hyperspectral Prior:*** Single-Image Denoising, Inpainting, Super-Resolution. [[Paper]](https://openaccess.thecvf.com/content_ICCVW_2019/papers/LCI/Sidorov_Deep_Hyperspectral_Prior_Single-Image_Denoising_Inpainting_Super-Resolution_ICCVW_2019_paper.pdf) [[Code]](https://github.com/acecreamu/deep-hs-prior)
  - **IJCAI**
    - Generative Image Inpainting with Submanifold Alignment [[Paper]](https://www.ruizhang.info/publications/IJCAI2019%20Generative%20Image%20Inpainting%20with%20Submanifold%20Alignment.pdf)
    - Coarse-to-Fine Image Inpainting via Region-wise Convolutions and Non-Local Correlation [[Paper]](https://www.ijcai.org/proceedings/2019/0433.pdf)
    - ***MUSICAL:*** Multi-Scale Image Contextual Attention Learning for Inpainting [[Paper]](https://www.ijcai.org/proceedings/2019/0520.pdf) [[Code]](https://github.com/wangning-001/MUSICAL)
    - Single-shot Semantic Image Inpainting with Densely Connected Generative Networks [[Paper]](https://dl.acm.org/doi/abs/10.1145/3343031.3350903)
    - ***GAIN:*** Gradient Augmented Inpainting Network for Irregular Holes [[Paper]](https://dl.acm.org/doi/abs/10.1145/3343031.3350912)
    - Progressive Image Inpainting with Full-Resolution Residual Network [[Paper]](https://arxiv.org/pdf/1907.10478.pdf) [[Code]](https://github.com/AnatoliiPotapov/inpainting_FRRN)
    - Deep Fusion Network for Image Completion [[Paper]](https://arxiv.org/pdf/1904.08060.pdf) [[Code]](https://github.com/hughplay/DFNet)

 [<u><small><🎯Back to Top></small></u>](#contents)

- <span id="vanilla-year-2018">**Year 2018**</span> 
  - **CVPR**
    - ***DeepFill-v1:*** Generative Image Inpainting With Contextual Attention [[Paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Yu_Generative_Image_Inpainting_CVPR_2018_paper.pdf) [[Code]](https://github.com/JiahuiYu/generative_inpainting) [[Video]](https://www.youtube.com/watch?v=xz1ZvcdhgQ0&feature=youtu.be)
    - Disentangling Structure and Aesthetics for Style-Aware Image Completion [[Paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Gilbert_Disentangling_Structure_and_CVPR_2018_paper.pdf)
  - **ECCV**
    - Contextual-based Image Inpainting: Infer, Match, and Translate [[Paper]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Yuhang_Song_Contextual_Based_Image_ECCV_2018_paper.pdf)
    - ***Shift-Net:*** Image Inpainting via Deep Feature Rearrangement [[Paper]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Zhaoyi_Yan_Shift-Net_Image_Inpainting_ECCV_2018_paper.pdf) [[Code]](https://github.com/Zhaoyi-Yan/Shift-Net) 
    - Image Inpainting for Irregular Holes Using Partial Convolutions [[Paper]](https://openaccess.thecvf.com/content_ECCV_2018/papers/Guilin_Liu_Image_Inpainting_for_ECCV_2018_paper.pdf) [[Code]](https://github.com/NVIDIA/partialconv) [[Video]](https://www.youtube.com/watch?v=gg0F5JjKmhA) [[Demo]](https://www.nvidia.com/en-us/research/ai-playground/)
  - **ACM MM**
    - Semantic Image Inpainting with Progressive Generative Networks [[Paper]](https://dl.acm.org/doi/10.1145/3240508.3240625) [[Code]](https://github.com/crashmoon/Progressive-Generative-Networks)
  - **NeurIPS**
    - Image Inpainting via Generative Multi-column Convolutional Neural Networks [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2018/file/6f3ef77ac0e3619e98159e9b6febf557-Paper.pdf) [[Code]](https://github.com/shepnerd/inpainting_gmcnn)
  - Photo Realistic Image Completion via Dense Correspondence [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8410011)
- <span id="vanilla-year-2017">**Year 2017**</span>
  - **CVPR**
    - High-Resolution Image Inpainting Using Multi-scale Neural Patch Synthesis [[Paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Yang_High-Resolution_Image_Inpainting_CVPR_2017_paper.pdf) [[Code]](https://github.com/leehomyc/Faster-High-Res-Neural-Inpainting)
    - Semantic Image Inpainting with Deep Generative Models [[Paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Yeh_Semantic_Image_Inpainting_CVPR_2017_paper.pdf) [[Code]](https://github.com/moodoki/semantic_image_inpainting)
    - Structural inpainting [[Paper]](https://arxiv.org/pdf/1803.10348.pdf)

 [<u><small><🎯Back to Top></small></u>](#contents)

- <span id="vanilla-year-2016">**Year 2016**</span>
  - **CVPR**
    - ***Context Encoders:*** Feature Learning by Inpainting [[Paper]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Pathak_Context_Encoders_Feature_CVPR_2016_paper.pdf) [[Code]](https://github.com/BoyuanJiang/context_encoder_pytorch)

 [<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
## Blind Image Inpainting
- <span id="blind-year-2023">**Year 2023**</span> 
  - **CVPRW**
    - Blind Image Inpainting via Omni-dimensional Gated Attention and Wavelet Queries [[Paper]](https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/papers/Phutke_Blind_Image_Inpainting_via_Omni-Dimensional_Gated_Attention_and_Wavelet_Queries_CVPRW_2023_paper.pdf) [[Code]](https://github.com/shrutiphutke/Blind_Omni_Wav_Net)
  - **TMM**
    - ***FT-TDR:*** Frequency-Guided Transformer and Top-Down Refinement Network for Blind Face Inpainting [[Paper]](https://arxiv.org/pdf/2108.04424.pdf)
  - **TPAMI**
    - Self-Prior Guided Pixel Adversarial Networks for Blind Image Inpainting [[Paper]](https://ieeexplore.ieee.org/document/10147235)
- <span id="blind-year-2022">**Year 2022**</span> 
  - **ACM MM**
    - ***TransCNN-HAE:*** Transformer-CNN Hybrid AutoEncoder for Blind Image Inpainting [[Paper]](https://dl.acm.org/doi/abs/10.1145/3503161.3547848)
  - **IPTA**
    - ***ARIN:*** Adaptive Resampling and Instance Normalization for Robust Blind Inpainting of Dunhuang Cave Paintings [[Paper]](https://arxiv.org/pdf/2402.16188.pdf)
- <span id="blind-year-2020">**Year 2020**</span> 
  - **ECCV**
    - ***VCNet:*** A Robust Approach to Blind Image Inpainting [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700749.pdf) [[Reproduced Code]](https://github.com/birdortyedi/vcnet-blind-image-inpainting)
  
[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
## Edge-Based Image Inpainting
- <span id="edge-year-2023">**Year 2023**</span> 
  - **TPAMI**
    - ***ZITS++:*** Image Inpainting by Improving the Incremental Transformer on Structural Priors [[Paper]](https://ieeexplore.ieee.org/document/10136788) [[Code]](https://github.com/DQiaole/ZITS_inpainting) [[Project]](https://dqiaole.github.io/ZITS_inpainting/)
- <span id="edge-year-2022">**Year 2022**</span> 
  - **CVPR**
    - ***ZITS:*** Incremental Transformer Structure Enhanced Image Inpainting with Masking Positional Encoding [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Dong_Incremental_Transformer_Structure_Enhanced_Image_Inpainting_With_Masking_Positional_Encoding_CVPR_2022_paper.pdf) [[Code]](https://github.com/DQiaole/ZITS_inpainting) [[Project]](https://dqiaole.github.io/ZITS_inpainting/)
- <span id="edge-year-2021">**Year 2021**</span> 
  - **ICCV**
    - Learning a Sketch Tensor Space for Image Inpainting of Man-made Scenes [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Cao_Learning_a_Sketch_Tensor_Space_for_Image_Inpainting_of_Man-Made_ICCV_2021_paper.pdf)
    - ***CTSDG:*** Image Inpainting via Conditional Texture and Structure Dual Generation [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Guo_Image_Inpainting_via_Conditional_Texture_and_Structure_Dual_Generation_ICCV_2021_paper.pdf) [[Code]](https://github.com/xiefan-guo/ctsdg)
  - **TCSVT**
    - E2I: Generative Inpainting From Edge to Image [[Paper]](https://ieeexplore.ieee.org/document/9113276) [[Code]](https://github.com/powder21/E2I-inpainting)
- <span id="edge-year-2019">**Year 2019**</span> 
  - **ICCV**
    - ***DeepFill-v2:*** Free-Form Image Inpainting With Gated Convolution [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yu_Free-Form_Image_Inpainting_With_Gated_Convolution_ICCV_2019_paper.pdf) [[Code]](https://github.com/JiahuiYu/generative_inpainting) [[Project]](https://jiahuiyu.com/deepfill) [[Video]](https://www.youtube.com/watch?v=uZkEi9Y2dj4&feature=youtu.be)
    - ***PRVS:*** Progressive Reconstruction of Visual Structure for Image Inpainting [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Progressive_Reconstruction_of_Visual_Structure_for_Image_Inpainting_ICCV_2019_paper.pdf) [[Code]](https://github.com/jingyuanli001/PRVS-Image-Inpainting)
  - **ICCVW**
    - ***EdgeConnect:*** Structure Guided Image Inpainting using Edge Prediction [[Paper]](https://openaccess.thecvf.com/content_ICCVW_2019/papers/AIM/Nazeri_EdgeConnect_Structure_Guided_Image_Inpainting_using_Edge_Prediction_ICCVW_2019_paper.pdf) [[Code]](https://github.com/knazeri/edge-connect)
    
[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
## Sketch-Guided Image Inpainting
- <span id="sketch-year-2024">**Year 2024**</span> 
  - **TMM**
      - ***SketchRefiner:*** Towards Interactive Image Inpainting via Robust Sketch Refinement [[Paper]](https://ieeexplore.ieee.org/document/10533842) [[Code]](https://github.com/AlonzoLeeeooo/SketchRefiner) [[Project]](https://alonzoleeeooo.github.io/SketchRefiner/)
- <span id="sketch-year-2023">**Year 2023**</span> 
  - **ACM MM**
    - ***Draw2Edit:*** Mask-Free Sketch-Guided Image Manipulation [[Paper]](https://dl.acm.org/doi/10.1145/3581783.3612398) [[Code]](https://github.com/YiwenXu/Draw2Edit)
- <span id="sketch-year-2022">**Year 2022**</span> 
  - **CVPR**
    - ***SketchEdit:*** Mask-Free Local Image Manipulation with Partial Sketches [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zeng_SketchEdit_Mask-Free_Local_Image_Manipulation_With_Partial_Sketches_CVPR_2022_paper.pdf) [[Code]](https://github.com/zengxianyu/sketchedit) [[Project]](http://zengyu.me/sketchedit/)
- <span id="sketch-year-2021">**Year 2021**</span> 
  - **CVPR**
    - ***DeFLOCNet:*** Deep Image Editing via Flexible Low-Level Controls [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_DeFLOCNet_Deep_Image_Editing_via_Flexible_Low-Level_Controls_CVPR_2021_paper.pdf) [[Code]](https://github.com/KumapowerLIU/DeFLOCNet?tab=readme-ov-file)
- <span id="sketch-year-2020">**Year 2020**</span> 
  - **ECCV**
    - ***Deep Plastic Surgery:*** Robust and Controllable Image Editing with Human-Drawn Sketches [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123600596.pdf) [[Code]](https://github.com/VITA-Group/DeepPS) [[Project]](https://williamyang1991.github.io/projects/ECCV2020/)
- <span id="sketch-year-2019">**Year 2019**</span> 
  - **ICCV**
    - ***DeepFill-v2:*** Free-Form Image Inpainting With Gated Convolution [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yu_Free-Form_Image_Inpainting_With_Gated_Convolution_ICCV_2019_paper.pdf) [[Code]](https://github.com/JiahuiYu/generative_inpainting) [[Project]](https://jiahuiyu.com/deepfill) [[Video]](https://www.youtube.com/watch?v=uZkEi9Y2dj4&feature=youtu.be)
    - ***SC-FEGAN:*** Face Editing Generative Adversarial Network With User's Sketch and Color [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Jo_SC-FEGAN_Face_Editing_Generative_Adversarial_Network_With_Users_Sketch_and_ICCV_2019_paper.pdf) [[Code]](https://github.com/run-youngjoo/SC-FEGAN)

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
## Face Image Inpainting
- <span id="face-year-2024">**Year 2024**</span>
  - **TCSVT**
    - Learning from Text: A Multimodal Face Inpainting Network for Irregular Holes [[Paper]](https://ieeexplore.ieee.org/document/10445705)
  - **arXiv**
    - Learning Position-Aware Implicit Neural Network for Real-World Face Inpainting [[Paper]](https://arxiv.org/pdf/2401.10537.pdf)
    - ***E2F-Net:*** Eyes-to-Face Inpainting via StyleGAN Latent Space [[Paper]](https://arxiv.org/pdf/2403.12197)
- <span id="face-year-2023">**Year 2023**</span> 
  - **CVPRW**
    - ***Unmasking Your Expression:*** Expression-Conditioned GAN for Masked Face Inpainting [[Paper]](https://openaccess.thecvf.com/content/CVPR2023W/ABAW/papers/Sola_Unmasking_Your_Expression_Expression-Conditioned_GAN_for_Masked_Face_Inpainting_CVPRW_2023_paper.pdf) [[Code]](https://github.com/SridharSola/ECGAN)
  - **WACV**
    - Nested Deformable Multi-head Attention for Facial Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/WACV2023/papers/Phutke_Nested_Deformable_Multi-Head_Attention_for_Facial_Image_Inpainting_WACV_2023_paper.pdf) [[Code]](https://github.com/shrutiphutke/NDMA_Facial_Inpainting)
  - **TMM**
    - Pluralistic Face Inpainting With Transformation of Attribute Information [[Paper]](https://ieeexplore.ieee.org/document/9991050)
  - **TCSVT**
    - Reference-Guided Large-Scale Face Inpainting With Identity and Texture Control [[Paper]](https://ieeexplore.ieee.org/document/10068561)
- <span id="face-year-2022">**Year 2022**</span> 
  - **TCSVT**
    - ***SwapInpaint:*** Identity-Specific Face Inpainting With Identity Swapping [[Paper]](https://ieeexplore.ieee.org/document/9625034)
    - Simultaneous Face Completion and Frontalization via Mask Guided Two-Stage GAN [[Paper]](https://ieeexplore.ieee.org/document/9535188)
  - **arXiv**
    - Do Inpainting Yourself: Generative Facial Inpainting Guided by Exemplars [[Paper]](https://arxiv.org/pdf/2202.06358) [[Code]](https://github.com/LonglongaaaGo/EXE-GAN) [[Project]](https://longlongaaago.github.io/EXE-GAN/)
- <span id="face-year-2021">**Year 2021**</span> 
  - **ACM MM**
    - When Face Completion Meets Irregular Holes: An Attributes Guided Deep Inpainting Network [[Paper]](https://dl.acm.org/doi/10.1145/3474085.3475466)
  - **TMM**
    - Recurrent Generative Adversarial Network for Face Completion [[Paper]](https://ieeexplore.ieee.org/document/9026767)
- <span id="face-year-2020">**Year 2020**</span> 
  - **CVPR**
    - Learning Oracle Attention for High-Fidelity Face Completion [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhou_Learning_Oracle_Attention_for_High-Fidelity_Face_Completion_CVPR_2020_paper.pdf)
  - **AAAI**
    - Geometry-Aware Face Completion and Editing [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/4096/3974)
  - **IJCAI**
    - ***r-FACE:*** Reference Guided Face Component Editing [[Paper]](https://www.ijcai.org/proceedings/2020/0070.pdf) 
- <span id="face-year-2017">**Year 2017**</span> 
  - **CVPR**
    - Generative Face Completion [[Paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Generative_Face_Completion_CVPR_2017_paper.pdf) [[Code]](https://github.com/Yijunmaverick/GenerativeFaceCompletion)

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
## Fashion Image Inpainting
- <span id="fashion-year-2024">**Year 2024**</span> 
    - ***TexFit:*** Text-Driven Fashion Image Editing with Diffusion Models [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/28885)
- <span id="fashion-year-2019">**Year 2019**</span> 
  - **TIP**
    - Deep Portrait Image Completion and Extrapolation [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8866746)
  - **ICCV**
    - ***FiNet:*** Compatible and Diverse Fashion Image Inpainting [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Han_FiNet_Compatible_and_Diverse_Fashion_Image_Inpainting_ICCV_2019_paper.pdf) [[Code]](https://github.com/Skype-line/FiNet-pytorch)

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
## Conventional Methods
- <span id="conventional-year-2024">**Year 2024**</span>
  - **arXiv**
    - ***HySim:*** An Efficient Hybrid Similarity Measure for Patch Matching in Image Inpainting [[Paper]](https://arxiv.org/pdf/2403.14292.pdf)
- <span id="conventional-year-2020">**Year 2020**</span>
  - **TIP**
    - Image Inpainting Using Nonlocal Texture Matching and Nonlinear Filtering [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8531678)
    - Truncated Low-Rank and Total p Variation Constrained Color Image Completion and its Moreau Approximation Algorithm [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9141413)
- <span id="conventional-year-2019">**Year 2019**</span>
    - Multiple Pyramids Based Image Inpainting Using Local Patch Statistics and Steering Kernel Feature [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8733204)
- <span id="conventional-year-2018">**Year 2018**</span>
  - **TIP**
    - A Group-Based Image Inpainting Using Patch Refinement in MRF Framework [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8089766)
- <span id="conventional-year-2016">**Year 2016**</span>
  - **CVPR**
    - Multiview Image Completion with Space Structure Propagation [[Paper]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Baek_Multiview_Image_Completion_CVPR_2016_paper.pdf)
  - **TIP**
    - Image Inpainting Through Metric Labeling via Guided Patch Mixing [[Paper]](https://ieeexplore.ieee.org/document/7559711)
- <span id="conventional-year-2011">**Year 2011**</span> 
  - **ICIG**
    - Structure-Aware Image Completion with Texture Propagation [[Paper]](https://ieeexplore.ieee.org/document/6005583)
- <span id="conventional-year-2005">**Year 2005**</span> 
  - **TIP**
    - Edge-Based Image Restoration [[Paper]](https://ieeexplore.ieee.org/document/1510681)
  - **SIGGRAPH**
    - Image Completion with Structure Propagation [[Paper]](https://jiaya.me/file/all_final_papers/ImageCompletion_SIGGRAPH05.pdf)
- <span id="conventional-year-2004">**Year 2004**</span> 
  - **TIP**
    - Region Filling and Object Removal by Exemplar-Based Image Inpainting [[Paper]](https://www.irisa.fr/vista/Papers/2004_ip_criminisi.pdf)
- <span id="conventional-year-2000">**Year 2000**</span> 
  - **SIGGRAPH**
    - Image Inpainting [[Paper]](https://dl.acm.org/doi/pdf/10.1145/344779.344972)

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
# Survey Papers
- [IJCV 2024] Deep Learning-based Image and Video Inpainting: A Survey [[Paper]](https://arxiv.org/pdf/2401.03395.pdf)
- [Pattern Recognit. 2023] Deep Learning for Image Inpainting: A Survey [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S003132032200526X)


[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
# Datasets
- ***Paris StreetView:*** Context Encoders: Feature Learning by Inpainting [[Paper]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Pathak_Context_Encoders_Feature_CVPR_2016_paper.pdf) [[Code]](https://github.com/BoyuanJiang/context_encoder_pytorch) _(Since Google's terms of service has forbidden anyone from creating repositories of streetview data, the dataset is currently not available.)_
- ***Places***: A 10 Million Image Database for Scene Recognition [[Paper]](http://places2.csail.mit.edu/PAMI_places.pdf) [[Dataset]](http://places2.csail.mit.edu/download.html)
- ***ImageNet***: A Large-Scale Hierarchical Image Database [[Paper]](https://image-net.org/static_files/papers/imagenet_cvpr09.pdf) [[Dataset]](https://www.image-net.org/)
- ***CelebA-HQ:*** Progressive Growing of GANs for Improved Quality, Stability, and Variation [[Paper]](https://openreview.net/pdf?id=Hk99zCeAb) [[Dataset]](https://github.com/suvojit-0x55aa/celebA-HQ-dataset-download)
- ***FFHQ:*** A Style-Based Generator Architecture for Generative Adversarial Networks [[Paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Karras_A_Style-Based_Generator_Architecture_for_Generative_Adversarial_Networks_CVPR_2019_paper.pdf) [[Dataset]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Karras_A_Style-Based_Generator_Architecture_for_Generative_Adversarial_Networks_CVPR_2019_paper.pdf)

[<u><small><🎯Back to Top></small></u>](#contents)


<!-- omit in toc -->
# Q&A
- **Q: The conference sequence of this paper list?**
  - This paper list is organized according to the following sequence:
    - Conferences
      - CVPR
      - CVPRW
      - ICCV
      - ICCVW
      - ECCV
      - AAAI
      - IJCAI
      - WACV
      - NeurIPS
      - ICLR
      - ACM MM
      - SIGGRAPH
      - IPTA
    - Journals
      - TMM
      - TIP
      - TPAMI
      - TCSVT
    - arXiv

[<u><small><🎯Back to Top></small></u>](#contents)


<!-- omit in toc -->
# References

The `reference.bib` file summarizes bibtex references of up-to-date image inpainting papers, widely used datasets, and toolkits.
Based on the original references, I have made the following modifications to make their results look nice in the `LaTeX` manuscripts:
- Refereces are normally constructed in the form of `author-etal-year-nickname`. Particularly, references of datasets and toolkits are directly constructed as `nickname`, e.g., `imagenet`.
- In each reference, all names of conferences/journals are converted into abbreviations, e.g., `Computer Vision and Pattern Recognition -> CVPR`.
- The `url`, `doi`, `publisher`, `organization`, `editor`, `series` in all references are removed.
- The `pages` of all references are added if they are missing.
- All paper names are in title case. Besides, I have added an additional `{}` to make sure that the title case would also work well in some particular templates. 

If you have other demands of reference formats, you may refer to the original references of papers by searching their names in [DBLP](https://dblp.org/) or [Google Scholar](https://scholar.google.com/).

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
# Star History

<p align="center">
    <a href="https://api.star-history.com/svg?repos=AlonzoLeeeooo/awesome-image-inpainting-studies&type=Date" target="_blank">
        <img width="500" src="https://api.star-history.com/svg?repos=AlonzoLeeeooo/awesome-image-inpainting-studies&type=Date" alt="Star History Chart">
    </a>
<p>

[<u><small><🎯Back to Top></small></u>](#contents)