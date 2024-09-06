---
id:             2023-unpaired-multiview
title:          "Learning from Semantic Alignment between Unpaired Multiviews for Egocentric Video Recognition"
authors:        
    - Me 
    - Long
    - Liangzhe
    - Ting
    - Xi
venue:          International Conference on Computer Vision (ICCV), Paris, France, 2023.
year:           "2023-10"
thumbnail:      assets/publications/2023-unpaired-multiview/title-image.png
overview:        assets/publications/2023-unpaired-multiview/overview.png
overview_text:  "Illustration of our framework. First, one batch (batch size = 4) of multiview pseudo-pairs is built from unpaired first-person and third-person videos. The pseudo-pairs are built based on mining the most semantics-similar third-person video for every first-person video. During training, the global features for multiview alignment (z_f, z_t) are extracted by their corresponding encoder, following the projection networks (h_f, h_t). In addition, textual features (d_f, d_t) are extracted by a large language model from textual narrations of first-person and third-person videos. The semantic similarity between d_f and d_t is calculated to filter out the multiview pseudo-pairs with low semantic similarity. Then the multiview pairs with high semantic similarity are employed to learn the view-invariant representations with the contrastive learning method. To further improve data efficiency, we employ all the first-person and third-person videos in the batch to learn contrastive multimodal relations. Finally, the task-specific heads (g_f, g_t) for both first-person and third-person videos are trained to make predictions for their corresponding downstream tasks. During testing, we only use the first-person encoder and task-specific head (g_f) to make first-person video predictions."
bibtex: "@InProceedings{Wang_2023_ICCV,<br>&emsp;author    = {Wang, Qitong and Zhao, Long and Yuan, Liangzhe and Liu, Ting and Peng, Xi},<br>&emsp;title     = {Learning from Semantic Alignment between Unpaired Multiviews for Egocentric Video Recognition},<br>&emsp;booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},<br>&emsp;month     = {October},<br>&emsp;year      = {2023},<br>&emsp;pages     = {3307-3317}<br>}"
links:
   paper:      https://arxiv.org/abs/2308.11489
   code:       https://github.com/wqtwjt1996/SUM-L
   blogpost:   https://research.google/blog/google-at-iccv-2023/
   bibtex:     assets/publications/2023-unpaired-multiview/ref.txt
results:
   text1:      Comparisons on Charades-Ego
   img1:       assets/publications/2023-unpaired-multiview/res/1.png
   text2:      Comparisons on EPIC-Kitchens
   img2:       assets/publications/2023-unpaired-multiview/res/2.png
   text3:      Comparisons on EPIC-Kitchens-100
   img3:       assets/publications/2023-unpaired-multiview/res/3.png

layout: project_plus
short_title: Unpaired Multiview Alignment
video_embed: https://www.youtube.com/embed/_B-i2S0nA1I?si=AG5BHvQmn8Mk4YWq
abstract: "We are concerned with a challenging scenario in unpaired multiview video learning. In this case, the model aims to learn comprehensive multiview representations while the cross-view semantic information exhibits variations. We propose Semantics-based Unpaired Multiview Learning (SUM-L) to tackle this unpaired multiview learning problem. The key idea is to build cross-view pseudo-pairs and do view-invariant alignment by leveraging the semantic information of videos. To facilitate the data efficiency of multiview learning, we further perform video-text alignment for first-person and third-person videos, to fully leverage the semantic knowledge to improve video representations. Extensive experiments on multiple benchmark datasets verify the effectiveness of our framework. Our method also outperforms multiple existing view-alignment methods, under the more challenging scenario than typical paired or unpaired multimodal or multiview learning."
---