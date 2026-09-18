# OCL-TSM: Online Continual Learning-Based Time-Series Modeling

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Papers](https://img.shields.io/badge/Papers-33-278ea5)](#paper-list)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](#contributing)

The official paper list for **“A Systematic Review on Online Continual Learning-Based Time-Series Modeling.”**

This repository organizes research at the intersection of **online continual learning (OCL)** and **time-series modeling** using a task-centric taxonomy: temporal forecasting, temporal regression, temporal classification, and compound tasks. It is intended as a living resource and will be updated as new relevant studies become available.

## Contents

- [Scope](#scope)
- [Paper List](#paper-list)
  - [Temporal Forecasting](#temporal-forecasting)
  - [Temporal Regression](#temporal-regression)
  - [Temporal Classification](#temporal-classification)
  - [Compound Tasks](#compound-tasks)
- [Contributing](#contributing)
- [Citation](#citation)

## Scope

The repository focuses on studies that learn from temporally ordered, non-stationary data streams and update the model continually under online or streaming constraints. The current collection contains **33 papers**.

| Task category | Number of papers |
| --- | :---: |
| Temporal forecasting | 8 |
| Temporal regression | 6 |
| Temporal classification | 16 |
| Compound tasks | 3 |
| **Total** | **33** |

## Paper List

The **Paper** column links to the publisher page, official proceedings, or arXiv record. The **Code** column links only to an author-provided project or repository identified from the paper or its official record. “—” means that no official public implementation was identified.

### Time-Series Forecasting

| Year | Paper | Venue | Code |
| :---: | --- | --- | :---: |
| 2023 | [Learning Fast and Slow for Online Time Series Forecasting](https://openreview.net/forum?id=q-PbpHD3EOk) | ICLR | [Code](https://github.com/salesforce/fsnet) |
| 2023 | [OneNet: Enhancing Time Series Forecasting Models under Concept Drift by Online Ensembling](https://proceedings.neurips.cc/paper_files/paper/2023/hash/dd6a47bc0aad6f34aa5e77706d90cdc4-Abstract-Conference.html) | NeurIPS | [Code](https://github.com/yfzhang114/OneNet) |
| 2025 | [Complementary Learning System Empowers Online Continual Learning of Vehicle Motion Forecasting in Smart Cities](https://arxiv.org/abs/2508.19597) | arXiv | [Code](https://github.com/lzrbit/Dual-LS) |
| 2025 | [Distribution-Aware Online Learning for Urban Spatiotemporal Forecasting on Streaming Data](https://www.ijcai.org/proceedings/2025/372) | IJCAI | [Code](https://github.com/cwang-nus/DOL) |
| 2025 | [Enhancing Real-Time Urban Drainage Network Modeling Through Crossformer Algorithm and Online Continual Learning](https://doi.org/10.1016/j.watres.2024.122614) | Water Research | — |
| 2025 | [Proactive Model Adaptation Against Concept Drift for Online Time Series Forecasting](https://doi.org/10.1145/3690624.3709210) | KDD | [Code](https://github.com/SJTU-DMTai/OnlineTSF) |
| 2026 | [Escaping Stability-Plasticity Dilemma in Online Continual Learning for Motion Forecasting via Synergetic Memory Rehearsal](https://doi.org/10.1109/TNNLS.2026.3700190) | IEEE TNNLS | [Code](https://github.com/BIT-Jack/SyReM) |
| 2026 | [Online Continual Learning for Time Series: A Natural Score-Driven Approach](https://arxiv.org/abs/2601.12931) | arXiv | [Code](https://anonymous.4open.science/r/NatSR) |

### Time-Series Regression

| Year | Paper | Venue | Code |
| :---: | --- | --- | :---: |
| 2023 | [CoDEPS: Online Continual Learning for Depth Estimation and Panoptic Segmentation](https://arxiv.org/abs/2303.10147) | RSS | [Code](http://codeps.cs.uni-freiburg.de/) |
| 2023 | [CoVIO: Online Continual Learning for Visual-Inertial Odometry](https://doi.org/10.1109/CVPRW59228.2023.00245) | CVPR Workshops | [Code](http://continual-slam.cs.uni-freiburg.de/) |
| 2023 | [Online Continual Learning for Control of Mobile Robots](https://doi.org/10.1109/IJCNN54540.2023.10191188) | IJCNN | [Code](https://github.com/andriyukr/unicycle/tree/main/python) |
| 2024 | [Adaptive VIO: Deep Visual-Inertial Odometry with Online Continual Learning](https://doi.org/10.1109/CVPR52733.2024.01706) | CVPR | — |
| 2024 | [Online Industrial Fault Prognosis in Dynamic Environments via Task-Free Continual Learning](https://doi.org/10.1016/j.neucom.2024.127930) | Neurocomputing | — |
| 2024 | [sEMG-Driven Hand Dynamics Estimation With Incremental Online Learning on a Parallel Ultra-Low-Power Microcontroller](https://doi.org/10.1109/TBCAS.2024.3415392) | IEEE TBioCAS | [Code](https://github.com/pulp-bio/incremental_hyser) |

### Time-Series Classification

| Year | Paper | Venue | Code |
| :---: | --- | --- | :---: |
| 2022 | [Online Continual Learning of End-to-End Speech Recognition Models](https://doi.org/10.21437/Interspeech.2022-11093) | INTERSPEECH | — |
| 2022 | [Resource-Efficient Continual Learning for Sensor-Based Human Activity Recognition](https://doi.org/10.1145/3530910) | ACM TECS | — |
| 2023 | [Online Continual Learning in Acoustic Scene Classification: An Empirical Study](https://doi.org/10.3390/s23156893) | Sensors | — |
| 2023 | [Online Continual Learning in Keyword Spotting for Low-Resource Devices via Pooling High-Order Temporal Statistics](https://arxiv.org/abs/2307.12660) | INTERSPEECH | [Code](https://github.com/umbertomichieli/TAP-SLDA) |
| 2023 | [Online Continual Learning for Human Activity Recognition](https://doi.org/10.1016/j.pmcj.2023.101817) | Pervasive and Mobile Computing | — |
| 2023 | [Rehearsal-Free Online Continual Learning for Automatic Speech Recognition](https://www.isca-archive.org/interspeech_2023/vandereeckt23_interspeech.html) | INTERSPEECH | [Code](https://github.com/StevenVdEeckt/online-cl-for-asr) |
| 2024 | [SRTFD: Scalable Real-Time Fault Diagnosis Through Online Continual Learning](https://arxiv.org/abs/2408.05681) | arXiv | [Code](https://anonymous.4open.science/r/SRTFD-F813) |
| 2024 | [Unsupervised Online Continual Learning for Automatic Speech Recognition](https://www.isca-archive.org/interspeech_2024/vandereeckt24_interspeech.html) | INTERSPEECH | [Code](https://github.com/StevenVdEeckt/unsupervised-ocl-for-asr) |
| 2025 | [Adaptive Online Continual Learning for In-Situ Quality Prediction in Manufacturing Processes](https://doi.org/10.1115/1.4066799) | Journal of Manufacturing Science and Engineering | — |
| 2025 | [Efficient Online Continual Learning in Sensor-Based Human Activity Recognition](https://arxiv.org/abs/2511.05566) | arXiv | [Code](https://anonymous.4open.science/r/PTRN-HAR-AF60/) |
| 2025 | [Handling Catastrophic Forgetting: Online Continual Learning for Next Activity Prediction](https://doi.org/10.1007/978-3-031-81375-7_13) | CoopIS | [Code](https://github.com/TamaraVerbeek/CNAPwP) |
| 2025 | [Online Class Incremental Learning of Acoustic Events Using Acoustic Pre-Trained Models](https://doi.org/10.1109/FMLDS67896.2025.00013) | IEEE FMLDS | — |
| 2025 | [PACL+: Online Continual Learning Using Proxy-Anchor and Contrastive Loss With Gaussian Replay for Sensor-Based Human Activity Recognition](https://doi.org/10.1016/j.eswa.2025.128603) | Expert Systems with Applications | [Code](https://github.com/Dhruvadityamittal/PACL) |
| 2026 | [COOL: Continual Online On-Device Learning for Human Activity Recognition Enhanced by KANs](https://doi.org/10.1007/s42486-026-00229-z) | CCF Transactions on Pervasive Computing and Interaction | — |
| 2026 | [Energy-Efficient Online Continual Learning for Time Series Classification in Nanorobot-Based Smart Health](https://doi.org/10.1109/JBHI.2023.3289992) | IEEE JBHI | — |
| 2026 | [Online Continual Learning-Based Intrusion Detection in Industrial Control Networks](https://doi.org/10.1109/ICSMECH69390.2026.11647216) | IEEE ICSMech | — |

### Compound Tasks

| Year | Paper | Venue | Code |
| :---: | --- | --- | :---: |
| 2023 | [Label-Efficient Online Continual Object Detection in Streaming Video](https://openaccess.thecvf.com/content/ICCV2023/html/Wu_Label-Efficient_Online_Continual_Object_Detection_in_Streaming_Video_ICCV_2023_paper.html) | ICCV | [Code](https://github.com/showlab/Efficient-CLS) |
| 2024 | [Online Continual Learning of Video Diffusion Models From a Single Video Stream](https://arxiv.org/abs/2406.04814) | arXiv | — |
| 2024 | [Semi-Supervised Online Continual Learning for 3D Object Detection in Mobile Robotics](https://doi.org/10.1007/s10846-024-02178-0) | Journal of Intelligent & Robotic Systems | [Code](https://github.com/npu-ius-lab/OCL3D) |

## Contributing

Contributions are welcome. When suggesting a paper, please provide:

1. the paper title and publication year;
2. the publisher, proceedings, DOI, or arXiv link;
3. the official code link, if available; and
4. the most appropriate task category.

Please avoid linking unofficial implementations in the **Code** column unless they are clearly labeled as third-party reproductions.

## Citation

Citation information for **“A Systematic Review on Online Continual Learning-Based Time-Series Modeling”** will be added after the paper is publicly available.

---

Last updated: 2026-09-18.
