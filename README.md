<p align="center">
  <h1 align="center">RaFD: Flow-Guided Radar Detection for Robust Autonomous Driving</h1>

  <p align="center">
    <strong>Shuocheng Yang</strong>
    ·
    <strong>Zikun Xu</strong>
    ·
    <strong>Jiahao Wang</strong>
    ·
    <strong>Shahid Nawaz</strong>
    ·
    <strong>Jianqiang Wang*</strong>
    ·
    <strong>Shaobing Xu*</strong>
</p>

## News

- [2026/03/13] 🎤 RaFD has been selected as an **Oral presentation** at **ICASSP 2026**!
- [2026/01/18] 🚀RaFD is accepted to ICASSP 2026!
- [2025/09/18] Paper released on [arXiv](https://arxiv.org/abs/2509.16261).
- [2025/09/18] This repository has been created for paper, and code will be released after acceptance.
- [2026/03/13] ✨ RaFD has been further extended in our new work **RaFP**. Stay tuned!

## Abstract

Radar has shown strong potential for robust perception in autonomous driving; however, raw radar images are frequently degraded by noise and “ghost” artifacts, making object detection based solely on semantic features highly challenging. To address this limitation, we introduce RaFD, a radar-based object detection framework that estimates inter-frame bird’s-eye-view (BEV) flow and leverages the resulting geometric cues to enhance detection accuracy. Specifically, we design a supervised flow estimation auxiliary task that is jointly trained with the detection network. The estimated flow is further utilized to guide feature propagation from the previous frame to the current one. Our flow-guided, radar-only detector achieves achieves state-of-the-art performance on the RADIATE dataset, underscoring the importance of incorporating geometric information to effectively interpret radar signals, which are inherently ambiguous in semantics.

## Overview

![overview](figs/rafd.png)

## Visualization

**Qualitative Results on RADIATE Dataset:**

<div align="center">
    <img src=".\figs\visual_det.png" alt="result_kaist" width="100%" />
</div

**Demo on RADIATE Dataset:**

https://github.com/user-attachments/assets/d73327cd-e58f-410e-b0e3-0ec648011454

## Acknowledgement

Many thanks to these excellent projects:

- [mmdet3d](https://github.com/open-mmlab/mmdetection3d)

- [bevformer](https://github.com/fundamentalvision/BEVFormer)
