# Awesome Visual Place Recognition [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of papers on Visual Place Recognition and related fields, inspired by [awesome-NeRF](https://github.com/awesome-NeRF/awesome-NeRF).
PRs are very much appreciated.

#### [How to submit a pull request?](https://github.com/gmberton/awesome-Visual-Place-Recognition/blob/main/how-to-PR.md)



## Table of Contents

- [Surveys](#surveys) 
- [Papers](#papers)
- [Talks](#talks)



## Surveys

- [Place recognition survey: An update on deep learning approaches](https://arxiv.org/abs/2106.10458), Tiago Barros et al., ArXiv 2022 | [bibtex](citations/Barros_2022_Survey.txt)
- [General Place Recognition Survey: Towards the Real-world Autonomy Age](https://arxiv.org/abs/2209.04497), Peng Yin et al., ArXiv 2022 | [bibtex](citations/Yin_2022_GeneralPR.txt)
- [A Survey on Deep Visual Place Recognition](https://ieeexplore.ieee.org/document/9336674), Carlo Masone et al., IEEE Access 2021 | [bibtex](citations/Masone_2021_survey.txt)
- [Visual place recognition: A survey from deep learning perspective](https://www.sciencedirect.com/science/article/abs/pii/S003132032030563X), Xiwu Zhang et al., Pattern Recognition 2021 | [bibtex](citations/Zhang_2021_Survey.txt)
- [Where is your place, Visual Place Recognition?](https://arxiv.org/abs/2103.06443), Sourav Garg et al., IJCAI 2021 | [bibtex](citations/Garg_2021_Survey.txt)
- [Visual Place Recognition: A Survey](https://ieeexplore.ieee.org/document/7339473), Stephanie Lowry et al., IEEE Transactions on Robotics 2016 | [bibtex](citations/Lowry_2016_Survey.txt)



## Papers

Papers are roughly split into categories, and a paper can (rarely) appear in more than one category.

<details open>
<summary>Standard VPR</summary>

- [EigenPlaces: Training Viewpoint Robust Models for Visual Place Recognition](https://arxiv.org/abs/2308.10832), Gabriele Berton et al., ICCV 2023 | [github](https://github.com/gmberton/EigenPlaces) | [bibtex](./citations/Berton_2023_EigenPlaces.txt)
- [AnyLoc: Towards Universal Visual Place Recognition](https://anyloc.github.io/), Nikhil Keetha et al., ArXiv 2023 | [github](https://github.com/AnyLoc/AnyLoc) | [bibtex](./citations/Keetha_2023_AnyLoc.txt)
- [MixVPR: Feature Mixing for Visual Place Recognition](https://arxiv.org/abs/2303.02190), Ali-bey Amar et al., WACV 2023 | [github](https://github.com/amaralibey/MixVPR) | [bibtex](./citations/Alibey_2023_mixvpr.txt)
- [Data-efficient Large Scale Place Recognition with Graded Similarity Supervision](https://arxiv.org/abs/2303.11739), María Leyva-Vallina et al., CVPR 2023 | [github](https://github.com/marialeyvallina/generalized_contrastive_loss) | [bibtex](./citations/Leyvavallina_2021_gcl.txt)
- [Rethinking Visual Geo-localization for Large-Scale Applications](https://arxiv.org/abs/2204.02287), Berton Gabriele et al., CVPR 2022 | [github](https://github.com/gmberton/CosPlace) | [bibtex](./citations/Berton_2022_cosPlace.txt)
- [GSV-Cities: Toward appropriate supervised visual place recognition](https://arxiv.org/abs/2210.10239), Ali-bey Amar et al., Neurocomputing 2022 | [github](https://github.com/amaralibey/gsv-cities) | [bibtex](./citations/Alibey_2022_gsvcities.txt)
- [Learning Semantics for Visual Place Recognition through Multi-Scale Attention](https://arxiv.org/abs/2201.09701), Valerio Paolicelli et al., ICIAP 2022 | [github](https://github.com/valeriopaolicelli/SegVPR) | [bibtex](./citations/Paolicelli_2022_Semantic_VPR.txt)
- [Attentional Pyramid Pooling of Salient Visual Residuals for Place Recognition](https://openaccess.thecvf.com/content/ICCV2021/papers/Peng_Attentional_Pyramid_Pooling_of_Salient_Visual_Residuals_for_Place_Recognition_ICCV_2021_paper.pdf), Peng Guohao et al., ICCV 2021 | [bibtex](./citations/Peng_2021_appsvr.txt)
- [Vector of Locally and Adaptively Aggregated Descriptors for Image Feature Representation](https://www.sciencedirect.com/science/article/abs/pii/S0031320321001394), Jian Zhang et al., PR 2021 | [bibtex](./citations/Zhang_2021_gated_netvlad.txt)
- [Semantic Reinforced Attention Learning for Visual Place Recognition](https://arxiv.org/abs/2108.08443), Guohao Peng et al., ICRA 2021 | [bibtex](./citations/Peng_2021_sralNet.txt)
- [Self-supervising Fine-Grained Region Similarities for Large-Scale Image Localization](https://arxiv.org/abs/2006.03926), Ge Yixiao et al., ECCV 2020 | [github](https://github.com/yxgeee/OpenIBL) | [bibtex](./citations/Ge_2020_sfrs.txt)
- [Stochastic Attraction-Repulsion Embedding for Large Scale Image Localization](https://arxiv.org/abs/1808.08779), Liu Liu et al., ICCV 2019 | [bibtex](./citations/Liu_2019_sare.txt)
- [Attention-based Pyramid Aggregation Network for Visual Place Recognition](https://arxiv.org/abs/1808.00288), Yingying Zhu et al., ACM MM 2018 | [bibtex](./citations/Zhu_2018_apanet.txt)
- [Learned Contextual Feature Reweighting for Image Geo-Localization](https://openaccess.thecvf.com/content_cvpr_2017/papers/Kim_Learned_Contextual_Feature_CVPR_2017_paper.pdf), Kim Hyo Jin et al., CVPR 2017 | [bibtex](./citations/Kim_2017_crn.txt)
- [NetVLAD: CNN architecture for weakly supervised place recognition](https://arxiv.org/abs/1511.07247), Relja Arandjelović et al., CVPR 2016 | [github](https://github.com/Relja/netvlad) | [bibtex](./citations/Arandjelovic_2016_NetVLAD.txt)
- [Visual Place Recognition with Repetitive Structures](https://openaccess.thecvf.com/content_cvpr_2013/papers/Torii_Visual_Place_Recognition_2013_CVPR_paper.pdf), A. Torii et al., PAMI 2015 | [bibtex](./citations/Torii_2015_pitts250k.txt)
- [Learning and Calibrating Per-Location Classifiers for Visual Place Recognition](https://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Gronat_Learning_and_Calibrating_2013_CVPR_paper.pdf), Gronat Petr et al., CVPR 2013 | [bibtex](./citations/Gronat_2013_cvpr_pitts.txt)

</details>


<details open>
<summary>VPR Datasets</summary>

- [Rethinking Visual Geo-localization for Large-Scale Applications](https://arxiv.org/abs/2204.02287), Berton Gabriele et al., CVPR 2022 | [github](https://github.com/gmberton/CosPlace) | [bibtex](./citations/Berton_2022_cosPlace.txt)
- [GSV-Cities: Toward appropriate supervised visual place recognition](https://arxiv.org/abs/2210.10239), Ali-bey Amar et al., Neurocomputing 2022 | [github](https://github.com/amaralibey/gsv-cities) | [bibtex](./citations/Alibey_2022_gsvcities.txt)
- [AmsterTime: A Visual Place Recognition Benchmark Dataset for Severe Domain Shift](https://arxiv.org/abs/2203.16291), B. Yildiz et al., ICPR 2022 | [bibtex](./citations/Yildiz_2022_AmsterTime.txt)
- [Adaptive-Attentive Geolocalization From Few Queries: A Hybrid Approach](https://arxiv.org/abs/2010.06897), Berton Gabriele et al., WACV 2021 | [github](https://github.com/valeriopaolicelli/adageo-pytorch) | [bibtex](./citations/Berton_2021_svox.txt)
- [Google Landmarks Dataset v2 – A Large-Scale Benchmark for Instance-Level Recognition and Retrieval](https://arxiv.org/abs/2004.01804), Tobias Weyand et al., CVPR 2020 | [github](https://github.com/cvdfoundation/google-landmark) | [bibtex](./citations/Weyand_2020_gldv2.txt)
- [Mapillary Street-Level Sequences: A Dataset for Lifelong Place Recognition](https://openaccess.thecvf.com/content_CVPR_2020/papers/Warburg_Mapillary_Street-Level_Sequences_A_Dataset_for_Lifelong_Place_Recognition_CVPR_2020_paper.pdf), Warburg Frederik et al., CVPR 2020 | [github](https://github.com/mapillary/mapillary_sls) | [bibtex](./citations/Warburg_2020_msls.txt)
- [24/7 Place Recognition by View Synthesis](https://openaccess.thecvf.com/content_cvpr_2015/papers/Torii_247_Place_Recognition_2015_CVPR_paper.pdf), A. Torii et al., PAMI 2018 | [bibtex](./citations/Torii_2018_tokyo247.txt)
- [Benchmarking 6DOF Outdoor Visual Localization in Changing Conditions](https://arxiv.org/abs/1707.09092), T. Sattler et al., cvpr 2018 | [bibtex](./citations/Sattler_2018_aachen_daynight.txt)
- [1 Year, 1000km: The Oxford RobotCar Dataset](https://robotcar-dataset.robots.ox.ac.uk/images/robotcar_ijrr.pdf), W. Maddern et al., IJRR 2017 | [website](https://oxford-robotics-institute.github.io/radar-robotcar-dataset/) | [bibtex](./citations/Maddern_2017_robotCar.txt)
- [The SYNTHIA Dataset: A Large Collection of Synthetic Images for Semantic Segmentation of Urban Scenes](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Ros_The_SYNTHIA_Dataset_CVPR_2016_paper.pdf), G. Ros et al., cvpr 2016 | [bibtex](./citations/Ros_2016_synthia.txt)
- [University of Michigan North Campus long-term vision and lidar dataset](http://robots.engin.umich.edu/nclt/nclt.pdf), N. Carlevaris-Bianco et al., ijrr 2016 | [webisite](http://robots.engin.umich.edu/nclt/) | [bibtex](./citations/CarlevarisBianco_2016_nclt.txt)
- [Image Geo-localization Based on Multiple Nearest Neighbor Feature Matching using Generalized Graphs](https://www.crcv.ucf.edu/papers/PAMI_Amir%20Zamir.pdf), Zamir A.R. et al., PAMI 2014 | [website](https://www.crcv.ucf.edu/projects/GMCP_Geolocalization/) | [bibtex](./citations/Zamir_2014_102k_streetview.txt)
- [Vision meets robotics: The KITTI dataset](https://www.cvlibs.net/publications/Geiger2013IJRR.pdf), A Geiger et al., IJRR 2013 | [website](https://www.cvlibs.net/datasets/kitti/) | [bibtex](./citations/Geiger_2013_kitti.txt)
- [Are we there yet? Challenging SeqSLAM on a 3000 km journey across all four seasons](https://www.researchgate.net/publication/283623386_Are_we_there_yet_challenging_SeqSLAM_on_a_3000_km_journey_across_all_four_seasons), N. Suenderhauf et al., ICRAW 2013 | [bibtex](./citations/Sunderhauf_2013_nordland.txt)
- [Image retrieval for image-based localization revisited](https://www.graphics.rwth-aachen.de/media/papers/sattler_weyand_bmvc12.pdf), Torsten Sattler et al., cvpr 2012 | [bibtex](./citations/Sattler_2012_aachen.txt)
- [City-scale landmark identification on mobile devices](https://ieeexplore.ieee.org/document/5995610), D. M. Chen et al., CVPR 2011 | [bibtex](./citations/Chen_2011_san_francisco_landmark.txt)
- [Avoiding confusing features in place recognition](https://www.researchgate.net/publication/221304796_Avoiding_Confusing_Features_in_Place_Recognition), Knopp J. et al., ECCV 2010 | [bibtex](./citations/Knopp_2010_geotagged_streetview.txt)
- [Highly scalable appearance-only SLAM - FAB-MAP 2.0](https://www.roboticsproceedings.org/rss05/p39.pdf), M. Cummins et al., RSS 2009 | [bibtex](./citations/Cummins_2009_eynsham.txt)
- [Mapping a Suburb With a Single Camera Using a Biologically Inspired SLAM System](https://www.researchgate.net/publication/224329582_Mapping_a_Suburb_With_a_Single_Camera_Using_a_Biologically_Inspired_SLAM_System), Michael Milford et al., TRO 2008 | [bibtex](./citations/Milford_2008_st_lucia.txt)

</details>


<details open>
<summary>Cross-domain VPR</summary>

- [Adaptive-Attentive Geolocalization From Few Queries: A Hybrid Approach](https://arxiv.org/abs/2010.06897), Berton Gabriele et al., WACV 2021 | [github](https://github.com/valeriopaolicelli/adageo-pytorch) | [bibtex](./citations/Berton_2021_svox.txt)
- [Inside Out Visual Place Recognition](https://arxiv.org/abs/2111.13546), Sarah Ibrahimi et al., BMVC 2021 | [github](https://github.com/saibr/IOVPR) | [bibtex](./citations/Ibrahimi_2021_insideout_vpr.txt)
- [Night-to-day image translation for retrieval-based localization](https://arxiv.org/abs/1809.09767), Anoosheh Asha et al., ICRA 2019 | [bibtex](./citations/Asha_2019_todaygan.txt)
- [Attention-Aware Age-Agnostic Visual Place Recognition](https://arxiv.org/abs/1909.05163), Ziqi Wang et al., ICCVW 2019 | [bibtex](./citations/Wang_2019_ageAgnosticVPR.txt)
- [Lazy Data Association For Image Sequences Matching Under Substantial Appearance Changes](https://www.ipb.uni-bonn.de/pdfs/vysotska16ral-icra.pdf), Olga Vysotska et al., RAL 2016 | [bibtex](./citations/Vysotska_2016_sequences_matching.txt)

</details>


<details open>
<summary>Sequence-based VPR</summary>

- [Learning Sequence Descriptor based on Spatio-Temporal Attention for Visual Place Recognition](https://arxiv.org/abs/2305.11467), Fenglin Zhang et al., ArXiv 2023 | [bibtex](./citations/Zhang_2023_SpatioTemporalAttention.txt)
- [MATC-Net: Learning compact sequence representation for hierarchical loop closure detection](https://www.sciencedirect.com/science/article/abs/pii/S0952197623009181), Fuji Fu et al., 2023 | [bibtex]((./citations/Fu_2023_matc_net.txt)
- [Learning Sequential Descriptors for Sequence-Based Visual Place Recognition](https://arxiv.org/abs/2207.03868), Riccardo Mereu et al., RAL 2022 | [github](https://github.com/vandal-vpr/vg-transformers) | [bibtex](./citations/Mereu_2022_SeqVLAD.txt)
- [SeqNet: Learning Descriptors for Sequence-based Hierarchical Place Recognition](https://arxiv.org/abs/2102.11603), Sourav Garg et al., RAL 2021 | [github](https://github.com/oravus/seqNet) | [bibtex](./citations/Garg_2021_SeqNet.txt)
- [Fast and Memory Efficient Graph Optimization via ICM for Visual Place Recognition](https://www.roboticsproceedings.org/rss17/p091.pdf), Stefan Schubert et al., RSS 2021 | [bibtex](./citations/Schubert_2021_graph_optimization.txt)
- [SeqSLAM: Visual route-based navigation for sunny summer days and stormy winter nights](https://ieeexplore.ieee.org/document/6224623), Michael Milford et al., ICRA 2012 | [bibtex](./citations/Milford_2012_SeqSLAM.txt)

</details>


<details open>
<summary>Re-ranking</summary>

- [Are Local Features All You Need for Cross-Domain Visual Place Recognition?](https://arxiv.org/abs/2304.05887), Giovanni Barbarani et al., CVPRW 2023 | [github](https://github.com/gbarbarani/re-ranking-for-VPR) | [bibtex](./citations/Barbarani_2023_reranking_benchmark.txt)
- [R2former: Unified retrieval and reranking transformer for place recognition](https://arxiv.org/abs/2304.03410), Sijie Zhu et al., CVPR 2023 | [github](https://github.com/bytedance/R2Former) | [bibtex](./citations/Zhu_2023_R2Former.txt)
- [TransVPR: Transformer-Based Place Recognition With Multi-Level Attention Aggregation](https://arxiv.org/abs/2201.02001), Wang Ruotong et al., CVPR 2022 | [bibtex](./citations/Wang_2022_TransVPR.txt)
- [Correlation Verification for Image Retrieval](https://arxiv.org/abs/2204.01458), Lee Seongwon et al., CVPR 2022 | [github](https://github.com/sungonce/CVNet) | [bibtex](./citations/Lee_2022_cvnet.txt)
- [Viewpoint Invariant Dense Matching for Visual Geolocalization](https://arxiv.org/abs/2109.09827), Berton Gabriele et al., ICCV 2021 | [github](https://github.com/gmberton/geo_warp) | [bibtex](./citations/Berton_2021_geowarp.txt)
- [Patch-NetVLAD: Multi-Scale Fusion of Locally-Global Descriptors for Place Recognition](https://arxiv.org/abs/2103.01486), Hausler Stephen et al., CVPR 2021 | [github](https://github.com/QVPR/Patch-NetVLAD) | [bibtex](./citations/Hausler_2021_patch_netvlad.txt)
- [LoFTR: Detector-Free Local Feature Matching with Transformers](https://arxiv.org/abs/2104.00680), Sun Jiaming et al., CVPR 2021 | [github](https://github.com/zju3dv/LoFTR) | [bibtex](./citations/Sun_2021_loftr.txt)
- [Instance-level Image Retrieval using Reranking Transformers](https://arxiv.org/abs/2103.12236), Fuwen Tan et al., ICCV 2021 | [github](https://github.com/uvavision/RerankingTransformer) | [bibtex](./citations/Fuwen_2021_reranking_transformers.txt)
- [DenserNet: Weakly Supervised Visual Localization Using Multi-scale Feature Aggregation](https://arxiv.org/abs/2012.02366), Liu Dongfang et al., AAAI 2021 | [bibtex](./citations/Liu_2021_densernet.txt)
- [Unifying Deep Local and Global Features for Image Search](https://arxiv.org/abs/2001.05027), B. Cao et al., eccv 2020 | [bibtex](./citations/Cao_2020_delg.txt)
- [SuperGlue: Learning Feature Matching with Graph Neural Networks](https://arxiv.org/abs/1911.11763), Paul-Edouard Sarlin and et al., CVPR 2020 | [github](https://github.com/magicleap/SuperGluePretrainedNetwork) | [bibtex](./citations/Sarlin_2020_superglue.txt)
- [R2D2: Repeatable and Reliable Detector and Descriptor](https://arxiv.org/abs/1906.06195), Jerome Revaud et al., NIPS 2019 | [github](https://github.com/naver/r2d2) | [bibtex](./citations/Revaud_2019_r2d2.txt)
- [D2-Net: A Trainable CNN for Joint Detection and Description of Local Features](https://arxiv.org/abs/1905.03561), Dusmanu Mihai et al., CVPR 2019 | [github](https://github.com/mihaidusmanu/d2-net) | [bibtex](./citations/Dusmanu_2019_D2Net.txt)
- [Large-Scale Image Retrieval with Attentive Deep Local Features](https://arxiv.org/abs/1612.06321), Noh Hyeonwoo et al., ICCV 2017 | [bibtex](./citations/Noh_2017_delf.txt)

</details>


<details open>
<summary>Benchmarks</summary>

- [Are Local Features All You Need for Cross-Domain Visual Place Recognition?](https://arxiv.org/abs/2304.05887), Giovanni Barbarani et al., CVPRW 2023 | [github](https://github.com/gbarbarani/re-ranking-for-VPR) | [bibtex](./citations/Barbarani_2023_reranking_benchmark.txt)
- [Deep Visual Geo-localization Benchmark](https://arxiv.org/abs/2204.03444), Berton Gabriele et al., CVPR 2022 | [github](https://github.com/gmberton/deep-visual-geo-localization-benchmark) | [bibtex](./citations/Berton_2022_benchmark_berton.txt)
- [VPR-Bench: An Open-Source Visual Place Recognition Evaluation Framework with Quantifiable Viewpoint and Appearance Change](https://arxiv.org/abs/2005.08135), Zaffar Mubariz et al., IJCV 2021 | [github](https://github.com/MubarizZaffar/VPR-Bench) | [bibtex](./citations/Zaffar_2021_vprbench.txt)
- [Benchmarking Image Retrieval for Visual Localization](https://arxiv.org/abs/2011.11946), Pion Noe et al., 3DV 2020 | [bibtex](./citations/Pion_2020_benchmark_VisLoc.txt)
- [Benchmarking 6DOF Outdoor Visual Localization in Changing Conditions](https://arxiv.org/abs/1707.09092), T. Sattler et al., cvpr 2018 | [bibtex](./citations/Sattler_2018_aachen_daynight.txt)

</details>


<details open>
<summary>World-wide Geo-Localization</summary>

- [Interpretable Semantic Photo Geolocation](https://arxiv.org/abs/2104.14995), Theiner Jonas et al., WACV 2022 | [github](https://github.com/jtheiner/semantic_geo_partitioning) | [bibtex](./citations/Theiner_2022_WACV.txt)
- [Where in the World is this Image? Transformer-based Geo-localization in the Wild](https://arxiv.org/abs/2204.13861), Pramanick Shraman et al., ECCV 2022 | [github](https://github.com/ShramanPramanick/Transformer_Based_Geo-localization) | [bibtex](./citations/Pramanick_2022_transformer_geoloc.txt)
- [Leveraging EfficientNet and Contrastive Learning for Accurate Global-scale Location Estimation](https://arxiv.org/abs/2105.07645), Giorgos Kordopatis-Zilos et al., ICMR 2021 | [github](https://github.com/mever-team/visloc-estimation) | [bibtex](./citations/Kordopatis_2021_EfficientNetGeoloc.txt)
- [Geolocation Estimation of Photos Using a Hierarchical Model and Scene Classification](https://openaccess.thecvf.com/content_ECCV_2018/papers/Eric_Muller-Budack_Geolocation_Estimation_of_ECCV_2018_paper.pdf), Muller-Budack Eric et al., ECCV 2018 | [github](https://github.com/TIBHannover/GeoEstimation) | [bibtex](./citations/Muller_2018_hierarchical_geolocation.txt)
- [CPlaNet: Enhancing Image Geolocalization by Combinatorial Partitioning of Maps](https://arxiv.org/abs/1808.02130), Paul Hongsuck Seo et al., ECCV 2018 | [github]() | [bibtex](./citations/Seo_2018_CPlaNet.txt)
- [Revisiting IM2GPS in the Deep Learning Era](https://arxiv.org/abs/1705.04838), Vo Nam et al., ICCV 2017 | [bibtex](./citations/Vo_2017_revIm2GPS.txt)
- [PlaNet - Photo Geolocation with Convolutional Neural Networks](https://arxiv.org/abs/1602.05314), Tobias Weyand et al., ECCV 2016 | [bibtex](./citations/Weyand_2016_PlaNet.txt)
- [IM2GPS: estimating geographic information from a single image](http://graphics.cs.cmu.edu/projects/im2gps/im2gps.pdf), James Hays et al., CVPR 2008 | [bibtex](./citations/Hays_2008_im2gps.txt)

</details>


<details open>
<summary>Others</summary>

- [Divide&Classify: Fine-Grained Classification for City-Wide Visual Geo-localization](https://arxiv.org/abs/2307.08417), Gabriele Trivigno et al., ICCV 2023 | [github](https://github.com/ga1i13o/Divide-and-Classify) | [bibtex](./citations/Trivigno_2023_DivideClassify.txt)
- [Unifying Visual Localization and Scene Recognition for People With Visual Impairment](https://www.researchgate.net/publication/340327129_Unifying_Visual_Localization_and_Scene_Recognition_for_People_With_Visual_Impairment), R. Cheng et al., IEEE Access 2020 | [bibtex](./citations/Cheng_2020_Unifying.txt)
- [Scalable Place Recognition Under Appearance Change for Autonomous Driving](https://arxiv.org/abs/1908.00178), A. D. Doan et al., ICCV 2019 | [bibtex](./citations/Doan_2019_scalable.txt)
- [Multi-Process Fusion: Visual Place Recognition Using Multiple Image Processing Methods](https://arxiv.org/abs/1903.03305), S. Hausler et al., ral 2019 | [github](https://github.com/StephenHausler/Multi-Process-Fusion) | [bibtex](./citations/Hausler_2019_fusion.txt)
- [Semantic–geometric visual place recognition: a new perspective for reconciling opposing views](https://www.researchgate.net/publication/332280264_Semantic-geometric_visual_place_recognition_a_new_perspective_for_reconciling_opposing_views), S. Garg et al., IJRR 2019 | [bibtex](./citations/Garg_2019_semanticGeometric.txt)
- [Are Large-Scale 3D Models Really Necessary for Accurate Visual Localization?](https://openaccess.thecvf.com/content_cvpr_2017/papers/Sattler_Are_Large-Scale_3D_CVPR_2017_paper.pdf), A. Torii et al., PAMI 2021 | [bibtex](./citations/Torii_2021_large_scale3D.txt)

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
