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
I received my Ph.D. degree at <a href='https://en.ustc.edu.cn/'>University of Science and Technology of China</a> (USTC) in 2023. Prior to that, I received my Bachelor degree of Information Security at University of Science and Technology of China in 2018. 

My research interest includes general representation learning (e.g., fundamental network structure design, self-supervised pretraining) and artificial intelligence security (e.g., adversarial samples, DeepFake). 




# 🔥 News
- *2023.11*: &nbsp;🎉🎉 PointCAT is accepted by TIP.
- *2023.07*: &nbsp;🎉🎉 ELP and RobustMAE are accepted by ICCV2023.
- *2023.03*: &nbsp;🎉🎉 MaskCLIP and DAM-VP are accepted by CVPR2023. 
- *2023.01*: &nbsp;🎉🎉 CSWin is selectd as <a href='https://www.paperdigest.org/2023/01/most-influential-cvpr-papers-2023-01/'>CVPR2022 top10 Influential  paper</a>. 
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/buol.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BUOL: A Bottom-Up Framework with Occupancy-aware Lifting for Panoptic 3D Scene Reconstruction From A Single Image]()

Tao Chu, **Pan Zhang**, Qiong Liu, Jiaqi Wang

CVPR 2023 \| [**Code coming soon**]()
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/talking_head.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MetaPortrait: Identity-Preserving Talking Head Generation with Fast Personalized Adaptation](https://arxiv.org/pdf/2212.08062.pdf)

Bowen Zhang\*, Chenyang Qi\*, **Pan Zhang**, Bo Zhang, HsiangTao Wu, Dong Chen,  Qifeng Chen, Yong Wang, Fang Wen

CVPR 2023 \| [**Project**](https://meta-portrait.github.io/) \| [**Github** ![](https://img.shields.io/github/stars/Meta-Portrait/MetaPortrait?style=social)](https://github.com/Meta-Portrait/MetaPortrait)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/cmpi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Real-time neural character rendering with pose-guided multiplane images](https://arxiv.org/pdf/2204.11820.pdf)

Hao Ouyang, Bo Zhang, **Pan Zhang**, Hao Yang, Jiaolong Yang, Dong Chen,  Qifeng Chen, Fang Wen

ECCV 2022 \| [**Project**](https://ken-ouyang.github.io/cmpi/index.html) \| [**Github** ![](https://img.shields.io/github/stars/ken-ouyang/PGMPI?style=social)](https://github.com/ken-ouyang/PGMPI) \| [**Video**](https://youtu.be/otL3UAak7wQ) \| [**Dynamic MVS Data**](https://hkustconnect-my.sharepoint.com/:u:/g/personal/houyangab_connect_ust_hk/EZ_w1wUORJpHo1W1arGuL-QBoAr7WojoCOqsPMXQYk7h3Q?e=XrFuae)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021</div><img src='images/proda.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Prototypical Pseudo Label Denoising and Target Structure Learning for Domain Adaptive Semantic Segmentation](https://arxiv.org/pdf/2101.10979.pdf)

**Pan Zhang**, Bo Zhang,  Ting Zhang, Dong Chen, Yong Wang, Fang Wen

CVPR 2021 \| [**Github** ![](https://img.shields.io/github/stars/microsoft/ProDA?style=social)](https://github.com/microsoft/ProDA) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021</div><img src='images/cocosnet_v2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CoCosNet v2: Full-Resolution Correspondence Learning for Image Translation](https://arxiv.org/pdf/2012.02047.pdf)

Xingran Zhou, Bo Zhang, Ting Zhang, **Pan Zhang**, Jianmin Bao, Dong Chen, Zhongfei Zhang, Fang Wen

CVPR 2021 <span style="color:red">**Oral**</span>, [<span style="color:red">**Best Paper Candidate**</span>](https://cvpr2021.thecvf.com/node/290) \| [**Github** ![](https://img.shields.io/github/stars/microsoft/CoCosNet-v2?style=social)](https://github.com/microsoft/CoCosNet-v2) \| [**Slides**](https://www.dropbox.com/s/g7dezxm2mhw6gqo/CoCosNet%20slides.pptx?dl=0)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI</div><img src='images/oldphoto.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Old Photo Restoration via Deep Latent Space Translation](https://arxiv.org/pdf/2009.07047v1.pdf)

Ziyu Wan, Bo Zhang, Dongdong Chen, **Pan Zhang**, Dong Chen, Jing Liao, Fang Wen

 TPAMI \| 🔥[**Github** ![](https://img.shields.io/github/stars/microsoft/Bringing-Old-Photos-Back-to-Life?style=social)](https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life) \| [**Colab demo**](https://colab.research.google.com/drive/1NEm6AsybIiC5TwTU_4DqDkQO0nFRB-uA?usp=sharing) \| [**Replicate Demo**](https://replicate.ai/zhangmozhe/bringing-old-photos-back-to-life)


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2020</div><img src='images/cocosnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cross-domain Correspondence Learning for Exemplar-based Image Translation](https://arxiv.org/pdf/2004.05571.pdf)

**Pan Zhang**, Bo Zhang, Dong Chen, Lu Yuan, Fang Wen

CVPR 2020 <span style="color:red">**Oral**</span> \| [**Project**](https://panzhang0212.github.io/CoCosNet/) \| [**Github** ![](https://img.shields.io/github/stars/microsoft/CoCosNet?style=social)](https://github.com/microsoft/CoCosNet) \| [**Supplementary**](https://panzhang0212.github.io/CoCosNet/supplementary.pdf) \| [**Slides**](https://www.dropbox.com/s/g7dezxm2mhw6gqo/CoCosNet%20slides.pptx?dl=0) \| [**Video**](https://youtu.be/BdopAApRSgo)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2020</div><img src='images/OldPhotos_teaser3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Bringing Old Photos Back to Life](https://arxiv.org/pdf/2004.09484.pdf)

Ziyu Wan, Bo Zhang, Dongdong Chen, **Pan Zhang**, Dong Chen, Jing Liao, Fang Wen

CVPR 2020 <span style="color:red">**Oral**</span> \| [**Project**](http://raywzy.com/Old_Photo/) \| 🔥[**Github** ![](https://img.shields.io/github/stars/microsoft/Bringing-Old-Photos-Back-to-Life?style=social)](https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life) \| [**Supplementary**](https://drive.google.com/file/d/10cctmu06yfhackflwkv4dfq5aqktueff/view) \| [**Colab demo**](https://colab.research.google.com/drive/1NEm6AsybIiC5TwTU_4DqDkQO0nFRB-uA?usp=sharing) \| [**Replicate Demo**](https://replicate.ai/zhangmozhe/bringing-old-photos-back-to-life)

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

