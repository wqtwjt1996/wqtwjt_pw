---
id:             2020-text-det
title:          "A Method for Detecting Text of Arbitrary Shapes in Natural Scenes That Improves Text Spotting"
# authors:        [Qitong Wang, Yi Zheng, Margrit Betke]
authors:        
    - Me
    - Yi 
    - Margrit
venue:          Workshop on Text and Documents in the Deep Learning Era (CVPR), Virtual, 2020.
year:           "2020-06"
thumbnail:      assets/publications/2020-text-det/title-image.jpeg
bibtex: "@InProceedings{Wang_2020_CVPR_Workshops,<br>&emsp;author = {Wang, Qitong and Zheng, Yi and Betke, Margrit},<br>&emsp;title = {A Method for Detecting Text of Arbitrary Shapes in Natural Scenes That Improves Text Spotting},<br>&emsp;booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},<br>&emsp;month = {June},<br>&emsp;year = {2020}<br>}"
links:
   paper:      https://openaccess.thecvf.com/content_CVPRW_2020/html/w34/Wang_A_Method_for_Detecting_Text_of_Arbitrary_Shapes_in_Natural_CVPRW_2020_paper.html
   code:       https://github.com/wqtwjt1996/UHT
   bibtex:     assets/publications/2020-text-det/ref.txt

layout: project
short_title: Text Detection Workshop
abstract: "Understanding the meaning of text in images of natural scenes like highway signs or store front emblems is particularly challenging if the text is foreshortened in the image or the letters are artistically distorted. We introduce a pipeline-based text spotting framework that can both detect and recognize text in various fonts, shapes, and orientations in natural scene images with complicated backgrounds. The main contribution of our work is the text detection component, which we call UHT, short for UNet, Heatmap, and Textfill. UHT uses a UNet to compute heatmaps for candidate text regions and a textfill algorithm to produce tight polygonal boundaries around each word in the candidate text. Our method trains the UNet with groundtruth heatmaps that we obtain from text bounding polygons provided by groundtruth annotations. Our text spotting framework, called UHTA, combines UHT with the state-of-the-art text recognition system ASTER. Experiments on four challenging and public scene-text-detection datasets (Total-Text, SCUT-CTW1500, MSRA-TD500, and COCO-Text) show the effectiveness and generalization ability of UHT in detecting not only multilingual (potentially rotated) straight but also curved text in scripts of multiple languages. Our experimental results of UHTA on the Total-Text dataset show that UHTA outperforms four state-of-the-art text spotting frameworks by at least 9.1 percent points in the F-measure, which suggests that UHTA may be used as a complete text detection and recognition system in real applications."
---