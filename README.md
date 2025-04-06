# Awesome-Spatial-Transformation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources including papers, datasets, and relevant links pertaining to spatial transformation for image composition, which aims to adjust the view/pose of the inserted foreground object in a composite image via simple spatial transformation (e.g., TPS transformation, perspective transformation). For more complete resources on general 
image composition ([object insertion](https://github.com/bcmi/Awesome-Object-Insertion)), please refer to [Awesome-Image-Composition](https://github.com/bcmi/Awesome-Object-Insertion).


## Contributing

Contributions are welcome.  If you wish to contribute, feel free to send a pull request. If you have suggestions for new sections to be included, please raise an issue and discuss before sending a pull request.
 
## Papers

+ Junhong Gou, Bo Zhang, Li Niu, Jianfu Zhang, Jianlou Si, Chen Qian, Liqing Zhang: "*Virtual Accessory Try-On via Keypoint Hallucination.*" arXiv preprint arXiv:2310.17131 (2023) [[arXiv]](https://arxiv.org/pdf/2310.17131.pdf)
+ Bo Zhang, Yue Liu, Kaixin Lu, Li Niu, Liqing Zhang: "*Spatial Transformation for Image Composition via Correspondence Learning.*" arXiv preprint arXiv:2207.02398 (2022) [[arXiv]](https://arxiv.org/pdf/2207.02398.pdf)
+ Fangneng Zhan, Hongyuan Zhu, Shijian Lu: "*Spatial Fusion GAN for Image Synthesis.*" CVPR (2019) [[pdf]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhan_Spatial_Fusion_GAN_for_Image_Synthesis_CVPR_2019_paper.pdf) 
+ Chen-Hsuan Lin, Ersin Yumer, Oliver Wang, Eli Shechtman, Simon Lucey: "*ST-GAN: Spatial Transformer Generative Adversarial Networks for Image Compositing.*" CVPR (2018) [[pdf]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Lin_ST-GAN_Spatial_Transformer_CVPR_2018_paper.pdf) [[code]](https://github.com/chenhsuanlin/spatial-transformer-GAN)

## Datasets

+ **STRAT**: it contains three subdatasets: STRAT-glasses, STRAT-hat, and STRAT-tie, which correspond to "glasses try-on", "hat try-on", and "tie try-on" respectively. The accessory image (resp., human face or portrait image) is treated as foreground (resp., background). In each subdataset, the training set has 2000 pairs of foregrounds and backgrounds, while the test set has 1000 pairs of foregrounds and backgrounds. [[pdf]](https://arxiv.org/pdf/2207.02398.pdf) [[link]](https://github.com/bcmi/Accessory-Try-On-Dataset-STRAT)


## Other Resources

+ [Awesome-Image-Composition](https://github.com/bcmi/Awesome-Object-Insertion)
