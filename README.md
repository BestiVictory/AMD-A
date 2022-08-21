# AMD-A

This is an open-source image attribute dataset called aesthetic mixed dataset with attributes(AMD-A), which we completed in the [Victory team of Besti](https://www.victory-lab.net/).

In order to construct a dataset with a reasonable distribution both in image aesthetics quality assessment and image aesthetic attributes assessment, we rebuild a dataset named Aesthetic mixed dataset with attributes(AMD-A) cincluding 16924 images. According to different tasks, AMD-A is divided into two sets. One set(11166 images) is applied to aesthetic overall score regression, another set(16924 images) is applied to aesthetic attribute score classification and regression.

As for the attribute regression, we collect images from EVA [1], AADB [2], PCCD [3], PADB, and HADB. PADB and HADB are self-built datasets. Each image has three attribute labels and one overall label for assessment. The three attributes include light, color and composition. To increase the training samples of the aesthetic regression, we collected 5758 images with only overall scores from other datasets. There are  from DPCallenge.com, SCUI-FBP5500 [4], Photo.net and SPAQ [5]. Data labels are continuous and each one has a score range of 0-1. 

[1] Chen Kang, Giuseppe Valenzise, and Frédéric Dufaux. 2020. EVA: An Explainable Visual Aesthetics Dataset. In Joint Workshop on Aesthetic and Technical Quality Assessment of Multimedia and Media Analytics for Societal Trends. 5–13.

[2] Shu Kong, Xiaohui Shen, Zhe Lin, Radomir Mech, and Charless Fowlkes. 2016. Photo aesthetics ranking network with attributes and content adaptation. In European conference on computer vision. Springer, 662–679.

[3] Kuang-Yu Chang, Kung-Hung Lu, and Chu-Song Chen. 2017. Aesthetic critiques generation for photos. In Proceedings of the IEEE international conference on computer vision. 3514–3523.

[4] Lingyu Liang, Luojun Lin, Lianwen Jin, Duorui Xie, and Mengru Li. 2018. SCUT-FBP5500: a diverse benchmark dataset for multi-paradigm facial beauty prediction. In 2018 24th International Conference on Pattern Recognition (ICPR). IEEE, 1598–1603.

[5] Yuming Fang, Hanwei Zhu, Yan Zeng, Kede Ma, and Zhou Wang. 2020. Perceptual quality assessment of smartphone photography. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 3677–3686.
  
**PS: Considering the copyright of images, we will only open-source the picture number public.**
  
### Our Paper  
  
Xin Jin, Xinning Li, Hao Lou, Chenyu Fan, Qiang Deng, Chaoen Xiao, Shuai Cui, Amit Kumar Singh. 
Aesthetic Attribute Assessment of Images Numerically on Mixed Multi-attribute Datasets. ACM Transactions on Multimedia Computing Communications and Applications (TOMM) **[arXiv](https://arxiv.org/abs/2207.01806)**(2207.01806)

