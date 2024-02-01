<p align="center">
  <h1 align="center">A Collection of Image Inpainting Studies</h1>

This GitHub repository summarizes papers and resources related to the image inpainting task. 

If you have any suggestions about this repository, please feel free to [start a new issue](https://github.com/AlonzoLeeeooo/awesome-image-inpainting-studies/issues/new) or [pull requests](https://github.com/AlonzoLeeeooo/awesome-image-inpainting-studies/pulls).


<!-- omit in toc -->
# Contents
- [References](#references)
- [Papers](#papers) _(Mainly Deep Learning-Based)_
  - [🔥Text-Guided Image Inpainting](#text-guided-image-inpainting)
    - [Year 2023](#text-year-2023)
    - [Year 2022](#text-year-2022)
  - [Vanilla Image Inpainting](#vanilla-image-inpainting)
    - [Year 2022](#vanilla-year-2022)
    - [Year 2021](#vanilla-year-2021)
    - [Year 2020](#vanilla-year-2020)
    - [Year 2019](#vanilla-year-2019)
    - [Year 2018](#vanilla-year-2018)
    - [Year 2017](#vanilla-year-2017)
    - [Year 2016](#vanilla-year-2016)
  - [Edge-Based Image Inpainting](#edge-based-image-inpainting)
    - [Year 2022](#edge-year-2022)
    - [Year 2021](#edge-year-2021)
    - [Year 2019](#edge-year-2019)
  - [Sketch-Guided Image Inpainting](#sketch-guided-image-inpainting)
    - [Year 2022](#sketch-year-2022)
    - [Year 2021](#sketch-year-2021)
    - [Year 2019](#sketch-year-2019)
  - [Face Image Inpainting](#face-image-inpainting)
    - [Year 2020](#face-year-2020)
    - [Year 2017](#face-year-2017)
  - [Fashion Image Inpainting](#fashion-image-inpainting)
    - [Year 2019](#fashion-year-2019)
  - [Conventional Methods](#conventional-methods) _(Non Deep Learning-Based)_
      - [Year 2016](#conventional-year-2016)
      - [Year 2011](#conventional-year-2011)
      - [Year 2005](#conventional-year-2005)
      - [Year 2004](#conventional-year-2004)
      - [Year 2000](#conventional-year-2000)
- [Datasets](#datasets)

<!-- omit in toc -->
# References

The `reference.bib` file summarizes bibtex references of up-to-date image inpainting papers, widely used datasets, and toolkits.
Based on the original references, I have made the following modifications to make their results look nice in the `LaTeX` manuscripts:
- Refereces are normally constructed in the form of `author-etal-year-nickname`. Particularly, references of datasets and toolkits are directly constructed as `nickname` (e.g., `imagenet`).
- In each reference, all names of conferences/journals are converted into abbreviations, e.g., `{IEEE/CVF} Conference on Computer Vision and Pattern Recognition -> CVPR`.
- The `url`, `doi`, `publisher`, `organization` in all references are removed.
- The `pages` of all references are added if they are missing.
- All paper names are in title case. Besides, I have added an additional `{}` to make sure that the title case would also work well in some particular templates. 

If you have other demands of reference formats, you may refer to the original references of papers by searching their names in [Google Scholar](https://scholar.google.com/).



<!-- omit in toc -->
# Papers

<!-- omit in toc -->
## 🔥 Text-Guided Image Inpainting
- <span id="text-year-2023">**Year 2023**</span>
  - **CVPR**
    - ***NÜWA-LIP:*** Language-guided Image Inpainting with Defect-free VQGAN [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Ni_NUWA-LIP_Language-Guided_Image_Inpainting_With_Defect-Free_VQGAN_CVPR_2023_paper.pdf) [[Code]](https://github.com/kodenii/NUWA-LIP)
    - ***Imagen Editor and EditBench:*** Advancing and Evaluating Text-Guided Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Imagen_Editor_and_EditBench_Advancing_and_Evaluating_Text-Guided_Image_Inpainting_CVPR_2023_paper.pdf)
    - ***SmartBrush:*** Text and Shape Guided Object Inpainting with Diffusion Model [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Xie_SmartBrush_Text_and_Shape_Guided_Object_Inpainting_With_Diffusion_Model_CVPR_2023_paper.pdf)
    - ***Paint by Example:*** Exemplar-based Image Editing with Diffusion Models [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Yang_Paint_by_Example_Exemplar-Based_Image_Editing_With_Diffusion_Models_CVPR_2023_paper.pdf) [[Code]](https://github.com/Fantasy-Studio/Paint-by-Example) [[Demo]](https://huggingface.co/spaces/Fantasy-Studio/Paint-by-Example)
  - **SIGGRAPH**
    - Blended Latent Diffusion [[Paper]](https://omriavrahami.com/blended-latent-diffusion-page/static/paper/Blended_Latent_Diffusion_Paper.pdf) [[Code]](https://github.com/omriav/blended-diffusion?tab=readme-ov-file) [[Project]](https://omriavrahami.com/blended-latent-diffusion-page/)
- <span id="text-year-2022">**Year 2022**</span>
  - **CVPR**
    - Blended Diffusion for Text-driven Editing of Natural Images [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Avrahami_Blended_Diffusion_for_Text-Driven_Editing_of_Natural_Images_CVPR_2022_paper.pdf) [[Code]](https://github.com/omriav/blended-diffusion)

<!-- omit in toc -->
## Vanilla Image Inpainting
- <span id="vanilla-year-2022">**Year 2022**</span>
  - **CVPR**
    - ***MISF:*** Multi-level Interactive Siamese Filtering for High-Fidelity Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_MISF_Multi-Level_Interactive_Siamese_Filtering_for_High-Fidelity_Image_Inpainting_CVPR_2022_paper.pdf) [[Code]](https://github.com/tsingqguo/misf)
    - ***MAT:*** Mask-Aware Transformer for Large Hole Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_MAT_Mask-Aware_Transformer_for_Large_Hole_Image_Inpainting_CVPR_2022_paper.pdf) [[Code]](https://github.com/fenglinglwb/MAT)
    - Reduce Information Loss in Transformers for Pluralistic Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Reduce_Information_Loss_in_Transformers_for_Pluralistic_Image_Inpainting_CVPR_2022_paper.pdf) [[Code]](https://github.com/liuqk3/PUT)
    - Dual-path Image Inpainting with Auxiliary GAN Inversion [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Dual-Path_Image_Inpainting_With_Auxiliary_GAN_Inversion_CVPR_2022_paper.pdf)
    - ***RePaint:*** Inpainting using Denoising Diffusion Probabilistic Models [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Lugmayr_RePaint_Inpainting_Using_Denoising_Diffusion_Probabilistic_Models_CVPR_2022_paper.pdf) [[Code]](https://github.com/andreas128/RePaint)
    - ***TFill:*** Bridging Global Context Interactions for High-Fidelity Image Completion [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zheng_Bridging_Global_Context_Interactions_for_High-Fidelity_Image_Completion_CVPR_2022_paper.pdf) [[Code]](https://github.com/lyndonzheng/TFill) [[Project]](https://chuanxiaz.com/tfill/) [[Video]](https://www.youtube.com/embed/efB1fw0jiLs)
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
    - ***CTSDG:*** Image Inpainting via Conditional Texture and Structure Dual Generation [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Guo_Image_Inpainting_via_Conditional_Texture_and_Structure_Dual_Generation_ICCV_2021_paper.pdf) [[Code]](https://github.com/xiefan-guo/ctsdg)
    - ***CR-Fill:*** Generative Image Inpainting with Auxiliary Contextual Reconstruction [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Zeng_CR-Fill_Generative_Image_Inpainting_With_Auxiliary_Contextual_Reconstruction_ICCV_2021_paper.pdf) [[Code]](https://github.com/zengxianyu/crfill)
    - Parallel Multi-Resolution Fusion Network for Image Inpainting [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Parallel_Multi-Resolution_Fusion_Network_for_Image_Inpainting_ICCV_2021_paper.pdf)
    - ***ICT:*** High-Fidelity Pluralistic Image Completion with Transformers [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wan_High-Fidelity_Pluralistic_Image_Completion_With_Transformers_ICCV_2021_paper.pdf) [[Code]](https://github.com/raywzy/ICT) [[Project]](http://raywzy.com/ICT/)
- <span id="vanilla-year-2020">**Year 2020**</span>
  - **CVPR**
    - ***UCTGAN:*** Diverse Image Inpainting Based on Unsupervised Cross-Space Translation [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhao_UCTGAN_Diverse_Image_Inpainting_Based_on_Unsupervised_Cross-Space_Translation_CVPR_2020_paper.pdf)
    - Contextual Residual Aggregation for Ultra High-Resolution Image Inpainting [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yi_Contextual_Residual_Aggregation_for_Ultra_High-Resolution_Image_Inpainting_CVPR_2020_paper.pdf) [[Code]](https://github.com/Atlas200dk/sample-imageinpainting-HiFill)
    - ***RFR-Net:*** Recurrent Feature Reasoning for Image Inpainting [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Recurrent_Feature_Reasoning_for_Image_Inpainting_CVPR_2020_paper.pdf) [[Code]](https://github.com/jingyuanli001/RFR-Inpainting)
    - Prior Guided GAN Based Semantic Inpainting [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Lahiri_Prior_Guided_GAN_Based_Semantic_Inpainting_CVPR_2020_paper.pdf)
    - Semantic Image Manipulation Using Scene Graph [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Dhamo_Semantic_Image_Manipulation_Using_Scene_Graphs_CVPR_2020_paper.pdf) [[Code]](https://github.com/he-dhamo/simsg)
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
- <span id="vanilla-year-2018">**Year 2018**</span>
  - **CVPR**
    - ***DeepFill-v1:*** Generative Image Inpainting With Contextual Attention [[Paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Yu_Generative_Image_Inpainting_CVPR_2018_paper.pdf) [[Code]](https://github.com/JiahuiYu/generative_inpainting) [[Video]](https://www.youtube.com/watch?v=xz1ZvcdhgQ0&feature=youtu.be)
    - Disentangling Structure and Aesthetics for Style-Aware Image Completion [[Paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Gilbert_Disentangling_Structure_and_CVPR_2018_paper.pdf)
- <span id="vanilla-year-2017">**Year 2017**</span>
  - **CVPR**
    - High-Resolution Image Inpainting Using Multi-scale Neural Patch Synthesis [[Paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Yang_High-Resolution_Image_Inpainting_CVPR_2017_paper.pdf) [[Code]](https://github.com/leehomyc/Faster-High-Res-Neural-Inpainting)
    - Semantic Image Inpainting with Deep Generative Models [[Paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Yeh_Semantic_Image_Inpainting_CVPR_2017_paper.pdf) [[Code]](https://github.com/moodoki/semantic_image_inpainting)
- <span id="vanilla-year-2016">**Year 2016**</span>
  - **CVPR**
    - ***Context Encoders:*** Feature Learning by Inpainting [[Paper]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Pathak_Context_Encoders_Feature_CVPR_2016_paper.pdf) [[Code]](https://github.com/BoyuanJiang/context_encoder_pytorch)

<!-- omit in toc -->
## Edge-Based Image Inpainting
- <span id="edge-year-2022">**Year 2022**</span>
  - **CVPR**
    - ***ZITS:*** Incremental Transformer Structure Enhanced Image Inpainting with Masking Positional Encoding [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Dong_Incremental_Transformer_Structure_Enhanced_Image_Inpainting_With_Masking_Positional_Encoding_CVPR_2022_paper.pdf) [[Code]](https://github.com/DQiaole/ZITS_inpainting) [[Project]](https://dqiaole.github.io/ZITS_inpainting/)
- <span id="edge-year-2021">**Year 2021**</span>
  - **ICCV**
    - Learning a Sketch Tensor Space for Image Inpainting of Man-made Scenes [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Cao_Learning_a_Sketch_Tensor_Space_for_Image_Inpainting_of_Man-Made_ICCV_2021_paper.pdf)
- <span id="edge-year-2019">**Year 2019**</span>
  - **ICCV**
    - ***DeepFill-v2:*** Free-Form Image Inpainting With Gated Convolution [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yu_Free-Form_Image_Inpainting_With_Gated_Convolution_ICCV_2019_paper.pdf) [[Code]](https://github.com/JiahuiYu/generative_inpainting) [[Project]](https://jiahuiyu.com/deepfill) [[Video]](https://www.youtube.com/watch?v=uZkEi9Y2dj4&feature=youtu.be)
    - ***PRVS:*** Progressive Reconstruction of Visual Structure for Image Inpainting [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Progressive_Reconstruction_of_Visual_Structure_for_Image_Inpainting_ICCV_2019_paper.pdf) [[Code]](https://github.com/jingyuanli001/PRVS-Image-Inpainting)

<!-- omit in toc -->
## Sketch-Guided Image Inpainting
- <span id="sketch-year-2022">**Year 2022**</span>
  - **CVPR**
    - ***SketchEdit:*** Mask-Free Local Image Manipulation with Partial Sketches [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zeng_SketchEdit_Mask-Free_Local_Image_Manipulation_With_Partial_Sketches_CVPR_2022_paper.pdf) [[Code]](https://github.com/zengxianyu/sketchedit) [[Project]](http://zengyu.me/sketchedit/)
- <span id="sketch-year-2021">**Year 2021**</span>
  - **CVPR**
    - ***DeFLOCNet:*** Deep Image Editing via Flexible Low-Level Controls [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_DeFLOCNet_Deep_Image_Editing_via_Flexible_Low-Level_Controls_CVPR_2021_paper.pdf) [[Code]](https://github.com/KumapowerLIU/DeFLOCNet?tab=readme-ov-file)
- <span id="sketch-year-2019">**Year 2019**</span>
  - **ICCV**
    - ***DeepFill-v2:*** Free-Form Image Inpainting With Gated Convolution [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yu_Free-Form_Image_Inpainting_With_Gated_Convolution_ICCV_2019_paper.pdf) [[Code]](https://github.com/JiahuiYu/generative_inpainting) [[Project]](https://jiahuiyu.com/deepfill) [[Video]](https://www.youtube.com/watch?v=uZkEi9Y2dj4&feature=youtu.be)
    - ***SC-FEGAN:*** Face Editing Generative Adversarial Network With User's Sketch and Color [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Jo_SC-FEGAN_Face_Editing_Generative_Adversarial_Network_With_Users_Sketch_and_ICCV_2019_paper.pdf) [[Code]](https://github.com/run-youngjoo/SC-FEGAN)

<!-- omit in toc -->
## Face Image Inpainting
- <span id="face-year-2020">**Year 2020**</span>
  - **CVPR**
    - Learning Oracle Attention for High-Fidelity Face Completion [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhou_Learning_Oracle_Attention_for_High-Fidelity_Face_Completion_CVPR_2020_paper.pdf)
- <span id="face-year-2017">**Year 2017**</span>
  - **CVPR**
    - Generative Face Completion [[Paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Generative_Face_Completion_CVPR_2017_paper.pdf) [[Code]](https://github.com/Yijunmaverick/GenerativeFaceCompletion)

<!-- omit in toc -->
## Fashion Image Inpainting
- <span id="fashion-year-2019">**Year 2019**</span>
  - **ICCV**
    - ***FiNet:*** Compatible and Diverse Fashion Image Inpainting [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Han_FiNet_Compatible_and_Diverse_Fashion_Image_Inpainting_ICCV_2019_paper.pdf) [[Code]](https://github.com/Skype-line/FiNet-pytorch)

<!-- omit in toc -->
## Conventional Methods
- <span id="conventional-year-2016">**Year 2016**</span>
  - **CVPR**
    - Multiview Image Completion with Space Structure Propagation [[Paper]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Baek_Multiview_Image_Completion_CVPR_2016_paper.pdf)
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

<!-- omit in toc -->
# Datasets
- ***Paris StreetView:*** Context Encoders: Feature Learning by Inpainting [[Paper]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Pathak_Context_Encoders_Feature_CVPR_2016_paper.pdf) [[Code]](https://github.com/BoyuanJiang/context_encoder_pytorch) _(Since Google's terms of service has forbidden anyone from creating repositories of streetview data, the dataset is currently not available.)_
- ***Places***: A 10 Million Image Database for Scene Recognition [[Paper]](http://places2.csail.mit.edu/PAMI_places.pdf) [[Dataset]](http://places2.csail.mit.edu/download.html)
- ***ImageNet***: A Large-Scale Hierarchical Image Database [[Paper]](https://image-net.org/static_files/papers/imagenet_cvpr09.pdf) [[Dataset]](https://www.image-net.org/)
- ***CelebA-HQ:*** Progressive Growing of GANs for Improved Quality, Stability, and Variation [[Paper]](https://openreview.net/pdf?id=Hk99zCeAb) [[Dataset]](https://github.com/suvojit-0x55aa/celebA-HQ-dataset-download)
- ***FFHQ:*** A Style-Based Generator Architecture for Generative Adversarial Networks [[Paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Karras_A_Style-Based_Generator_Architecture_for_Generative_Adversarial_Networks_CVPR_2019_paper.pdf) [[Dataset]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Karras_A_Style-Based_Generator_Architecture_for_Generative_Adversarial_Networks_CVPR_2019_paper.pdf)


<!-- omit in toc -->
# To-Do Lists
- Published Papers on Conferences
  - [x] Update CVPR papers
  - [ ] Update CVPRW papers
  - [x] Update ICCV papers
  - [ ] Update ICCVW papers
  - [ ] Update ECCV papers
  - [ ] Update ECCVW papers
  - [ ] Update AAAI papers
  - [ ] Update IJCAI papers
  - [ ] Update ACM MM papers
  - [ ] Update WACV papers
  - [ ] Update ACCV papers
  - [ ] Update NeurIPS papers
  - [ ] Update ICLR papers
  - [ ] Update SIGGRAPH papers
- Published Papers on Journals
  - [ ] Update TMM papers
  - [ ] Update TIP papers
  - [ ] Update TCSVT papers
  - [ ] Update TPAMI papers
- Regular Maintenance of Preprint arXiv Papers and Missed Papers