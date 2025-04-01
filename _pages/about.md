---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
 
# Short Bio 
I received my Ph.D. degree at <a href='https://en.ustc.edu.cn/'>University of Science and Technology of China</a> (USTC) in 2023. Prior to that, I received my Bachelor degree from the University of Science and Technology of China in 2018. 

My research interest includes general representation learning (e.g., fundamental network structure design, self-supervised pretraining) and artificial intelligence security (e.g., adversarial samples, DeepFake). 




# 🔥 News
- *2025.03*: &nbsp;🎉🎉 MMStar is selectd as <a href='https://www.paperdigest.org/2025/03/most-influential-nips-papers-2025-03-version/'>NeurIPS 2024 top10 Influential paper</a>.
- *2025.02*: &nbsp;🎉🎉 Dispider, ViCo, OVO-Bench, and ByTheWay were accepted by CVPR 2025.
- *2025.01*: &nbsp;🎉🎉 MIA-DPO and MotionClone were accepted by ICLR 2025.
- *2024.11*: &nbsp;🎉🎉 ShareGPT4V is selectd as <a href='https://www.paperdigest.org/2024/09/most-influential-eccv-papers-2024-09/'>ECCV 2024 top10 Influential paper</a>.
- *2024.11*: &nbsp;🎉🎉 InternLM-XComposer2 and InternVL is selectd as <a href='https://www.paperdigest.org/2024/10/most-influential-arxiv-computer-vision-and-pattern-recognition-papers-2024-10/'>Arxiv2024 CV top10 Influential paper</a>. 
- *2024.09*: &nbsp;🎉🎉 ShareGPT4Video, MMDU, and MMLongBench-Doc are accepted by NeurIPS2024 D&B.
- *2024.09*: &nbsp;🎉🎉 InternLM-XComposer2-4KHD, MMStar, and Video-Streaming are accepted by NeurIPS2024.
- *2024.07*: &nbsp;🎉🎉 ShareGPT4V and Long-CLIP are accepted by ECCV2024.
- *2024.05*: &nbsp;🎉🎉 PeCo is selectd as <a href='https://www.paperdigest.org/2024/05/most-influential-aaai-papers-2024-05/'>AAAI2023 top10 Influential paper</a>. 
- *2024.02*: &nbsp;🎉🎉 OPERA is accepted by CVPR2024 as Highlight.
- *2023.11*: &nbsp;🎉🎉 PointCAT is accepted by TIP.
- *2023.07*: &nbsp;🎉🎉 ELP and RobustMAE are accepted by ICCV2023.
- *2023.03*: &nbsp;🎉🎉 MaskCLIP and DAM-VP are accepted by CVPR2023. 
- *2023.01*: &nbsp;🎉🎉 CSWin is selectd as <a href='https://www.paperdigest.org/2023/01/most-influential-cvpr-papers-2023-01/'>CVPR2022 top10 Influential paper</a>. 
- *2022.12*: &nbsp;🎉🎉 PeCo is accepted by AAAI2023.
- *2022.10*: &nbsp;🎉🎉 MaskCLIP won the <a href='https://eval.ai/web/challenges/challenge-page/1832/overview'> 1st place in ICinW Industry Track</a>. 
- *2022.07*: &nbsp;🎉🎉 BootMAE and CD-Net are accepted by ECCV2022.
- *2022.03*: &nbsp;🎉🎉 CSWin, ICT, Mobile-Former, SI-Adv are accepted by CVPR2022. 
- *2021.11*: &nbsp;🎉🎉 PeCo reaches the <a href='https://paperswithcode.com/sota/image-classification-on-imagenet?tag_filter=171'>highest ImageNet-1K accuracy</a> w/o addition data.
- *2021.08*: &nbsp;🎉🎉 Tacr-net is accepted by ACM MM.
- *2020.09*: &nbsp;🎉🎉 GreedyFool is accepted by NeurIPS2020.
- *2020.03*: &nbsp;🎉🎉 Sup-ADV, GVG and LG-GAN are accepted by CVPR2020.
- *2019.07*: &nbsp;🎉🎉 MAN is accepted by ICCV2019. 

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/maskclip.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MaskCLIP: Masked Self-Distillation Advances Contrastive Language-Image Pretraining ](https://arxiv.org/abs/2208.12262)

**Xiaoyi Dong**, Jianmin Bao, Yinglin Zheng, Ting Zhang, Dongdong Chen, Hao Yang, Ming Zeng, Weiming Zhang, Lu Yuan, Dong Chen, Fang Wen, Nenghai Yu 

CVPR 2023 <span style="color:red"> [<span style="color:red">**1st in ICinW Industry Track**</span>](https://eval.ai/web/challenges/challenge-page/1832/overview)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/peco.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Peco: Perceptual codebook for bert pre-training of vision transformers ](https://arxiv.org/pdf/2111.12710.pdf)

**Xiaoyi Dong**, Jianmin Bao, Ting Zhang, Dongdong Chen, Weiming Zhang, Lu Yuan, Dong Chen, Fang Wen, Nenghai Yu 

AAAI 2023 <span style="color:red"> [<span style="color:red">**SOTA ImageNet-1K accuracy**</span>](https://paperswithcode.com/sota/image-classification-on-imagenet?tag_filter=171)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/bootmae.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Bootstrapped Masked Autoencoders for Vision BERT Pretraining ](https://arxiv.org/abs/2207.07116)

**Xiaoyi Dong**, Jianmin Bao, Ting Zhang, Dongdong Chen, Weiming Zhang, Lu Yuan, Dong Chen, Fang Wen, Nenghai Yu 

ECCV 2022 \| [**Github**](https://github.com/LightDXY/BootMAE) 


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/cswin.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CSWin Transformer: A General Vision Transformer Backbone with Cross-Shaped Windows ](https://arxiv.org/pdf/2107.00652.pdf)

**Xiaoyi Dong**, Jianmin Bao, Dongdong Chen, Weiming Zhang, Nenghai Yu, Lu Yuan, Dong Chen, Baining Guo 

CVPR 2022 <span style="color:red"> [<span style="color:red">**CVPR2022 top10 Influential paper**</span>](https://www.paperdigest.org/2023/01/most-influential-cvpr-papers-2023-01/) \| [**Github**](https://github.com/microsoft/CSWin-Transformer) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/ict_deepfake.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Protecting Celebrities from DeepFake with Identity Consistency Transformer ](https://arxiv.org/abs/2203.01318)

**Xiaoyi Dong**, Jianmin Bao, Dongdong Chen, Ting Zhang, Weiming Zhang, Nenghai Yu, Dong Chen, Fang Wen, Baining Guo 

CVPR 2022  \| [**Github**](https://github.com/LightDXY/ICT_DeepFake) 

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2020</div><img src='images/greedfool_nips2020.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ GreedyFool: Distortion-Aware Sparse Adversarial Attack ](https://arxiv.org/pdf/2010.13773.pdf)

**Xiaoyi Dong**, Dongdong Chen, Jianmin Bao, Chuan Qin, Lu Yuan, Weiming Zhang, Nenghai Yu, Dong Chen 

NeurIPS 2020  \| [**Github**](https://github.com/LightDXY/GreedyFool) 

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2020</div><img src='images/cvpr20_superatt.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust Superpixel-Guided Attentional Adversarial Attack](https://openaccess.thecvf.com/content_CVPR_2020/papers/Dong_Robust_Superpixel-Guided_Attentional_Adversarial_Attack_CVPR_2020_paper.pdf)

**Xiaoyi Dong**, Jiangfan Han, Dongdong Chen, et al., Nenghai Yu 

CVPR 2020  \| [**Github**](https://github.com/LightDXY/Super_Pix_Adv) 

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2020</div><img src='images/cvpr20_sr3d.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Self-Robust 3D Point Recognition via Gather-vector Guidance ](https://openaccess.thecvf.com/content_CVPR_2020/papers/Dong_Self-Robust_3D_Point_Recognition_via_Gather-Vector_Guidance_CVPR_2020_paper.pdf)

**Xiaoyi Dong**, Dongdong Chen, et al., Nenghai Yu 

CVPR 2020

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2019</div><img src='images/attack_iccv2019_nail.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Once a MAN: Towards Multi-Target Attack via Learning Multi-Target Adversarial Network Once ](https://arxiv.org/abs/1908.05185.pdf)

Jiangfan Han*, **Xiaoyi Dong***, Ruimao Zhang, Dongdong Chen, Weiming Zhang, Nenghai Yu, Ping Luo, Xiaogang Wang (* Equal Contribution)

ICCV 2019

</div>
</div>


<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- Outstanding Reviewer of CVPR2023, ICCV2021
- *2023.10*, President Scholarship, Chinese Academy of Sciences.
- *2023.05*, Outstanding Doctoral Dissertation Award, USTC
- *2023.05*, Excellent award, Stars of Tomorrow Internship Program, Microsoft Research Asia (MSRA). 
- *2020.06*, National Scholarship (The highest scholarship awarded by the Ministry of Education, China).
- *2019.09*, IJCAI-2019 Alibaba Adversarial AI Challenge(AAAC2019). 1st prize in Defense Track, 2nd prize in Non-Target Attack Track.
- *2018.10*, Competition on Adversarial Attacks and Defenses (CAAD2018). 2nd prize in Non-Target Attack Track.

# 📖 Educations
- *2018.06 - 2023.06*, Ph.D., University of Science and Technology of China.
- *2014.09 - 2018.06*, Undergraduate, University of Science and Technology of China.

# Professional Activities
- Reviewer for CVPR 2021, 2022, 2023
- Reviewer for ICCV 2021, 2023
- Reviewer for ECCV 2022
- Reviewer for NeurIPS 2023
- Reviewer for AAAI 2020, 2021, 2022
- Reviewer for IEEE Transactions on Pattern Analysis and Machine Intelligence(TPAMI)
- Reviewer for IEEE Transactions on Image Processing(TIP)

