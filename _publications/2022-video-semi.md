---
id:             2022-video-semi
title:          "Learning Representational Invariances for Data-Efficient Action Recognition"
# authors:        [Yuliang Zou, Jinwoo Choi*, Qitong Wang, and Jia-Bin Huang]
authors:        
    - Yuliang 
    - Jinwoo
    - Me
    - Jiabin
authors_note:   (* corresponding author)
venue:          Computer Vision and Image Understanding (CVIU), 2022.
year:           "2022-11"
thumbnail:      assets/publications/2022-video-semi/title-image.png
bibtex: "@article{zou2023learning,<br>&emsp;title={Learning representational invariances for data-efficient action recognition},<br>&emsp;author={Zou, Yuliang and Choi, Jinwoo and Wang, Qitong and Huang, Jia-Bin},<br>&emsp;journal={Computer Vision and Image Understanding},<br>&emsp;volume={227},<br>&emsp;pages={103597},<br>&emsp;year={2023},<br>&emsp;publisher={Elsevier}<br>}"
links:
   paper:      https://arxiv.org/abs/2103.16565
   code:       https://github.com/vt-vl-lab/video-data-aug
   website:    https://yuliang.vision/video-data-aug/
   bibtex:     assets/publications/2022-video-semi/ref.txt

layout: project_plus
short_title: Video Augmentation
abstract: "Data augmentation is a ubiquitous technique for improving image classification when labeled data is scarce. Constraining the model predictions to be invariant to diverse data augmentations effectively injects the desired representational invariances to the model (e.g., invariance to photometric variations) and helps improve accuracy. Compared to image data, the appearance variations in videos are far more complex due to the additional temporal dimension. Yet, data augmentation methods for videos remain under-explored. This paper investigates various data augmentation strategies that capture different video invariances, including photometric, geometric, temporal, and actor/scene augmentations. When integrated with existing semi-supervised learning frameworks, we show that our data augmentation strategy leads to promising performance on the Kinetics-100/400, Mini-Something-v2, UCF-101, and HMDB-51 datasets in the low-label regime. We also validate our data augmentation strategy in the fully supervised setting and demonstrate improved performance."
---