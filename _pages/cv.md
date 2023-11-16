---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

---

Education
======
* **University of California San Diego**, Sept. 2020 - Present
  * Ph.D in Electrical and Computer Engineering, Current overall GPA: 4.0/4.0
  * Advisor: Prof. [Truong Q. Nguyen](http://jacobsschool.ucsd.edu/faculty/faculty_bios/index.sfe?fmp_recid=48)
  * Research: Deep learning based retinal image analysis

* **University of Science and Technology of China**, Sept. 2017 - July 2020
  * Master in Electrical Engineering, Overall GPA: 4.01/4.3
  * Advisor: Prof. [Dong Liu](https://faculty.ustc.edu.cn/dongeliu/en/index/85593/list/index.htm)
  * Research: Deep learning based image and video super-resolution

* **University of Science and Technology of China**, Aug. 2013 - June 2017
  * B.S. in Electrical Engineering, Overall GPA: 3.73/4.3



Internship
======
* **Advanced Analytic Intern**, May. 2023 – Aug. 2023
  * OXY Petroleum, Houston
  * PI: Dr. Nikolaos Mitsakos, Dr. Ahmad Mustafa, Dr. Daniel De Lilla
  * Adopted segmentation network for seismic horizon tracking task, seeking to alleviate the interpretation burden on geologists dealing with 3D volumetric data. 
    * Improved the performance with label trick, multi-inline input and ConvLSTM;
    * Predicted 80% of horizon within 3-pixel-tolerance using only 1% manual label.

* **Computer Vision Research Intern**, Nov. 2020 – Aug. 2021
  * AI Lab, ByteDance, Beijing
  * PI: Dr. [Zehuan Yuan](https://shallowyuan.github.io/)
  * Trial-and-error: Proposed and implemented many ideas in computer vision field, especially low-level vision. 
    * For example, using knowledge distillation as implicit prior for super-resolution;
    * Searching the best simulation degradation for real world super-resolution.


Research Experience
======
* **2D and 3D Retina OCT Angiography images classification**, Dec. 2021 – Present
  * Video Processing Lab @ UCSD, PI: Dr. [Truong Q. Nguyen](http://videoprocessing.ucsd.edu/?page_id=40)
  * Detect and differentiate active and inactive choroidal neovascularization (CNV) in different stages of age-related macular degeneration (AMD) using Optical Coherence Tomography Angiography (OCTA) scans.
  * It is like a fine-grained classification problem since the categories belong to one disease but in different stages. 
  * The challenges are small dataset with unbalanced distribution and potential retina layer segmentation errors.
  * One paper has been published in ICCVW 2023 [5].

* **Domain Adaptation based Unpaired Super-Resolution**, Nov. 2020 – Apr. 2021
  * ByteDance AI Lab @ Beijing, PI: Dr. [Zehuan Yuan](https://shallowyuan.github.io/)
  * Formulated unpaired SR training as a feature-level domain adaptation problem, where the given LR images can be regard as the inputs in target domain and the provided HR images can be seen as label in source domain. 
  * Adopted adversarial-based _feature distribution alignment_ to close the gap between source and target feature domains, and proposed several _feature domain regularizations_ to achieve better aligning performance as well as preserve image details for the downstream SR task. 
  * This work has been published in ICCV 2021 [4].
  
* **Tradeoff in Signal Restoration**,  Mar. 2019 – July. 2020
  * MOE-Microsoft Key Laboratory of Multimedia Computing and Communication @ USTC, PI: Dr. [Dong Liu](http://staff.ustc.edu.cn/~dongeliu/)
  * Analyzed the relationship among _signal fidelity_, _perceptual naturalness_ and _semantic quality_ in the image restoration tasks. Demonstrated a _tradeoff_ among the three metrics _theoretically_ and _experimentally_. 
  * This work has been published in NeurIPS 2019 [3].

* **Video Super-Resolution and Inverse Tone-Mapping**,  Nov. 2019 – Jan. 2020
  * MOE-Microsoft Key Laboratory of Multimedia Computing and Communication @ USTC, PI: Dr. [Dong Liu](http://staff.ustc.edu.cn/~dongeliu/)
  * Participated in the 4K-HDR track of the first National Artificial Intelligence Challenge ([NAIC](https://naic.pcl.ac.cn/landingpage/2019/index.html)). 
  * After passing the preliminary (_super-resolution on noisy video_) and the semi-final (_video super-resolution + enhancement_) round, we entered the final round with the best performance. 
  * During the final round, we completed the _video super-resolution + SDR to HDR task_ using the specified machine within the specified time. Through subjective and objective evaluation and on-site defense, we finally won the runner-up prize with ￥500,000 bonus.

* **Video Super-Resolution Tailored for Action Recognition**,  Sept. 2017 – Mar. 2019
  * MOE-Microsoft Key Laboratory of Multimedia Computing and Communication @ USTC, PI: Dr. [Dong Liu](http://staff.ustc.edu.cn/~dongeliu/)
  * Investigated the video super-resolution (SR) problem for facilitating video analytics tasks rather than for visual quality. 
  * Tailored for two-stream action recognition networks, we developed SR methods for the spatial and temporal recognition respectively. On the one hand, we proposed _an optical-flow guided weighted MSE_ to emphasize the reconstruction of moving objects. On the other hand, we proposed _a siamese network training strategy_ in order to guarantee the temporal continuity between consecutive frames. 
  * This work has been published in ICCV 2019 [2].

* **Text Image Super-Resolution Tailored for OCR**,  Sept. 2016 – June 2017
  * MOE-Microsoft Key Laboratory of Multimedia Computing and Communication @ USTC, PI: Dr. [Dong Liu](http://staff.ustc.edu.cn/~dongeliu/)
  * Developed text image SR method to help optical character recognition (OCR). 
  * We proposed _an edge-based loss function_ for SR training and conducted model combination to further improve the performance. Besides, we also developed _an image padding method_ to refine the image boundaries during SR. 
  * This work has been published in VCIP 2017 [1].
  

Publications
======
Also see [pulication](https://alanzhang1995.github.io/Haochen-Zhang.github.io//publications/) page.

[1] **Haochen Zhang**, Dong Liu $^*$, Zhiwei Xiong. [CNN-based Text Image Super-Resolution Tailored for OCR](https://ieeexplore.ieee.org/abstract/document/8305127), In _VCIP_, St. Petersburg, FL, USA. Dec.10-13, 2017. 

[2] **Haochen Zhang**, Dong Liu $^*$, Zhiwei Xiong. [Two-Stream Action Recognition-Oriented Video Super-Resolution](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Two-Stream_Action_Recognition-Oriented_Video_Super-Resolution_ICCV_2019_paper.pdf), In _ICCV_, Seoul, Korea. Oct.27-Nov.2, 2019.

[3] Dong Liu $^*$, **Haochen Zhang**, Zhiwei Xiong. [On the Classification-Distortion-Perception Tradeoff](https://papers.nips.cc/paper/2019/file/6c29793a140a811d0c45ce03c1c93a28-Paper.pdf), In _NeurIPS_, Vancouver, Canada. Dec.8-14, 2019.

[4] Wei Wang $^\dagger$, **Haochen Zhang** $^\dagger$, Zehuan Yuan $^*$, Changhu Wang. [Unsupervised Real-World Super-Resolution: A Domain Adaptation Perspective](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Unsupervised_Real-World_Super-Resolution_A_Domain_Adaptation_Perspective_ICCV_2021_paper.pdf), In _ICCV_, Virtual. Oct.11-17, 2021.

[5] **Haochen Zhang**, Anna Heinke, Carlo Galang, Daniel Deussen, Bo Wen, Dirk-Uwe Bartsch, William Freeman, Truong Nguyen $^* $, Cheolhong An $^* $. [Robust AMD Stage Grading with Exclusively OCTA Modality Leveraging 3D Volume](https://openaccess.thecvf.com/content/ICCV2023W/CVAMD/papers/Zhang_Robust_AMD_Stage_Grading_with_Exclusively_OCTA_Modality_Leveraging_3D_ICCVW_2023_paper.pdf), In _ICCVW_, Paris, France. Oct.2-Oct.6, 2023.

<p align="right"> $^*$ denotes my advisor, $^\dagger$ denotes equal contribution co-author </p>
