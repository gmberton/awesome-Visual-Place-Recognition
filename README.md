# Awesome Visual Place Recognition [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of papers on Visual Place Recognition and related fields, inspired by [awesome-NeRF](https://github.com/awesome-NeRF/awesome-NeRF).
PRs are very much appreciated.

#### [How to submit a pull request?](https://github.com/gmberton/awesome-Visual-Place-Recognition/blob/main/how-to-PR.md)



## Table of Contents

- [Surveys](#surveys) 
- [Papers](#papers)
- [Talks](#talks)



## Surveys

| Title | First Author | Venue | Github | Bibtex |
|---|---|---|---|---|
| [Visual Place Recognition: A Tutorial](https://ieeexplore.ieee.org/document/10261441) | Stefan Schubert | RAM 2023 |  | [BibTex](citations/Schubert_2023_vpr_tutorial.txt) |
| [Place recognition survey: An update on deep learning approaches](https://arxiv.org/abs/2106.10458) | Tiago Barros | ArXiv 2022 |  | [BibTex](citations/Barros_2022_Survey.txt) |
| [General Place Recognition Survey: Towards the Real-world Autonomy Age](https://ieeexplore.ieee.org/abstract/document/10937370) | Peng Yin | T-RO 2025 |  | [BibTex](citations/Yin_2025_GeneralPR.txt) |
| [A Survey on Deep Visual Place Recognition](https://ieeexplore.ieee.org/document/9336674) | Carlo Masone | IEEE Access 2021 |  | [BibTex](citations/Masone_2021_survey.txt) |
| [Visual place recognition: A survey from deep learning perspective](https://www.sciencedirect.com/science/article/abs/pii/S003132032030563X) | Xiwu Zhang | Pattern Recognition 2021 |  | [BibTex](citations/Zhang_2021_Survey.txt) |
| [Where is your place, Visual Place Recognition?](https://arxiv.org/abs/2103.06443) | Sourav Garg | IJCAI 2021 |  | [BibTex](citations/Garg_2021_Survey.txt) |
| [Visual Place Recognition: A Survey](https://ieeexplore.ieee.org/document/7339473) | Stephanie Lowry | IEEE Transactions on Robotics 2016 |  | [BibTex](citations/Lowry_2016_Survey.txt) |


## Papers

Papers are roughly split into categories, and a paper can (rarely) appear in more than one category. Papers are sorted in reverse chronological order within each category.

<details open>
<summary>Standard VPR</summary>

| Title | First Author | Venue | Github | Bibtex |
|---|---|---|---|---|
| [MegaLoc: One Retrieval to Place Them All](https://arxiv.org/abs/2502.17237) | Gabriele Berton | | [GitHub](https://github.com/gmberton/MegaLoc) | [BibTex](./citations/Berton_2025_MegaLoc.txt)
| [Close, But Not There: Boosting Geographic Distance Sensitivity in Visual Place Recognition](https://arxiv.org/abs/2407.02422) | Sergio Izquierdo | ECCV 2024 | [GitHub](https://github.com/serizba/cliquemining) | [BibTex](./citations/Izquierdo_2024_cliquemining.txt)
| [VLAD-BuFF: Burst-aware Fast Feature Aggregation for Visual Place Recognition](https://arxiv.org/abs/2409.19293) | Ahmad Khaliq | ECCV 2024 | [GitHub](https://github.com/Ahmedest61/VLAD-BuFF/) | [BibTex](./citations/Khaliq_2024_vladbuff.txt)
| [Revisit Anything: Visual Place Recognition via Image Segment Retrieval](https://arxiv.org/abs/2409.18049) | Kartik Garg | ECCV 2024 | [GitHub](https://github.com/AnyLoc/Revisit-Anything) | [Bibtex](./citations/Garg_2024_revisitanything.txt)
| [Optimal Transport Aggregation for Visual Place Recognition](https://arxiv.org/abs/2311.15937) | Sergio Izquierdo | CVPR 2024 | [GitHub](https://github.com/serizba/salad) | [BibTex](./citations/Izquierdo_2024_salad.txt) |
| [CricaVPR: Cross-image Correlation-aware Representation Learning for Visual Place Recognition](https://arxiv.org/abs/2402.19231) | Feng Lu | CVPR 2024 | [GitHub](https://github.com/Lu-Feng/CricaVPR) | [BibTex](./citations/Lu_2024_CricaVPR.txt) |
| [EigenPlaces: Training Viewpoint Robust Models for Visual Place Recognition](https://arxiv.org/abs/2308.10832) | Gabriele Berton | ICCV 2023 | [GitHub](https://github.com/gmberton/EigenPlaces) | [BibTex](./citations/Berton_2023_EigenPlaces.txt) |
| [AnyLoc: Towards Universal Visual Place Recognition](https://anyloc.github.io/) | Nikhil Keetha | ArXiv 2023 | [GitHub](https://github.com/AnyLoc/AnyLoc) | [BibTex](./citations/Keetha_2023_AnyLoc.txt) |
| [MixVPR: Feature Mixing for Visual Place Recognition](https://arxiv.org/abs/2303.02190) | Ali-bey Amar | WACV 2023 | [GitHub](https://github.com/amaralibey/MixVPR) | [BibTex](./citations/Alibey_2023_mixvpr.txt) |
| [Data-efficient Large Scale Place Recognition with Graded Similarity Supervision](https://arxiv.org/abs/2303.11739) | María Leyva-Vallina | CVPR 2023 | [GitHub](https://github.com/marialeyvallina/generalized_contrastive_loss) | [BibTex](./citations/Leyvavallina_2021_gcl.txt) |
| [Rethinking Visual Geo-localization for Large-Scale Applications](https://arxiv.org/abs/2204.02287) | Berton Gabriele | CVPR 2022 | [GitHub](https://github.com/gmberton/CosPlace) | [BibTex](./citations/Berton_2022_cosPlace.txt) |
| [GSV-Cities: Toward appropriate supervised visual place recognition](https://arxiv.org/abs/2210.10239) | Ali-bey Amar | Neurocomputing 2022 | [GitHub](https://github.com/amaralibey/gsv-cities) | [BibTex](./citations/Alibey_2022_gsvcities.txt) |
| [Learning Semantics for Visual Place Recognition through Multi-Scale Attention](https://arxiv.org/abs/2201.09701) | Valerio Paolicelli | ICIAP 2022 | [GitHub](https://github.com/valeriopaolicelli/SegVPR) | [BibTex](./citations/Paolicelli_2022_Semantic_VPR.txt) |
| [Attentional Pyramid Pooling of Salient Visual Residuals for Place Recognition](https://openaccess.thecvf.com/content/ICCV2021/papers/Peng_Attentional_Pyramid_Pooling_of_Salient_Visual_Residuals_for_Place_Recognition_ICCV_2021_paper.pdf) | Peng Guohao | ICCV 2021 |  | [BibTex](./citations/Peng_2021_appsvr.txt) |
| [Vector of Locally and Adaptively Aggregated Descriptors for Image Feature Representation](https://www.sciencedirect.com/science/article/abs/pii/S0031320321001394) | Jian Zhang | PR 2021 |  | [BibTex](./citations/Zhang_2021_gated_netvlad.txt) |
| [Semantic Reinforced Attention Learning for Visual Place Recognition](https://arxiv.org/abs/2108.08443) | Guohao Peng | ICRA 2021 |  | [BibTex](./citations/Peng_2021_sralNet.txt) |
| [Self-supervising Fine-Grained Region Similarities for Large-Scale Image Localization](https://arxiv.org/abs/2006.03926) | Ge Yixiao | ECCV 2020 | [GitHub](https://github.com/yxgeee/OpenIBL) | [BibTex](./citations/Ge_2020_sfrs.txt) |
| [Stochastic Attraction-Repulsion Embedding for Large Scale Image Localization](https://arxiv.org/abs/1808.08779) | Liu Liu | ICCV 2019 |  | [BibTex](./citations/Liu_2019_sare.txt) |
| [Attention-based Pyramid Aggregation Network for Visual Place Recognition](https://arxiv.org/abs/1808.00288) | Yingying Zhu | ACM MM 2018 |  | [BibTex](./citations/Zhu_2018_apanet.txt) |
| [Learned Contextual Feature Reweighting for Image Geo-Localization](https://openaccess.thecvf.com/content_cvpr_2017/papers/Kim_Learned_Contextual_Feature_CVPR_2017_paper.pdf) | Kim Hyo Jin | CVPR 2017 |  | [BibTex](./citations/Kim_2017_crn.txt) |
| [NetVLAD: CNN architecture for weakly supervised place recognition](https://arxiv.org/abs/1511.07247) | Relja Arandjelović | CVPR 2016 | [GitHub](https://github.com/Relja/netvlad) | [BibTex](./citations/Arandjelovic_2016_NetVLAD.txt) |
| [Visual Place Recognition with Repetitive Structures](https://openaccess.thecvf.com/content_cvpr_2013/papers/Torii_Visual_Place_Recognition_2013_CVPR_paper.pdf) | A. Torii | PAMI 2015 |  | [BibTex](./citations/Torii_2015_pitts250k.txt) |
| [Learning and Calibrating Per-Location Classifiers for Visual Place Recognition](https://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Gronat_Learning_and_Calibrating_2013_CVPR_paper.pdf) | Gronat Petr | CVPR 2013 |  | [BibTex](./citations/Gronat_2013_cvpr_pitts.txt) |

</details>


<details open>
<summary>VPR Datasets</summary>

| Title | First Author | Venue | Github | Bibtex |
|---|---|---|---|---|
| [Rethinking Visual Geo-localization for Large-Scale Applications](https://arxiv.org/abs/2204.02287) | Berton Gabriele | CVPR 2022 | [GitHub](https://github.com/gmberton/CosPlace) | [BibTex](./citations/Berton_2022_cosPlace.txt) |
| [GSV-Cities: Toward appropriate supervised visual place recognition](https://arxiv.org/abs/2210.10239) | Ali-bey Amar | Neurocomputing 2022 | [GitHub](https://github.com/amaralibey/gsv-cities) | [BibTex](./citations/Alibey_2022_gsvcities.txt) |
| [AmsterTime: A Visual Place Recognition Benchmark Dataset for Severe Domain Shift](https://arxiv.org/abs/2203.16291) | B. Yildiz | ICPR 2022 |  | [BibTex](./citations/Yildiz_2022_AmsterTime.txt) |
| [Adaptive-Attentive Geolocalization From Few Queries: A Hybrid Approach](https://arxiv.org/abs/2010.06897) | Berton Gabriele | WACV 2021 | [GitHub](https://github.com/valeriopaolicelli/adageo-pytorch) | [BibTex](./citations/Berton_2021_svox.txt) |
| [Google Landmarks Dataset v2 – A Large-Scale Benchmark for Instance-Level Recognition and Retrieval](https://arxiv.org/abs/2004.01804) | Tobias Weyand | CVPR 2020 | [GitHub](https://github.com/cvdfoundation/google-landmark) | [BibTex](./citations/Weyand_2020_gldv2.txt) |
| [Mapillary Street-Level Sequences: A Dataset for Lifelong Place Recognition](https://openaccess.thecvf.com/content_CVPR_2020/papers/Warburg_Mapillary_Street-Level_Sequences_A_Dataset_for_Lifelong_Place_Recognition_CVPR_2020_paper.pdf) | Warburg Frederik | CVPR 2020 | [GitHub](https://github.com/mapillary/mapillary_sls) | [BibTex](./citations/Warburg_2020_msls.txt) |
| [24/7 Place Recognition by View Synthesis](https://openaccess.thecvf.com/content_cvpr_2015/papers/Torii_247_Place_Recognition_2015_CVPR_paper.pdf) | A. Torii | PAMI 2018 |  | [BibTex](./citations/Torii_2018_tokyo247.txt) |
| [Benchmarking 6DOF Outdoor Visual Localization in Changing Conditions](https://arxiv.org/abs/1707.09092) | T. Sattler | cvpr 2018 |  | [BibTex](./citations/Sattler_2018_aachen_daynight.txt) |
| [1 Year, 1000km: The Oxford RobotCar Dataset](https://robotcar-dataset.robots.ox.ac.uk/images/robotcar_ijrr.pdf) | W. Maddern | IJRR 2017 | [website](https://oxford-robotics-institute.github.io/radar-robotcar-dataset/) |  | [BibTex](./citations/Maddern_2017_robotCar.txt) |
| [The SYNTHIA Dataset: A Large Collection of Synthetic Images for Semantic Segmentation of Urban Scenes](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Ros_The_SYNTHIA_Dataset_CVPR_2016_paper.pdf) | G. Ros | cvpr 2016 |  | [BibTex](./citations/Ros_2016_synthia.txt) |
| [University of Michigan North Campus long-term vision and lidar dataset](http://robots.engin.umich.edu/nclt/nclt.pdf) | N. Carlevaris-Bianco | ijrr 2016 | [webisite](http://robots.engin.umich.edu/nclt/) |  | [BibTex](./citations/CarlevarisBianco_2016_nclt.txt) |
| [Image Geo-localization Based on Multiple Nearest Neighbor Feature Matching using Generalized Graphs](https://www.crcv.ucf.edu/papers/PAMI_Amir%20Zamir.pdf) | Zamir A.R. | PAMI 2014 | [website](https://www.crcv.ucf.edu/projects/GMCP_Geolocalization/) |  | [BibTex](./citations/Zamir_2014_102k_streetview.txt) |
| [Vision meets robotics: The KITTI dataset](https://www.cvlibs.net/publications/Geiger2013IJRR.pdf) | A Geiger | IJRR 2013 | [website](https://www.cvlibs.net/datasets/kitti/) |  | [BibTex](./citations/Geiger_2013_kitti.txt) |
| [Are we there yet? Challenging SeqSLAM on a 3000 km journey across all four seasons](https://www.researchgate.net/publication/283623386_Are_we_there_yet_challenging_SeqSLAM_on_a_3000_km_journey_across_all_four_seasons) | N. Suenderhauf | ICRAW 2013 |  | [BibTex](./citations/Sunderhauf_2013_nordland.txt) |
| [Image retrieval for image-based localization revisited](https://www.graphics.rwth-aachen.de/media/papers/sattler_weyand_bmvc12.pdf) | Torsten Sattler | cvpr 2012 |  | [BibTex](./citations/Sattler_2012_aachen.txt) |
| [City-scale landmark identification on mobile devices](https://ieeexplore.ieee.org/document/5995610) | D. M. Chen | CVPR 2011 |  | [BibTex](./citations/Chen_2011_san_francisco_landmark.txt) |
| [Avoiding confusing features in place recognition](https://www.researchgate.net/publication/221304796_Avoiding_Confusing_Features_in_Place_Recognition) | Knopp J. | ECCV 2010 |  | [BibTex](./citations/Knopp_2010_geotagged_streetview.txt) |
| [Highly scalable appearance-only SLAM - FAB-MAP 2.0](https://www.roboticsproceedings.org/rss05/p39.pdf) | M. Cummins | RSS 2009 |  | [BibTex](./citations/Cummins_2009_eynsham.txt) |
| [Mapping a Suburb With a Single Camera Using a Biologically Inspired SLAM System](https://www.researchgate.net/publication/224329582_Mapping_a_Suburb_With_a_Single_Camera_Using_a_Biologically_Inspired_SLAM_System) | Michael Milford | TRO 2008 |  | [BibTex](./citations/Milford_2008_st_lucia.txt) |

</details>

<details open>
<summary>Uncertainty estimation in VPR</summary>

| Title | First Author | Venue | Github | Bibtex |
|---|---|---|---|---|
| [To Match or Not to Match: Revisiting Image Matching for Reliable Visual Place Recognition](https://arxiv.org/abs/2504.06116) | Davide Sferrazza | ArXiv 2025 | [GitHub](https://github.com/FarInHeight/To-Match-or-Not-to-Match) | [BibTex](./citations/Sferrazza_2025_match.txt) |
| [On the Estimation of Image-matching Uncertainty in Visual Place Recognition](https://arxiv.org/abs/2404.00546) | Mubariz Zaffar | CVPR 2024 | [GitHub](https://github.com/MubarizZaffar/SUE) | [BibTex](./citations/Zaffar_2024_estimation.txt) |
| [STUN: Self-Teaching Uncertainty Estimation for Place Recognition](https://arxiv.org/abs/2203.01851) | Kaiwen Cai | IROS 2022 | [GitHub](https://github.com/ramdrop/stun) | [BibTex](./citations/Cai_2022_stun.txt) |
| [Bayesian Triplet Loss: Uncertainty Quantification in Image Retrieval](https://arxiv.org/abs/2011.12663) | Frederik Warburg | ICCV 2021 |  | [BibTex](./citations/Warburg_2021_bayesian.txt) |


</details>

<details open>
<summary>Cross-domain VPR</summary>

| Title | First Author | Venue | Github | Bibtex |
|---|---|---|---|---|
| [Adaptive-Attentive Geolocalization From Few Queries: A Hybrid Approach](https://arxiv.org/abs/2010.06897) | Berton Gabriele | WACV 2021 | [GitHub](https://github.com/valeriopaolicelli/adageo-pytorch) | [BibTex](./citations/Berton_2021_svox.txt) |
| [Inside Out Visual Place Recognition](https://arxiv.org/abs/2111.13546) | Sarah Ibrahimi | BMVC 2021 | [GitHub](https://github.com/saibr/IOVPR) | [BibTex](./citations/Ibrahimi_2021_insideout_vpr.txt) |
| [Night-to-day image translation for retrieval-based localization](https://arxiv.org/abs/1809.09767) | Anoosheh Asha | ICRA 2019 |  | [BibTex](./citations/Asha_2019_todaygan.txt) |
| [Attention-Aware Age-Agnostic Visual Place Recognition](https://arxiv.org/abs/1909.05163) | Ziqi Wang | ICCVW 2019 |  | [BibTex](./citations/Wang_2019_ageAgnosticVPR.txt) |
| [Lazy Data Association For Image Sequences Matching Under Substantial Appearance Changes](https://www.ipb.uni-bonn.de/pdfs/vysotska16ral-icra.pdf) | Olga Vysotska | RAL 2016 |  | [BibTex](./citations/Vysotska_2016_sequences_matching.txt) |

</details>


<details open>
<summary>Sequence-based VPR</summary>

| Title | First Author | Venue | Github | Bibtex |
|---|---|---|---|---|
| [Learning Sequence Descriptor based on Spatio-Temporal Attention for Visual Place Recognition](https://arxiv.org/abs/2305.11467) | Fenglin Zhang | ArXiv 2023 |  | [BibTex](./citations/Zhang_2023_SpatioTemporalAttention.txt) |
| [MATC-Net: Learning compact sequence representation for hierarchical loop closure detection](https://www.sciencedirect.com/science/article/abs/pii/S0952197623009181) | Fuji Fu | 2023 |  | [BibTex](./citations/Fu_2023_matc_net.txt) |
| [Learning Sequential Descriptors for Sequence-Based Visual Place Recognition](https://arxiv.org/abs/2207.03868) | Riccardo Mereu | RAL 2022 | [GitHub](https://github.com/vandal-vpr/vg-transformers) | [BibTex](./citations/Mereu_2022_SeqVLAD.txt) |
| [SeqNet: Learning Descriptors for Sequence-based Hierarchical Place Recognition](https://arxiv.org/abs/2102.11603) | Sourav Garg | RAL 2021 | [GitHub](https://github.com/oravus/seqNet) | [BibTex](./citations/Garg_2021_SeqNet.txt) |
| [Fast and Memory Efficient Graph Optimization via ICM for Visual Place Recognition](https://www.roboticsproceedings.org/rss17/p091.pdf) | Stefan Schubert | RSS 2021 |  | [BibTex](./citations/Schubert_2021_graph_optimization.txt) |
| [SeqSLAM: Visual route-based navigation for sunny summer days and stormy winter nights](https://ieeexplore.ieee.org/document/6224623) | Michael Milford | ICRA 2012 |  | [BibTex](./citations/Milford_2012_SeqSLAM.txt) |

</details>


<details open>
<summary>Re-ranking</summary>

| Title | First Author | Venue | Github | Bibtex |
|---|---|---|---|---|
| [SelaVPR++: Towards Seamless Adaptation of Foundation Models for Efficient Place Recognition](https://arxiv.org/abs/2502.16601) | Feng Lu | | [GitHub](https://github.com/Lu-Feng/SelaVPR) | [BibTex](./citations/Lu_2025_SelaVPRpp.txt) |
| [Pair-VPR: Place-Aware Pre-training and Contrastive Pair Classification for Visual Place Recognition with Vision Transformers](http://arxiv.org/abs/2410.06614) | Stephen Hausler | IEEE RA-L 2025 | [GitHub](https://github.com/csiro-robotics/Pair-VPR) | [BibTex](./citations/Hausler_2025_PairVPR.txt) | [BibTex](./citations/Hausler_2025_PairVPR.txt)
| [Towards Seamless Adaptation of Pre-trained Models for Visual Place Recognition](https://arxiv.org/abs/2402.14505) | Feng Lu | ICLR 2024 | [GitHub](https://github.com/Lu-Feng/SelaVPR) | [BibTex](./citations/Lu_2024_SelaVPR.txt) |
| [Are Local Features All You Need for Cross-Domain Visual Place Recognition?](https://arxiv.org/abs/2304.05887) | Giovanni Barbarani | CVPRW 2023 | [GitHub](https://github.com/gbarbarani/re-ranking-for-VPR) | [BibTex](./citations/Barbarani_2023_reranking_benchmark.txt) |
| [R2former: Unified retrieval and reranking transformer for place recognition](https://arxiv.org/abs/2304.03410) | Sijie Zhu | CVPR 2023 | [GitHub](https://github.com/bytedance/R2Former) | [BibTex](./citations/Zhu_2023_R2Former.txt) |
| [TransVPR: Transformer-Based Place Recognition With Multi-Level Attention Aggregation](https://arxiv.org/abs/2201.02001) | Wang Ruotong | CVPR 2022 |  | [BibTex](./citations/Wang_2022_TransVPR.txt) |
| [Correlation Verification for Image Retrieval](https://arxiv.org/abs/2204.01458) | Lee Seongwon | CVPR 2022 | [GitHub](https://github.com/sungonce/CVNet) | [BibTex](./citations/Lee_2022_cvnet.txt) |
| [Viewpoint Invariant Dense Matching for Visual Geolocalization](https://arxiv.org/abs/2109.09827) | Berton Gabriele | ICCV 2021 | [GitHub](https://github.com/gmberton/geo_warp) | [BibTex](./citations/Berton_2021_geowarp.txt) |
| [Patch-NetVLAD: Multi-Scale Fusion of Locally-Global Descriptors for Place Recognition](https://arxiv.org/abs/2103.01486) | Hausler Stephen | CVPR 2021 | [GitHub](https://github.com/QVPR/Patch-NetVLAD) | [BibTex](./citations/Hausler_2021_patch_netvlad.txt) |
| [LoFTR: Detector-Free Local Feature Matching with Transformers](https://arxiv.org/abs/2104.00680) | Sun Jiaming | CVPR 2021 | [GitHub](https://github.com/zju3dv/LoFTR) | [BibTex](./citations/Sun_2021_loftr.txt) |
| [Instance-level Image Retrieval using Reranking Transformers](https://arxiv.org/abs/2103.12236) | Fuwen Tan | ICCV 2021 | [GitHub](https://github.com/uvavision/RerankingTransformer) | [BibTex](./citations/Fuwen_2021_reranking_transformers.txt) |
| [DenserNet: Weakly Supervised Visual Localization Using Multi-scale Feature Aggregation](https://arxiv.org/abs/2012.02366) | Liu Dongfang | AAAI 2021 |  | [BibTex](./citations/Liu_2021_densernet.txt) |
| [Unifying Deep Local and Global Features for Image Search](https://arxiv.org/abs/2001.05027) | B. Cao | eccv 2020 |  | [BibTex](./citations/Cao_2020_delg.txt) |
| [SuperGlue: Learning Feature Matching with Graph Neural Networks](https://arxiv.org/abs/1911.11763) | Paul-Edouard Sarlin and | CVPR 2020 | [GitHub](https://github.com/magicleap/SuperGluePretrainedNetwork) | [BibTex](./citations/Sarlin_2020_superglue.txt) |
| [R2D2: Repeatable and Reliable Detector and Descriptor](https://arxiv.org/abs/1906.06195) | Jerome Revaud | NIPS 2019 | [GitHub](https://github.com/naver/r2d2) | [BibTex](./citations/Revaud_2019_r2d2.txt) |
| [D2-Net: A Trainable CNN for Joint Detection and Description of Local Features](https://arxiv.org/abs/1905.03561) | Dusmanu Mihai | CVPR 2019 | [GitHub](https://github.com/mihaidusmanu/d2-net) | [BibTex](./citations/Dusmanu_2019_D2Net.txt) |
| [Large-Scale Image Retrieval with Attentive Deep Local Features](https://arxiv.org/abs/1612.06321) | Noh Hyeonwoo | ICCV 2017 |  | [BibTex](./citations/Noh_2017_delf.txt) |

</details>


<details open>
<summary>Benchmarks</summary>

| Title | First Author | Venue | Github | Bibtex |
|---|---|---|---|---|
| [Are Local Features All You Need for Cross-Domain Visual Place Recognition?](https://arxiv.org/abs/2304.05887) | Giovanni Barbarani | CVPRW 2023 | [GitHub](https://github.com/gbarbarani/re-ranking-for-VPR) | [BibTex](./citations/Barbarani_2023_reranking_benchmark.txt) |
| [Deep Visual Geo-localization Benchmark](https://arxiv.org/abs/2204.03444) | Berton Gabriele | CVPR 2022 | [GitHub](https://github.com/gmberton/deep-visual-geo-localization-benchmark) | [BibTex](./citations/Berton_2022_benchmark_berton.txt) |
| [VPR-Bench: An Open-Source Visual Place Recognition Evaluation Framework with Quantifiable Viewpoint and Appearance Change](https://arxiv.org/abs/2005.08135) | Zaffar Mubariz | IJCV 2021 | [GitHub](https://github.com/MubarizZaffar/VPR-Bench) | [BibTex](./citations/Zaffar_2021_vprbench.txt) |
| [Benchmarking Image Retrieval for Visual Localization](https://arxiv.org/abs/2011.11946) | Pion Noe | 3DV 2020 |  | [BibTex](./citations/Pion_2020_benchmark_VisLoc.txt) |
| [Benchmarking 6DOF Outdoor Visual Localization in Changing Conditions](https://arxiv.org/abs/1707.09092) | T. Sattler | cvpr 2018 |  | [BibTex](./citations/Sattler_2018_aachen_daynight.txt) |

</details>


<details open>
<summary>World-wide Geo-Localization</summary>

| Title | First Author | Venue | Github | Bibtex |
|---|---|---|---|---|
| [PIGEON: Predicting Image Geolocations](https://arxiv.org/abs/2307.05845) | Lukas Haas | CVPR 2024 | [GitHub](https://github.com/LukasHaas/PIGEON) | [BibTex](./citations/Haas_2024_pigeon.txt) |
| [OpenStreetView-5M: The Many Roads to Global Visual Geolocation](https://arxiv.org/abs/2404.18873) | Guillaume Astruc | CVPR 2024 | [GitHub](https://github.com/gastruc/osv5m) | [BibTex](./citations/Gastruc_2024_OSV5M.txt) |
| [GeoCLIP: Clip-Inspired Alignment between Locations and Images for Effective Worldwide Geo-localization](https://arxiv.org/abs/2309.16020) | Vicente Vivanco Cepeda | NeurIPS 2023 | [GitHub](https://github.com/VicenteVivan/geo-clip) | [BibTex](./citations/Cepeda_2023_GeoCLIP.txt) |
| [Where We Are and What We're Looking At: Query Based Worldwide Image Geo-localization Using Hierarchies and Scenes](https://arxiv.org/abs/2303.04249) | Brandon Clark | CVPR 2023 | [GitHub](https://github.com/AHKerrigan/GeoGuessNet) | [BibTex](./citations/Clark_2023_GeoGuessNet.txt) |
| [Interpretable Semantic Photo Geolocation](https://arxiv.org/abs/2104.14995) | Theiner Jonas | WACV 2022 | [GitHub](https://github.com/jtheiner/semantic_geo_partitioning) | [BibTex](./citations/Theiner_2022_WACV.txt) |
| [Where in the World is this Image? Transformer-based Geo-localization in the Wild](https://arxiv.org/abs/2204.13861) | Pramanick Shraman | ECCV 2022 | [GitHub](https://github.com/ShramanPramanick/Transformer_Based_Geo-localization) | [BibTex](./citations/Pramanick_2022_transformer_geoloc.txt) |
| [Leveraging EfficientNet and Contrastive Learning for Accurate Global-scale Location Estimation](https://arxiv.org/abs/2105.07645) | Giorgos Kordopatis-Zilos | ICMR 2021 | [GitHub](https://github.com/mever-team/visloc-estimation) | [BibTex](./citations/Kordopatis_2021_EfficientNetGeoloc.txt) |
| [Geolocation Estimation of Photos Using a Hierarchical Model and Scene Classification](https://openaccess.thecvf.com/content_ECCV_2018/papers/Eric_Muller-Budack_Geolocation_Estimation_of_ECCV_2018_paper.pdf) | Muller-Budack Eric | ECCV 2018 | [GitHub](https://github.com/TIBHannover/GeoEstimation) | [BibTex](./citations/Muller_2018_hierarchical_geolocation.txt) |
| [CPlaNet: Enhancing Image Geolocalization by Combinatorial Partitioning of Maps](https://arxiv.org/abs/1808.02130) | Paul Hongsuck Seo | ECCV 2018 |  | [BibTex](./citations/Seo_2018_CPlaNet.txt) |
| [Revisiting IM2GPS in the Deep Learning Era](https://arxiv.org/abs/1705.04838) | Vo Nam | ICCV 2017 |  | [BibTex](./citations/Vo_2017_revIm2GPS.txt) |
| [PlaNet - Photo Geolocation with Convolutional Neural Networks](https://arxiv.org/abs/1602.05314) | Tobias Weyand | ECCV 2016 |  | [BibTex](./citations/Weyand_2016_PlaNet.txt) |
| [IM2GPS: estimating geographic information from a single image](http://graphics.cs.cmu.edu/projects/im2gps/im2gps.pdf) | James Hays | CVPR 2008 |  | [BibTex](./citations/Hays_2008_im2gps.txt) |

</details>


<details open>
<summary>Others</summary>

| Title | First Author | Venue | Github | Bibtex |
|---|---|---|---|---|
| [MeshVPR: Citywide Visual Place Recognition Using 3D Meshes](https://arxiv.org/abs/2406.02776) | Gabriele Berton | ECCV 2024 | [GitHub](https://github.com/gmberton/MeshVPR) | [Bibtex](./citations/Berton_2024_meshvpr.txt)
| [Divide&Classify: Fine-Grained Classification for City-Wide Visual Geo-localization](https://arxiv.org/abs/2307.08417) | Gabriele Trivigno | ICCV 2023 | [GitHub](https://github.com/ga1i13o/Divide-and-Classify) | [BibTex](./citations/Trivigno_2023_DivideClassify.txt) |
| [Unifying Visual Localization and Scene Recognition for People With Visual Impairment](https://www.researchgate.net/publication/340327129_Unifying_Visual_Localization_and_Scene_Recognition_for_People_With_Visual_Impairment) | R. Cheng | IEEE Access 2020 |  | [BibTex](./citations/Cheng_2020_Unifying.txt) |
| [Scalable Place Recognition Under Appearance Change for Autonomous Driving](https://arxiv.org/abs/1908.00178) | A. D. Doan | ICCV 2019 |  | [BibTex](./citations/Doan_2019_scalable.txt) |
| [Multi-Process Fusion: Visual Place Recognition Using Multiple Image Processing Methods](https://arxiv.org/abs/1903.03305) | S. Hausler | ral 2019 | [GitHub](https://github.com/StephenHausler/Multi-Process-Fusion) | [BibTex](./citations/Hausler_2019_fusion.txt) |
| [Semantic–geometric visual place recognition: a new perspective for reconciling opposing views](https://www.researchgate.net/publication/332280264_Semantic-geometric_visual_place_recognition_a_new_perspective_for_reconciling_opposing_views) | S. Garg | IJRR 2019 |  | [BibTex](./citations/Garg_2019_semanticGeometric.txt) |
| [Are Large-Scale 3D Models Really Necessary for Accurate Visual Localization?](https://openaccess.thecvf.com/content_cvpr_2017/papers/Sattler_Are_Large-Scale_3D_CVPR_2017_paper.pdf) | A. Torii | PAMI 2021 |  | [BibTex](./citations/Torii_2021_large_scale3D.txt) |

</details>



## Talks

- [Benchmarking urban visual geo-localization](https://www.youtube.com/watch?v=snxP0yrabnQ), Carlo Masone, CVPR 2023
- [Urban visual geo-localization: towards large-scale applications](https://youtu.be/snxP0yrabnQ?si=2R_wH9SCE_90-P-b&t=1629), Gabriele Berton, CVPR 2023
- [Large-Scale Visual Localization](https://www.youtube.com/watch?v=RaVPiIGhdWk), Giorgos Tolias, Yannis Avrithis, Zuzana Kukelova, Torsten Sattler, Sudipta n: Sinha, Eric Brachmann, ICCV 2021
- [General Place Recognition Competition](https://www.youtube.com/watch?v=xpEKOyJ7OIU), Yimin Zhang, Luca Carlone, Michael Milford, Junyan Zhu, Ji Zhang, Sebastian Scherer, ICRA 2022
- [Tutorial : Large-Scale Visual Place Recognition and Image-Based Localization Part 1](https://www.youtube.com/watch?v=GDMLjzbEth8), Akihiko Torii, Giorgos Tolias, CVPR 2017
- [Tutorial : Large-Scale Visual Place Recognition and Image-Based Localization Part 2](https://www.youtube.com/watch?v=947W99gAvQ8), Torsten Sattler, Alex Kendall, CVPR 2017



## License 
MIT
