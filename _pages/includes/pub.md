# 📝 Publications 
## 🧑‍🎨 Face Recognition
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TBIOM 2024</div><img src='images/tbiom_2024.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning Multi-Scale Knowledge-Guided Features for Text-Guided Face Recognition](https://doi.org/10.1109/TBIOM.2024.3466216) \\
 IEEE Transactions on Biometrics, Behavior, and Identity Science (TBIOM)\\
**Md Mahedi Hasan**, Shoaib Meraj Sami, Nasser Nasrabadi, and Jeremy Dawson [\[code\]](https://github.com/Mahedi-61/Text_Guided_Face_Recognition)
<details>
<summary>Abstract</summary>
Text-guided face recognition (TGFR) aims to improve the performance of state-of-the-art face recognition (FR) algorithms by incorporating auxiliary information, such as distinct facial marks and attributes, provided as natural language descriptions. Current TGFR algorithms have been proven to be highly effective in addressing performance drops in state-of-the-art FR models, particularly in scenarios involving sensor noise, low resolution, and turbulence effects. Although existing methods explore various algorithms using different cross-modal alignment and fusion techniques, they encounter practical limitations in real-world applications. For example, during inference, textual descriptions associated with face images may be missing, lacking crucial details, or incorrect. Furthermore, the presence of inherent modality heterogeneity poses a significant challenge in achieving effective cross-modal alignment. To address these challenges, we introduce CaptionFace, a TGFR framework that integrates GPTFace, a face image captioning model designed to generate context-rich natural language descriptions from low-resolution facial images. By leveraging GPTFace, we overcome the issue of missing textual descriptions, expanding the applicability of CaptionFace to single-modal FR datasets. Additionally, we introduce a multi-scale feature alignment (MSFA) module to ensure semantic alignment between face-caption pairs at different granularities. Furthermore, we introduce an attribute-aware loss and perform knowledge adaptation to specifically adapt textual knowledge from facial features. Extensive experiments on three face-caption datasets and various unconstrained single-modal benchmark datasets demonstrate that CaptionFace significantly outperforms state-of-the-art FR models and existing TGFR approaches.
</details>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WACV 2024</div><img src='images/wacv_2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Text-Guided Face Recognition using Multi-Granularity Cross-Modal Contrastive Learning](https://openaccess.thecvf.com/content/WACV2024/html/Hasan_Text-Guided_Face_Recognition_Using_Multi-Granularity_Cross-Modal_Contrastive_Learning_WACV_2024_paper.html) \\
IEEE/CVF Winter Conference on Applications of Computer Vision (WACV 2024) \\
**Md Mahedi Hasan**, Shoaib Meraj Sami, and Nasser Nasrabadi. [\[code\]](https://github.com/Mahedi-61/Text_Guided_Face_Recognition) [\[video\]](https://www.youtube.com/watch?v=Hb8SlpFCuGI)

<details>
<summary>Abstract</summary>
State-of-the-art face recognition (FR) models often experience a significant performance drop when dealing with facial images in surveillance scenarios where images are in low quality and often corrupted with noise. Leveraging facial characteristics, such as freckles, scars, gender, and ethnicity, becomes highly beneficial in improving FR performance in such scenarios. In this paper, we introduce text-guided face recognition (TGFR) to analyze the impact of integrating facial attributes in the form of natural language descriptions. We hypothesize that adding semantic information into the loop can significantly improve the image understanding capability of an FR algorithm compared to other soft biometrics. However, learning a discriminative joint embedding within the multimodal space poses a considerable challenge due to the semantic gap in the unaligned image-text representations, along with the complexities arising from ambiguous and incoherent textual descriptions of the face. To address these challenges, we introduce a face-caption alignment module (FCAM), which incorporates cross-modal contrastive losses across multiple granularities to maximize the mutual information between local and global features of the face-caption pair. Within FCAM, we refine both facial and textual features for learning aligned and discriminative features. We also design a face-caption fusion module (FCFM) that applies fine-grained interactions and coarse-grained associations among cross-modal features. Through extensive experiments conducted on three face-caption datasets, proposed TGFR demonstrates remarkable improvements, particularly on low-quality images, over existing FR models and outperforms other related methods and benchmarks.
</details>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCB 2024</div><img src='images/IJCB_2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Improving Face Recognition from Caption Supervision with Multi-Granular Contextual Feature Aggregation](https://doi.org/10.1109/IJCB57857.2023.10448749) \\
2023 IEEE International Joint Conference on Biometrics (IJCB 2023) \\
**Md Mahedi Hasan**, and Nasser Nasrabadi.
<details>
<summary>Abstract</summary>
We introduce caption-guided face recognition (CGFR) as a new framework to improve the performance of commercial-off-the-shelf (COTS) face recognition (FR) systems. In contrast to combining soft biometrics (eg., facial marks, gender, and age) with face images, in this work, we use facial descriptions provided by face examiners as a piece of auxiliary information. However, due to the heterogeneity of the modalities, improving the performance by directly fusing the textual and facial features is very challenging, as both lie in different embedding spaces. In this paper, we propose a contextual feature aggregation module (CFAM) that addresses this issue by effectively exploiting the fine-grained word-region interaction and global image-caption association. Specifically, CFAM adopts a self-attention and a cross-attention scheme for improving the intra-modality and inter-modality relationship between the image and textual features, respectively. Additionally, we design a textual feature refinement module (TFRM) that refines the textual features of the pre-trained BERT encoder by updating the contextual embeddings. This module enhances the discriminative power of textual features with a cross-modal projection loss and realigns the word and caption embeddings with visual features by incorporating a visual-semantic alignment loss. We implemented the proposed CGFR framework on two face recognition models (ArcFace and AdaFace) and evaluated its performance on the Multi-Modal CelebA-HQ dataset. Our framework significantly improves the performance of ArcFace in both 1:1 verification and 1:N identification protocol.
</details>
</div>
</div>

## 🧑‍🎨 Continual Learning
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WACV 2025</div><img src='images/wacv_2025.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[CLFace: A Scalable and Resource-Efficient Continual Learning Framework for Lifelong Face Recognition]() \\
IEEE/CVF Winter Conference on Applications of Computer Vision (WACV 2025) \\
**Md Mahedi Hasan**, Shoaib Meraj Sami, Nasser Nasrabadi, and Jeremy Dawson [\[code\]]()
<details>
<summary>Abstract</summary>
An important aspect of deploying face recognition (FR) algorithms in real-world applications is their ability to learn new face identities from a continuous data stream. However, the online training of existing deep neural network-based FR algorithms, which are pre-trained offline on large-scale stationary datasets, encounter two major challenges: 1. catastrophic forgetting of previously learned identities, and 2. the need to store past data for complete retraining from scratch, leading to significant storage constraints and privacy concerns. In this paper, we introduce CLFace, a continual learning framework designed to preserve and incrementally extend the learned knowledge. CLFace eliminates the classification layer, resulting in a resource-efficient FR model that remains fixed throughout lifelong learning and provides label-free supervision to a student model, making it suitable for open-set face recognition during incremental steps. We introduce an objective function that employs feature-level distillation to reduce drift between feature maps of the student and teacher models across multiple stages. Additionally, it incorporates a geometry-preserving distillation scheme to maintain the orientation of the teacher model's feature embedding. Furthermore, a contrastive knowledge distillation is incorporated to continually enhance the discriminative power of the feature representation by matching similarities between new identities. Experiments on several benchmark FR datasets demonstrate that CLFace outperforms baseline approaches and state-of-the-art methods on unseen identities using both in-domain and out-of-domain datasets.
</details>
</div>
</div>

## 🎼 Automatic Target Recognition
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TAES 2024</div><img src='images/TAES_2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Contrastive Learning and Cycle Consistency-Based Transductive Transfer Learning for Target Annotation](https://doi.org/10.1109/TAES.2023.3337768) \\
IEEE Transactions on Aerospace and Electronic Systems (TAES 2024) \\
Shoaib Meraj Sami, **Md Mahedi Hasan**, Nasser Nasrabadi, Raghuveer Rao
<details>
<summary>Abstract</summary>
Annotating automatic target recognition (ATR) is a highly challenging task, primarily due to the unavailability of labeled data in the target domain. Hence, it is essential to construct an optimal target domain classifier by utilizing the labeled information of the source domain images. The transductive transfer learning (TTL) method that incorporates a CycleGAN-based unpaired domain translation network has been previously proposed in the literature for effective ATR annotation. Although this method demonstrates great potential for ATR, it severely suffers from lower annotation performance, higher Fréchet inception distance (FID) score, and the presence of visual artifacts in the synthetic images. To address these issues, we propose a hybrid contrastive learning base unpaired domain translation (H-CUT) network that achieves a significantly lower FID score. It incorporates both attention and entropy to emphasize the domain-specific region, a noisy feature mixup module to generate high variational synthetic negative patches, and a modulated noise contrastive estimation (MoNCE) loss to reweight all negative patches using optimal transport for better performance. Our proposed contrastive learning and cycle-consistency-based TTL (C3TTL) framework consists of two H-CUT networks and two classifiers. It simultaneously optimizes cycle-consistency, MoNCE, and identity losses. In C3TTL, two H-CUT networks have been employed through a bijection mapping to feed the reconstructed source domain images into a pretrained classifier to guide the optimal target domain classifier. Extensive experimental analysis conducted on six ATR datasets demonstrates that the proposed C3TTL method is effective in annotating civilian and military vehicles, ships, planes, and human targets.
</details>
</div>
</div>

## 📚 Fingerprint Recognition 
- `IET Biometrics 2023` [On Improving Interoperability for Cross-Domain Multi-Finger Fingerprint Matching Using Coupled Adversarial Learning](https://doi.org/10.1049/bme2.12117), **Md Mahedi Hasan**, Nasser Nasrabadi, and Jeremy Dawson 
- `BIOSIG 2022` [Deep Coupled GAN-Based Score-Level Fusion for Multi-Finger Contact to Contactless Fingerprint Matching](https://doi.org/10.1109/BIOSIG55365.2022.9897056) <span style="color:red">[Oral Presentation]</span>
**Md Mahedi Hasan**, Nasser Nasrabadi, and Jeremy Dawson 

## 🎼 Gait Recognition
- `IET Computer Vision 2021` [Learning view-invariant features using stacked autoencoder for skeleton-based gait recognition](https://doi.org/10.1049/cvi2.12050), **Md Mahedi Hasan**, and Hossen Asiful Mustafa. 
- `IJCSIS 2021` [Multi-level feature fusion for robust pose-based gait recognition using RNN](https://www.academia.edu/download/61987403/03_Paper_01012007_IJCSIS_Camera_Ready_pp20-3120200204-65998-gq509w.pdf), **Md Mahedi Hasan**, and Hossen Asiful Mustafa. <strong><span class='show_paper_citations' data='m3MlVBUAAAAJ:r0BpntZqJG4C'></span></strong>

## Others
- `ETCCE 2021` [A deep Spatio-temporal network for vision-based sexual harassment detection](https://doi.org/10.1109/ETCCE54784.2021.9689891), Md Shamimul Islam, **Md Mahedi Hasan**, Sohaib Abdullah, et al.
- ``Book Chapter 2020`` [Deep Learning based Early Detection and Grading of Diabetic Retinopathy Using Retinal Fundus Images](http://dx.doi.org/10.1201/9781003031352-6), Sheikh Muhammad Saiful Islam, **Md Mahedi Hasan**, Sohaib Abdullah <strong><span class='show_paper_citations' data='m3MlVBUAAAAJ:R3hNpaxXUhUC'></span></strong> [arXiv](https://arxiv.org/abs/1812.10595)
- `RAAICON 2019` [Robust Pose-Based Human Fall Detection using Recurrent Neural Network](https://doi.org/10.1109/RAAICON48939.2019.23), **Md Mahedi Hasan**, Md Shamimul Islam, Sohaib Abdullah <strong><span class='show_paper_citations' data='m3MlVBUAAAAJ:maZDTaKrznsC'></span></strong> 
- `ICBSLP 2019` [Aibangla: A Benchmark Dataset for Isolated Bangla Handwritten Basic and Compound Character Recognition](https://doi.org/10.1109/ICBSLP47725.2019.201481), **Md Mahedi Hasan**, Mahathir Mohammad Abir, et al. [\[dataset\]](https://doi.org/10.17632/hf2tt9kxkn.1)
- `ICBSLP 2018` [YOLO-Based Three-Stage Network for Bangla License Plate Recognition in Dhaka Metropolitan City](https://doi.org/10.1109/ICBSLP.2018.8554668), Sohaib Abdullah, **Md Mahedi Hasan**, Sheikh Muhammad Saiful Islam <span class='show_paper_citations' data='m3MlVBUAAAAJ:HDshCWvjkbEC'></span> [\[code\]](https://github.com/Mahedi-61/Text_Guided_Face_Recognition), [\[dataset\]](https://github.com/Mahedi-61/Bangla_License_Plate_Dataset)
- `ICCIT 2018` [DEEPGONET: Multi-label Prediction of GO Annotation for Protein from Sequence Using Cascaded Convolutional and Recurrent Network](https://doi.org/10.1109/ICCITECHN.2018.8631921), Sheikh Muhammad Saiful Islam, **Md Mahedi Hasan** 
- `IJCSIS 2020` [Forensic Detection of Digital Image Tampering Using Statistical Analysis](https://doi.org/10.5281/zenodo.4130382), Md. Zahurul Haque, **Md Mahedi Hasan** 

# 📝 Research Grants
## Multi-Finger Contactless Fingerprint Matching
-   PI Name: Jeremy M. Dawson, Nasser M. Nasrabadi
-   Name of Funding Organization: [CITer](https://citer.clarkson.edu/) (Project \#21S-04W),  IUCRC - NSF
-   Period of Grant Award: 1 Year (08/13/2021 - 08/12/2022)
-   Amount: $50,000
-   Project Title: **Evaluation of the Performance of Multi-Finger Contactless Fingerprint Matching**
-   <p align="justify">My Role in the Project: I developed an algorithm for multi-finger contactless fingerprint matching. I successfully achieved all project milestones under the supervision of the PIs. I presented the final report and webinar, along with publishing two academic papers based on the experimental results. </p>

## One-to-One Face Recognition
-   PI Name: Nasser M. Nasrabadi, Jeremy M. Dawson
-   Name of Funding Organization: [CITer](https://citer.clarkson.edu/) (Project #22S-06W),  IUCRC - NSF
-   Period of Grant Award: 1 Year (11/05/2022 - 04/21/2023)
-   Amount: $50,000
-   Project Title: **One-to-One Face Recognition with Human Examiner in the Loop**
-   <p align="justify">My Role in the Project: I developed a text-guided face recognition (FR) system to improve the performance of state-of-the-art FR algorithms by integrating facial attributes through natural language descriptions. I successfully met all project milestones under the supervision of the PIs. I presented both the progress report and the final report, and additionally published two academic papers.</p>

## Deep Face Recognition
-   PI Name: Nasser M. Nasrabadi, **Md Mahedi Hasan**
-   Name of Funding Organization: [CITer](https://citer.clarkson.edu/) (Project #22F-01W),  IUCRC - NSF
-   Period of Grant Award: 1 Year (09/03/2022 - 10/25/2023)
-   Amount: $50,000
-   Project Title: **A Perpetual Deep Face Recognition System**
-   <p align="justify">My Role in the Project: I wrote the proposal with Prof. Nasser. I designed the class-incremental learning framework which can learn and improve from a sequence of face recognition tasks without storing any exemplar sets. I successfully completed all the project milestones. I presented the progress and the final report. </p>

# 📝 Research Projects
### License Plate Recognition
-  Project Title: Real-time Automatic Bangla License Plate Detection and Recognition
-  Period: 1 Year (05/01/2018 - 04/30/2019)
-  Description: We have developed a real-time automatic Bangla license plate recognition system based on YOLO-v3. Additionally, we curated a dataset comprising 1,500 diverse images of Bangladeshi vehicular license plates. These images were manually captured from streets, simulating various real-world scenarios. This project is funded by department of CSE, Manarat International University ([MIU](https://manarat.ac.bd/)).
-  Resources: [\[dataset\]](https://github.com/Mahedi-61/Bangla_License_Plate_Dataset), [\[paper\]](https://doi.org/10.1109/ICBSLP.2018.8554668) 

### Bangla Handwritten Character Recognition
-  Project Title: Deep Isolated Bangla Handwritten Basic and Compound Character Recognition
-  Period: 1 Year (01/12/2018 - 12/30/2018)
-  Description: We present AIBangla, a new benchmark image database for isolated handwritten Bangla characters with detailed usage and a performance baseline. Our dataset contains 80,403 hand-written images on 50 Bangla basic characters and 249,911 hand-written images on 171 Bangla compound characters which were written by more than 2,000 unique writers from various institutes across Bangladesh. This project is funded by department of CSE, Manarat International University ([MIU](https://manarat.ac.bd/))
-  Resources: [\[dataset\]](https://doi.org/10.17632/hf2tt9kxkn.1), [\[paper\]](https://doi.org/10.1109/ICBSLP47725.2019.201481) 

### Bangla Sign Language Recognition
-  Project Title: Deep Bangla Sign Language Recognition from Video: A New Large-scale Dataset
-  Period: 2 Year (11/05/2021 - 04/05/2023)
- Description: We have developed an attention-based Bi-GRU model that captures the temporal dynamics of pose information used by individuals communicating through sign language. Furthermore, we created a large-scale dataset called the MVBSL-W50, which comprises 50 isolated words across 13 categories. 
- Resources: [\[dataset\]](https://github.com/Mahedi-61/MV-BSDL), [\[paper\]](https://arxiv.org/abs/2302.11559)