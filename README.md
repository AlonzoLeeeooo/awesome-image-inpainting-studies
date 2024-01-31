<p align="center">
  <h1 align="center">A Collection of Image Inpainting Studies</h1>

This GitHub repository summarizes papers and resources related to the image inpainting task. 

If you have any suggestions about this repository, please feel free to [start a new issue](https://github.com/AlonzoLeeeooo/awesome-image-inpainting-studies/issues/new) or [pull requests](https://github.com/AlonzoLeeeooo/awesome-image-inpainting-studies/pulls).

<!-- omit in toc -->
# Contents
- [References](#references)
- [Deep Learning-Based Methods](#deep-learning-based-methods)
  - [Vanilla Image Inpainting](#vanilla-image-inpainting)
    - [Year 2018](#vanilla-year-2018)
    - [Year 2017](#vanilla-year-2017)
    - [Year 2016](#vanilla-year-2016)
  - [Face Completion](#face-completion)
    - [Year 2017](#face-year-2017)
- [Conventional Methods](#conventional-methods)
    - [Year 2016](#conventional-year-2016)
    - [Year 2011](#conventional-year-2011)
    - [Year 2005](#conventional-year-2005)
    - [Year 2004](#conventional-year-2004)
    - [Year 2000](#conventional-year-2000)
- [Datasets](#datasets)

<!-- omit in toc -->
# References

In `reference.bib`, bibtex references of up-to-date image inpainting papers, widely used datasets, and toolkits are summarized.
Based on the original references, I have made the following modifications to make their results look nice in the `LaTeX` manuscripts:
- Refereces are normally constructed in the form of `author-etal-year-nickname`. Particularly, references of datasets and toolkits are directly constructed as `nickname` (e.g., `imagenet`).
- In each reference, all names of conferences/journals are converted into abbreviations, e.g., `{IEEE/CVF} Conference on Computer Vision and Pattern Recognition -> CVPR`.
- The `url`, `doi`, `publisher`, `organization` in all references are removed.
- The `pages` of all references are added if they are missing.
- All paper names are in title case. Besides, I have added an additional `{}` to make sure that the title case would also work well in some particular templates. 

If you have other demands of reference formats, you may refer to the original references of papers by searching their names in [Google Scholar](https://scholar.google.com/).



<!-- omit in toc -->
# Deep Learning-Based Methods

<!-- omit in toc -->
## Vanilla Image Inpainting
- <span id="vanilla-year-2018">**Year 2018**</span>
  - CVPR
    - ***DeepFill-v1:*** Generative Image Inpainting With Contextual Attention [[Paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Yu_Generative_Image_Inpainting_CVPR_2018_paper.pdf) [[Code]](https://github.com/JiahuiYu/generative_inpainting)
    - Disentangling Structure and Aesthetics for Style-Aware Image Completion [[Paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Gilbert_Disentangling_Structure_and_CVPR_2018_paper.pdf)
- <span id="vanilla-year-2017">**Year 2017**</span>
  - CVPR
    - High-Resolution Image Inpainting Using Multi-scale Neural Patch Synthesis [[Paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Yang_High-Resolution_Image_Inpainting_CVPR_2017_paper.pdf) [[Code]](https://github.com/leehomyc/Faster-High-Res-Neural-Inpainting)
    - Semantic Image Inpainting with Deep Generative Models [[Paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Yeh_Semantic_Image_Inpainting_CVPR_2017_paper.pdf) [[Code]](https://github.com/moodoki/semantic_image_inpainting)
- <span id="vanilla-year-2016">**Year 2016**</span>
  - CVPR
    - Context Encoders: Feature Learning by Inpainting [[Paper]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Pathak_Context_Encoders_Feature_CVPR_2016_paper.pdf) [[Code]](https://github.com/BoyuanJiang/context_encoder_pytorch)

<!-- omit in toc -->
## Face Completion
- <span id="face-year-2017">**Year 2017**</span>
  - CVPR
    - Generative Face Completion [[Paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Generative_Face_Completion_CVPR_2017_paper.pdf) [[Code]](https://github.com/Yijunmaverick/GenerativeFaceCompletion)

<!-- omit in toc -->
# Conventional Methods
- <span id="conventional-year-2016">**Year 2016**</span>
  - CVPR
    - Multiview Image Completion with Space Structure Propagation [[Paper]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Baek_Multiview_Image_Completion_CVPR_2016_paper.pdf)
- <span id="conventional-year-2011">**Year 2011**</span>
  - ICIG
    - Structure-Aware Image Completion with Texture Propagation [[Paper]](https://ieeexplore.ieee.org/document/6005583)
- <span id="conventional-year-2005">**Year 2005**</span>
  - TIP
    - Edge-Based Image Restoration [[Paper]](https://ieeexplore.ieee.org/document/1510681)
  - SIGGRAPH
    - Image Completion with Structure Propagation [[Paper]](https://jiaya.me/file/all_final_papers/ImageCompletion_SIGGRAPH05.pdf)
- <span id="conventional-year-2004">**Year 2004**</span>
  - TIP
    - Region Filling and Object Removal by Exemplar-Based Image Inpainting [[Paper]](https://www.irisa.fr/vista/Papers/2004_ip_criminisi.pdf)
- <span id="conventional-year-2000">**Year 2000**</span>
  - SIGGRAPH
    - Image Inpainting [[Paper]](https://dl.acm.org/doi/pdf/10.1145/344779.344972)

<!-- omit in toc -->
# Datasets
- ***Places***: A 10 Million Image Database for Scene Recognition [[Paper]](http://places2.csail.mit.edu/PAMI_places.pdf) [[Dataset]](http://places2.csail.mit.edu/download.html)
- ***ImageNet***: A Large-Scale Hierarchical Image Database [[Paper]](https://image-net.org/static_files/papers/imagenet_cvpr09.pdf) [[Dataset]](https://www.image-net.org/)
- ***CelebA-HQ:*** Progressive Growing of GANs for Improved Quality, Stability, and Variation [[Paper]](https://openreview.net/pdf?id=Hk99zCeAb) [[Dataset]](https://github.com/suvojit-0x55aa/celebA-HQ-dataset-download)