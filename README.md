---

# 🌟 Awesome Egocentric-and-Exocentric Vision

[![Survey Paper](https://img.shields.io/badge/Survey-Paper-blue)](https://arxiv.org/abs/2506.06253)
![Last Updated](https://img.shields.io/badge/Last%20Updated-2025--10--03-brightgreen)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-orange)
![Stars](https://img.shields.io/github/stars/ayiyayi/Awesome-Egocentric-and-Exocentric-Vision?style=social)

A curated list of **papers and datasets** on **Egocentric (first-person) and Exocentric (third-person) Vision**.
This repo complements our survey and is continuously updated.

---

## 📖 Contents

* [Papers](##papers)

  * [Egocentric for Exocentric](#egocentric-for-exocentric)
  * [Exocentric for Egocentric](#exocentric-for-egocentric)
  * [Joint Learning](#joint-learning)
* [Datasets](#datasets)

---

## 📑 Papers

### 🔹 Egocentric for Exocentric

#### ✨ Video Generation

|  Title  |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[Intention-driven Ego-to-Exo Video Generation](https://arxiv.org/abs/2403.09194) | arxiv | 2024 | - |
|[Ego-to-Exo: Interfacing Third Person Visuals from Egocentric Views in Real-time for Improved ROV Teleoperation](https://arxiv.org/abs/2407.00848)|arxiv|2024|-|

####  ✨ Action Understanding

|  Title  |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[From my view to yours: Egoaugmented learning in large vision language models <br> for understanding exocentric daily living activities](https://arxiv.org/abs/2501.05711)|arxiv|2025|[Github](https://github.com/dominickrei/EgoExo4ADL)|

####  ✨ View Birdification

|  Title  |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[View birdification in the crowd: Ground-plane localization from perceived movements](https://arxiv.org/abs/2111.05060)|arxiv|2021|-|
|[Viewbirdiformer: Learning to recover ground-plane crowd trajectories and ego-motion from a single ego-centric view](https://ieeexplore.ieee.org/document/9944870)|RAL|2022|-|
|[Incrowdformer: On-ground pedestrian world model from egocentric views](https://arxiv.org/abs/2303.09534)|arxiv|2023|-|

#### ✨  View Selection
|  Title  |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[Camera selection for occlusion-less surgery recording via training with an egocentric camera](https://ieeexplore.ieee.org/document/9562527)|Access|2021|-|



### 🔹 Exocentric for Egocentric

#### ✨  Video Generation

|  Title  |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[From third person to first person: Dataset and baselines for synthesis and retrieval](https://arxiv.org/abs/1812.00104)|CVPRW|2019|[Github](https://github.com/M-Elfeki/ThirdToFirst)|
|[Crossview exocentric to egocentric video synthesis](https://arxiv.org/abs/2107.03120)|arxiv|2021|-|
|[Parallel generative adversarial network for third-person to first-person image generation](https://openaccess.thecvf.com/content/CVPR2022W/VOCVALC/papers/Liu_Parallel_Generative_Adversarial_Network_for_Third-Person_to_First-Person_Image_Generation_CVPRW_2022_paper.pdf)|CVPRW|2022|-|
|[Towards third-person visual imitation learning using generative adversarial networks](https://ieeexplore.ieee.org/document/9962214)|ICDL|2022|-|
|[4diff: 3d-aware diffusion model for third-to-first viewpoint translation](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03536.pdf)|ECCV|2024|[Github](https://klauscc.github.io/4diff)|
|[Diffusing in someone else’s shoes: Robotic perspective taking with diffusion](https://ieeexplore.ieee.org/document/10769830)|Humanoids|2024|[Github](https://github.com/knowledgetechnologyuhh/robotic-perspective-taking-with-diffusion)|
|[Put myself in your shoes: Lifting the egocentric perspective from exocentric videos](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/05558.pdf)|ECCV|2024|-|
|[Exocentric-to-EgocentricVideoGeneration](https://arxiv.org/abs/2503.09143)|NeulIPS|2024|[Github](https://github.com/showlab/Exo2Ego-V)
|[EgoExo-Gen: Ego-centric Video Prediction by Watching Exo-centric Videos](https://arxiv.org/abs/2504.11732)|ICLR|2025|-

#### ✨  Video Captioning

|  Title  |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[Exo2egodvc: Dense video captioning of egocentric procedural activities using web instructional videos](https://arxiv.org/abs/2311.16444)|WACV|2023|[Github](https://github.com/ut-vision/Exo2EgoDVC)|
|[Retrieval-augmented egocentric video captioning](https://openaccess.thecvf.com/content/CVPR2024/papers/Xu_Retrieval-Augmented_Egocentric_Video_Captioning_CVPR_2024_paper.pdf)|CVPR|2024|[Github](https://github.com/Jazzcharles/Egoinstructor/)|

#### ✨  Action Understanding
| Title   |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[Unsupervised and semi-supervised domain adaptation for action recognition from drones](https://ieeexplore.ieee.org/document/9093511)|WACV|2020|-|
|[Ego-exo: Transferring visual representations from third-person to first-person videos](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Ego-Exo_Transferring_Visual_Representations_From_Third-Person_to_First-Person_Videos_CVPR_2021_paper.pdf)|CVPR|2021|[Github](https://github.com/facebookresearch/Ego-Exo)|
|[Audio-Adaptive Activity Recognition Across Video Domains](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Audio-Adaptive_Activity_Recognition_Across_Video_Domains_CVPR_2022_paper.pdf)|CVPR|2022|[Github](https://github.com/xiaobai1217/DomainAdaptation)|
|[Estimating egocentric 3d human pose in the wild with external weak supervision](https://arxiv.org/abs/2201.07929)|CVPR|2022|[Github](https://github.com/jianwang-mpi/EgoPW)|
|[Cross-view action recognition understanding from exocentric to egocentric perspective](https://arxiv.org/abs/2305.15699)|arxiv|2023|-|
|[Cross-view generalisation in action recognition: Feature design for transitioning from exocentric to egocentric views](https://link.springer.com/chapter/10.1007/978-3-031-58676-7_13)|Robot|2023|-|
|[Learning from semantic alignment between unpaired multiviews for egocentric video recognition](https://ieeexplore.ieee.org/abstract/document/10378238)|ICCV|2023|[Github](https://github.com/wqtwjt1996/SUM-L)|
|[Egofish3d: Egocentric 3d pose estimation from a fisheye camera via selfsupervised learning](https://ieeexplore.ieee.org/document/10037218)|TMM|2023|[Github](https://github.com/Lrnyux/EgoCentric-Human-Pose-ECHP-Dataset)|
|[Ex2eg-mae: A framework for adaptation of exocentric video masked autoencoders for egocentric social role understanding](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/10301.pdf)|ECCV|2024|-|
|[Synchronization is all you need: Exocentric-to-egocentric transfer for temporal action segmentation <br> with unlabeled synchronized video pairs](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09116.pdf)|ECCV|2024|[Github](https://github.com/fpv-iplab/synchronization-is-all-you-need)|
|[Unlocking exocentric video-language data for egocentric video representation learning](https://arxiv.org/abs/2408.03567)|arxiv|2024|-|


#### ✨  Affordance Grounding

| Title   |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[Learning affordance grounding from exocentric images](https://openaccess.thecvf.com/content/CVPR2022/papers/Luo_Learning_Affordance_Grounding_From_Exocentric_Images_CVPR_2022_paper.pdf)|CVPR|2022|[Github](https://github.com/lhc1224/Cross-View-AG)|
|[Locate: Localize and transfer object parts for weakly supervised affordance grounding](https://ieeexplore.ieee.org/document/10203835)|CVPR|2023|[Github](https://github.com/Reagan1311/LOCATE)|
|[Weakly supervised multimodal affordance grounding for egocentric images](https://ojs.aaai.org/index.php/AAAI/article/view/28451)|AAAI|2024|[Github](https://github.com/xulingjing88/WSMA)|
|[Self-explainable affordance learning with embodied caption](https://arxiv.org/abs/2404.05603)|arxiv|2024|-|
|[Strategies to leverage foundational model knowledge in object affordance grounding](https://openaccess.thecvf.com/content/CVPR2024W/MMFM/papers/Rai_Strategies_to_Leverage_Foundational_Model_Knowledge_in_Object_Affordance_Grounding_CVPRW_2024_paper.pdf)|CVPRW|2024|-|
|[Intra: Interaction relationship-aware weakly supervised affordance grounding](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08064.pdf)|ECCV|2024|-|
|[Learning granularity-aware affordances from humanobject interaction for tool-based functional grasping in dexterous robotics](https://arxiv.org/abs/2407.00614)|arxiv|2024|[Github](https://github.com/Popeye-pxx/gaaf-dex)|

#### ✨  Remote Drone Teleoperation

| Title   |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[Droneaugmented human vision: Exocentric control for drones exploring hidden areas](https://ieeexplore.ieee.org/document/8260942)|TVCG|2018|-|
|[Third-person piloting: Increasing situational awareness using a spatially coupled second drone](https://dl.acm.org/doi/10.1145/3332165.3347953)|UIST|2019|-|
|[Starhopper: A touch interface for remote object-centric drone navigation](https://graphicsinterface.org/proceedings/gi2020/gi2020-32/)|Graphics Interface|2020|-|
|[Birdviewar: Surroundings-aware remote drone piloting using an augmented thirdperson perspective](https://dl.acm.org/doi/full/10.1145/3544548.3580681)|CHI|2023|[Github](https://github.com/icd-tohoku/BirdViewAR_chi2023)|


### 🔹 Joint Learning
#### ✨  Video Captioning

| Title   |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[Fourth-Person Captioning: Describing Daily Events by Uni-supervised and Tri-regularized Training](https://ieeexplore.ieee.org/document/8616361)|SMC|2018|-|
|[Lifelogging caption generation via fourth-person vision in a human–robot symbiotic environment](https://robomechjournal.springeropen.com/articles/10.1186/s40648-020-00181-2)|ROBOMECH|2020|-|

#### ✨  Cross-View Retrieval
| Title   |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[Egotransfer: Transferring motion across egocentric and exocentric domains using deep neural networks](https://arxiv.org/abs/1612.05836)|arxiv|2016|-|
| [Actor and observer: Joint modeling of first and third-person videos](https://openaccess.thecvf.com/content_cvpr_2018/papers/Sigurdsson_Actor_and_Observer_CVPR_2018_paper.pdf)|CVPR|2018|[Github](https://github.com/gsig/actor-observer)
|[From Third Person to First Person: Dataset and Baselines for Synthesis and Retrieval](https://arxiv.org/abs/1812.00104)|CVPRW|2019|[Github](https://github.com/M-Elfeki/ThirdToFirst)
|[First- and third-person video co-analysis by learning spatial-temporal joint attention](https://ieeexplore.ieee.org/document/9220850)|TPAMI|2020|-
|[Objectrelator: Enabling cross-view object relation understanding in ego-centric and exo-centric videos](https://arxiv.org/html/2411.19083v1)|arxiv|2024|[Github](https://github.com/lovelyqian/ObjectRelator)

#### ✨  3D Camera Localization

| Title   |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[Relating view directions of complementary-view mobile cameras via the human shadow](https://dl.acm.org/doi/10.1007/s11263-022-01744-z)|IJCV|2023|[Github](https://github.com/RuizeHan/CVCR)
|[From a bird’s eye view to see: Joint camera and subject registration without the camera calibration](https://ieeexplore.ieee.org/document/10657684)|CVPR|2024|[Github](https://github.com/zekunqian/bevsee)
|[Yowo: You only walk once to jointly map an indoor scene and register ceiling-mounted cameras](https://ieeexplore.ieee.org/document/10663468)|TCSVT|2024|-


#### ✨  Action Understanding

| Title   |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[Action recognition in the presence of one egocentric and multiple static cameras](https://link.springer.com/chapter/10.1007/978-3-319-16814-2_12)|ACCV|2014|-
|[An exocentric look at egocentric actions and vice versa](https://arxiv.org/abs/1612.05836)|CVIU|2016|-
|[Recognizing micro-actions and reactions from paired egocentric videos](https://ieeexplore.ieee.org/document/7780657)|CVPR|2016|-
| [Actor and observer: Joint modeling of first and third-person videos](https://openaccess.thecvf.com/content_cvpr_2018/papers/Sigurdsson_Actor_and_Observer_CVPR_2018_paper.pdf)|CVPR|2018|[Github](https://github.com/gsig/actor-observer)
|[Holographic feature learning of egocentric-exocentric videos for multi-domain action recognition](https://ieeexplore.ieee.org/document/9429982)|TMM|2021|-
|[Holistic-guided disentangled learning with cross-video semantics mining for concurrent first-person and third-person activity recognition](https://ieeexplore.ieee.org/document/9887964)|TNNLS|2022|-|
|[Look both ways: Self-supervising driver gaze estimation and road scene saliency](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730128.pdf)|ECCV|2022|[Github](https://github.com/Kasai2020/look_both_ways)
|[Aide: A vision-driven multi-view, multi-modal, multitasking dataset for assistive driving perception](https://openaccess.thecvf.com/content/ICCV2023/papers/Yang_AIDE_A_Vision-Driven_Multi-View_Multi-Modal_Multi-Tasking_Dataset_for_Assistive_Driving_ICCV_2023_paper.pdf)|ICCV|2023|[Github](https://github.com/ydk122024/AIDE)
|[Learning fine-grained view-invariant representations from unpaired ego-exo videos via temporal alignment](https://arxiv.org/abs/2306.05526)|NeurIPS|2023|[Github](https://github.com/zihuixue/AlignEgoExo)
|[Pov: Prompt-oriented view-agnostic learning for egocentric hand-object interaction in the multi-view world](https://arxiv.org/abs/2403.05856)|ACMMM|2023|[Github](https://github.com/xuboshen/pov_acmmm2023)
|[Enhancing egocentric 3d pose estimation with third person views](https://arxiv.org/abs/2201.02017)|PR|2023|[Github](https://github.com/nudlesoup/First2Third-Pose)
|[Next-generation surgical navigation: Marker-less multi-view 6dof pose estimation of surgical instruments](https://arxiv.org/abs/2305.03535)|arxiv|2023|[Github](https://github.com/jonashein/mvpsp)
|[Tell, don’t show: Language guidance eases transfer across domains in images and videos](https://arxiv.org/abs/2403.05535)|ICML|2024|[Github](https://github.com/ViLab-UCSD/LaGTran_ICML2024)
|[Viewpoint Rosetta Stone: Unlocking Unpaired Ego-Exo Videos for View-invariant Representation Learning](https://openaccess.thecvf.com/content/CVPR2025/papers/Luo_Viewpoint_Rosetta_Stone_Unlocking_Unpaired_Ego-Exo_Videos_for_View-invariant_Representation_CVPR_2025_paper.pdf)|CVPR|2025|[Github](https://github.com/luomi777/ViewpointRosetta)
|[Bootstrap Your Own Views: Masked Ego-Exo Modeling for Fine-grained View-invariant Video Representations](https://openaccess.thecvf.com/content/CVPR2025/papers/Park_Bootstrap_Your_Own_Views_Masked_Ego-Exo_Modeling_for_Fine-grained_View-invariant_CVPR_2025_paper.pdf)|CVPR|2025|[Github](https://github.com/park-jungin/byov)

#### ✨  Egocentric Wearer Identification

| Title   |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[Ego2top: Matching viewers in egocentric and top-view videos](https://arxiv.org/abs/1607.06986)|arxiv|2016|-
|[Identifying first-person camera wearers in third-person videos](https://openaccess.thecvf.com/content_cvpr_2017/papers/Fan_Identifying_First-Person_Camera_CVPR_2017_paper.pdf)|CVPR|2017|-
|[Egocentric meets top-view](https://ieeexplore.ieee.org/document/8353133)|TPAMI|2018
|[Integrating egocentric videos in top-view surveillance videos: Joint identification and temporal alignment](https://openaccess.thecvf.com/content_ECCV_2018/papers/Shervin_Ardeshir_Integrating_Egocentric_Videos_ECCV_2018_paper.pdf)|ECCV|2018|-
|[Joint person segmentation and identification in synchronized first- and third-person videos](https://openaccess.thecvf.com/content_ECCV_2018/papers/Mingze_Xu_Joint_Person_Segmentation_ECCV_2018_paper.pdf)|ECCV|2018|[Github](https://github.com/xumingze0308/firstthird-eccv2018)
|[Visual-gps: Ego-downward and ambient video based person location association](https://ieeexplore.ieee.org/document/9025474)|CVPRW|2019|-
|[Seeing the unseen: Predicting the first-person camera wearer’s location and pose in third-person scenes](https://ieeexplore.ieee.org/document/9607539)|ICCVW|2021|-
|[Fusing personal and environmental cues for identification and segmentation of first-person camera wearers in third-person views](https://ieeexplore.ieee.org/abstract/document/10656137)|CVPR|2024|[Github](https://github.com/ziweizhao1993/PEN)

#### ✨  Cross-View Human Tracking and Association

| Title   |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[Integrating egocentric videos in top-view surveillance videos: Joint identification and temporal alignment](https://openaccess.thecvf.com/content_ECCV_2018/papers/Shervin_Ardeshir_Integrating_Egocentric_Videos_ECCV_2018_paper.pdf)|ECCV|2018|-
|[Complementary-view co-interest person detection](https://dlnext.acm.org/doi/10.1145/3394171.3413659)|ACM MM|2020|[Github](https://github.com/RuizeHan/CIP)
|[CVMHT: Complementary-view multiple human tracking](https://ojs.aaai.org/index.php/AAAI/article/view/6724)|AAAI|2020|[Github](https://github.com/RuizeHan/CVMHT)
|[Multiple human association and tracking from egocentric and complementary top views](https://ieeexplore.ieee.org/document/9394804)|TPAMI|2021|[Github](https://github.com/RuizeHan/CVMHAT)
|[Connecting the complementary-view videos: Joint camera identification and subject association](https://ieeexplore.ieee.org/document/9879989)|CVPR|2022|[Github](https://github.com/RuizeHan/DMHA)

#### ✨  Robotic Manipulation

| Title   |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[Third-Person Visual Imitation Learning via Decoupled Hierarchical Controller](https://proceedings.neurips.cc/paper_files/paper/2019/file/8a146f1a3da4700cbf03cdc55e2daae6-Paper.pdf)|NeulIPS|2019|[GitHub](https://github.com/pathak22/hierarchical-imitation/)
|[Vision-based manipulators need to also see from their hands](https://arxiv.org/abs/2203.12677)|ICLR|2021|[Github](https://github.com/moojink/cube-grasping)
|[Self-supervised disentangled representation learning for third-person imitation learning](https://ieeexplore.ieee.org/document/9636363)|IROS|2021|-
|[Look closer: Bridging egocentric and third-person views with transformers for robotic manipulation](https://arxiv.org/abs/2201.07779)|arxiv|2022|[Github](https://github.com/jangirrishabh/look-closer)
|[Visual-policy learning through multi-camera view to single-camera view knowledge distillation for robot manipulation tasks](https://ieeexplore.ieee.org/document/10327777)|LRR|2023|-
|[Multi-View Masked World Models for Visual Robotic Manipulation](https://arxiv.org/abs/2302.02408)|arxiv|2023|[Github](https://github.com/younggyoseo/MV-MWM)
|[Multi-view disentanglement for reinforcement learning with multiple cameras](https://arxiv.org/abs/2404.14064)|arxiv|2024|[Github](https://github.com/uoe-agents/MVD)

#### ✨  Remote Drone Teleoperation
| Title   |   Venue  |   Year   |   Code   |
|:--------|:--------:|:--------:|:--------:|
|[Spatial assisted human-drone collaborative navigation and interaction through immersive mixed reality](https://ieeexplore.ieee.org/abstract/document/10611351)|ICRA|2024|[Github](https://github.com/arplaboratory/mri_ros_public)



## 📊 Datasets
### Action Understanding

| Dataset |   Year   |   Paper  |   Project| Code|
|:--------|:--------:|:--------:|:--------:|:--------:|
|CMU-MMAC |2009|[Guide to the carnegie mellon university multimodal activity (cmu-mmac) database](https://kilthub.cmu.edu/articles/journal_contribution/Guide_to_the_Carnegie_Mellon_University_Multimodal_Activity_CMU-MMAC_Database/6555020/1?file=12037214)|[Project](http://kitchen.cs.cmu.edu/index.php)|-
|Charades-Ego|2018|[Actor and observer: Joint modeling of first and third-person videos](https://arxiv.org/abs/1804.09627)|[Project](https://prior.allenai.org/projects/charades-ego)|[Github](https://github.com/gsig/actor-observer)
|H2O|2021|[H2o: Two hands manipulating objects for first person interaction recognition](https://openaccess.thecvf.com/content/ICCV2021/papers/Kwon_H2O_Two_Hands_Manipulating_Objects_for_First_Person_Interaction_Recognition_ICCV_2021_paper.pdf)|[Project](https://taeinkwon.com/projects/h2o/)|[Github](https://github.com/taeinkwon/h2odataset)
|Assembly101|2022|[Assembly101: A large-scale multi-view video dataset for understanding procedural activities](https://openaccess.thecvf.com/content/CVPR2022/papers/Sener_Assembly101_A_Large-Scale_Multi-View_Video_Dataset_for_Understanding_Procedural_Activities_CVPR_2022_paper.pdf)|[Project](https://assembly-101.github.io/)|[Github](https://github.com/assembly-101?tab=repositories)
|Homage|2021|[Home action genome: Cooperative compositional action understanding](https://openaccess.thecvf.com/content/CVPR2021/papers/Rai_Home_Action_Genome_Cooperative_Compositional_Action_Understanding_CVPR_2021_paper.pdf)|[Project](https://homeactiongenome.org/)|[Github](https://homeactiongenome.org/)
|LEMMA|2020|[Lemma: A multiview dataset for le arning m ulti-agent m ulti-task a ctivities](https://arxiv.org/pdf/2007.15781)|[Project](https://sites.google.com/view/lemma-activity)|[Github](https://github.com/Buzz-Beater/LEMMA)
|FT-HID|2022| [Ft-hid: a large-scale rgb-d dataset for first-and third-person human interaction analysis](https://arxiv.org/abs/2209.10155)|-|[Github](https://github.com/ENDLICHERE/FT-HID)
|EgoPW|2022|[Estimating egocentric 3d human pose in the wild with external weak supervision](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Estimating_Egocentric_3D_Human_Pose_in_the_Wild_With_External_CVPR_2022_paper.pdf)|[Project](https://people.mpi-inf.mpg.de/~jianwang/projects/egopw/)|[Github](https://github.com/jianwang-mpi/EgoPW)
|First2Third-Pose|2022|[Enhancing egocentric 3d pose estimation with third person views](https://arxiv.org/abs/2201.02017)|-|[GitHub](https://github.com/nudlesoup/First2Third-Pose)
|ARCTIC|2023|[ARCTIC: A dataset for dexterous bimanual hand-object manipulation](https://openaccess.thecvf.com/content/CVPR2023/papers/Fan_ARCTIC_A_Dataset_for_Dexterous_Bimanual_Hand-Object_Manipulation_CVPR_2023_paper.pdf)|[Project](https://arctic.is.tue.mpg.de/)|[Github](https://github.com/zc-alexfan/arctic)
|ECHP|2023|[Egofish3d: Egocentric 3d pose estimation from a fisheye camera via selfsupervised learning](https://ieeexplore.ieee.org/document/10037218)|-|[Github](https://github.com/Lrnyux/EgoCentric-Human-Pose-ECHP-Dataset)
|AssemblyHands|2023|[Assemblyhands: Towards egocentric activity understanding via 3d hand pose estimation](https://openaccess.thecvf.com/content/CVPR2023/papers/Ohkawa_AssemblyHands_Towards_Egocentric_Activity_Understanding_via_3D_Hand_Pose_Estimation_CVPR_2023_paper.pdf)|[Project](https://assemblyhands.github.io/)|[Github](https://github.com/facebookresearch/assemblyhands-toolkit)
|EgoHumans|2023|[Ego-humans: An ego-centric 3d multi-human benchmark](https://ieeexplore.ieee.org/document/10377933)|[Project](https://rawalkhirodkar.github.io/egohumans/)|[Github](https://github.com/rawalkhirodkar/egohumans)
|-|2023|[Next-generation surgical navigation: Marker-less multi-view 6dof pose estimation of surgical instruments](https://arxiv.org/abs/2305.03535)|[Project](https://jonashein.github.io/mvpsp/)|-
|ThermoHands|2024|[Thermohands: A benchmark for 3d hand pose estimation from egocentric thermal image](https://arxiv.org/abs/2403.09871)|[Project](https://thermohands.github.io/)|[Github](https://github.com/LawrenceZ22/ThermoHands)
|OVR|2024| [Ovr: A dataset for open vocabulary temporal repetition counting in videos](https://arxiv.org/abs/2407.17085)|-|[Github](https://github.com/google-deepmind/ovr/)
|Nymeria|2024|[Nymeria: A massive collection of multimodal egocentric daily motion in the wild](https://arxiv.org/abs/2406.09905)|[Project](https://www.projectaria.com/datasets/nymeria/)|[Github](https://github.com/facebookresearch/nymeria_dataset)
|OAKINK2|2024|[Oakink2: A dataset of bimanual hands-object manipulation in complex task completion](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhan_OAKINK2_A_Dataset_of_Bimanual_Hands-Object_Manipulation_in_Complex_Task_CVPR_2024_paper.pdf)|[Project](https://oakink.net/v2)|[Github](https://github.com/oakink/OakInk2)
|CORE4D|2024| [Core4d: A 4d humanobject-human interaction dataset for collaborative object rearrangement](https://arxiv.org/abs/2406.19353)|[Project](https://core4d.github.io/)|[Github](https://github.com/leolyliu/CORE4D-Instructions)
|Ego-Exo4D|2024|[Ego-exo4d: Understanding skilled human activity from first-and third-person perspectives](https://ieeexplore.ieee.org/document/10658224)|[Project](https://ego-exo4d-data.org/)|[Github](https://github.com/EGO4D)
|EgoExoLearn|2024|[Egoexolearn: A dataset for bridging asynchronous ego-and exo-centric view of procedural activities in real world](https://ieeexplore.ieee.org/document/10657292)|-|[Github](https://github.com/OpenGVLab/EgoExoLearn)
|EgoExo-Fitness|2024|[Egoexo-fitness: Towards egocentric and exocentric full-body action understanding](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/3057_ECCV_2024_paper.php)|-|[Github](https://github.com/iSEE-Laboratory/EgoExo-Fitness)

### Driving

| Dataset |   Year   |   Paper  |   Project| Code|
|:--------|:--------:|:--------:|:--------:|:--------:|
|LBW|2022|[Look both ways: Self-supervising driver gaze estimation and road scene saliency](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730128.pdf)|-|[Github](https://github.com/Kasai2020/look_both_ways)
|AIDE|2023|[Aide: A vision-driven multi-view, multi-modal, multitasking dataset for assistive driving perception](https://openaccess.thecvf.com/content/ICCV2023/papers/Yang_AIDE_A_Vision-Driven_Multi-View_Multi-Modal_Multi-Tasking_Dataset_for_Assistive_Driving_ICCV_2023_paper.pdf)|-|[Github](https://github.com/ydk122024/AIDE)
|WTS|2024|[Wts: A pedestrian-centric traffic video dataset for fine-grained spatial-temporal understanding](https://arxiv.org/html/2407.15350v1)|[Project](https://woven-visionai.github.io/wts-dataset-homepage/)|[Github](https://github.com/woven-visionai/wts-dataset)

### Affordance Grounding
| Dataset |   Year   |   Paper  |   Project| Code|
|:--------|:--------:|:--------:|:--------:|:--------:|
|PAD|2021|[One-shot affordance detection](https://arxiv.org/abs/2106.14747)|-|[Github](https://github.com/lhc1224/OSAD_Net)
|AGD20K|2022|[Learning affordance grounding from exocentric images](https://openaccess.thecvf.com/content/CVPR2022/papers/Luo_Learning_Affordance_Grounding_From_Exocentric_Images_CVPR_2022_paper.pdf)|-|[Github](https://github.com/lhc1224/Cross-View-AG)
|FAH|2024|[Learning granularity-aware affordances from humanobject interaction for tool-based functional grasping in dexterous robotics](https://arxiv.org/abs/2407.00614)|-|[Github](https://github.com/Popeye-pxx/gaaf-dex)

### Generation
| Dataset |   Year   |   Paper  |   Project| Code|
|:--------|:--------:|:--------:|:--------:|:--------:|
|ThirdtoFirst|2021|[Ego-exo: Transferring visual representations from third-person to first-person videos](https://arxiv.org/abs/2104.07905)|-|[Github](https://github.com/facebookresearch/Ego-Exo)

### Scene Understanding
| Dataset |   Year   |   Paper  |   Project| Code|
|:--------|:--------:|:--------:|:--------:|:--------:|
|360 + x|2024|[360 + x: A panoptic multi-modal scene understanding dataset](https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_360x_A_Panoptic_Multi-modal_Scene_Understanding_Dataset_CVPR_2024_paper.pdf)|[Project](https://x360dataset.github.io/)|[Github](https://github.com/x360dataset/x360dataset-kit)

### Video Question Answering
| Dataset |   Year   |   Paper  |   Project| Code|
|:--------|:--------:|:--------:|:--------:|:--------:|
|GazeVQA|2023|[Gazevqa: A video question answering dataset for multiview eye-gaze task-oriented collaborations](https://aclanthology.org/2023.emnlp-main.648/)|-|[Github](https://github.com/mfurkanilaslan/GazeVQA)

### Egocentric Wearer Identification
| Dataset |   Year   |   Paper  |   Project| Code|
|:--------|:--------:|:--------:|:--------:|:--------:|
|TF2023|2024|[Fusing personal and environmental cues for identification and segmentation of first-person camera wearers in third-person views](https://ieeexplore.ieee.org/abstract/document/10656137)|-|[Github](https://github.com/ziweizhao1993/PEN)

### Cross-View Human Tracking and Association
| Dataset |   Year   |   Paper  |   Project| Code|
|:--------|:--------:|:--------:|:--------:|:--------:|
|CVMHT|2020|[Complementary-view multiple human tracking](https://ojs.aaai.org/index.php/AAAI/article/view/6724)|-|[GitHub](https://github.com/RuizeHan/CVMHT)
|DMHA|2022| [Connecting the complementary-view videos: Joint camera identification and subject association](https://ieeexplore.ieee.org/document/9879989)|-|[Github](https://github.com/RuizeHan/DMHA)

### Camera Registration
| Dataset |   Year   |   Paper  |   Project| Code|
|:--------|:--------:|:--------:|:--------:|:--------:|
|-|2024|[From a bird’s eye view to see: Joint camera and subject registration without the camera calibration](https://ieeexplore.ieee.org/document/10657684)|-|[Github](https://github.com/zekunqian/bevsee)
