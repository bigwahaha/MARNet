# MARNet
[Unifying Visual and Semantic Feature Spaces with Diffusion Models for Enhanced Cross-Modal Alignment](https://arxiv.org/abs/2407.18854)
## Introduction
Image classification models often demonstrate unstable performance in real-world applications due to variations in image information, driven by differing visual perspectives of subject objects and lighting discrepancies. To mitigate these challenges, existing studies commonly incorporate additional modal information matching the visual data to regularize the model's learning process, enabling the extraction of high-quality visual features from complex image regions. Specifically, in the realm of multimodal learning, cross-modal alignment is recognized as an effective strategy, harmonizing different modal information by learning a domain-consistent latent feature space for visual and semantic features. However, this approach may face limitations due to the heterogeneity between multimodal information, such as differences in feature distribution and structure. To address this issue, we introduce a Multimodal Alignment and Reconstruction Network (MARNet), designed to enhance the model's resistance to visual noise. Importantly, MARNet includes a cross-modal diffusion reconstruction module for smoothly and stably blending information across different domains. Experiments conducted on two benchmark datasets, Vireo-Food172 and Ingredient-101, demonstrate that MARNet effectively improves the quality of image information extracted by the model. It is a plug-and-play framework that can be rapidly integrated into various image classification frameworks, boosting model performance.
![image](https://github.com/user-attachments/assets/de0088da-b353-459c-9f2a-25dc7bcd0a90)
## Citation
If you find our work useful in your research, please consider citing MARNet:
```
@inproceedings{zheng2024unifying,
  title={Unifying Visual and Semantic Feature Spaces with Diffusion Models for Enhanced Cross-Modal Alignment},
  author={Zheng, Yuze and Li, Zixuan and Li, Xiangxian and Liu, Jinxing and Wang, Yuqing and Meng, Xiangxu and Meng, Lei},
  booktitle={International Conference on Artificial Neural Networks},
  pages={110--125},
  year={2024},
  organization={Springer}
}
```
