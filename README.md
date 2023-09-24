# REVO-LION
**REVO-LION: Evaluating and Refining Vision-Language Instruction Tuning Datasets**

*Ning Liao, Shaofeng Zhang, Renqiu Xia, Bo Zhang, Min Cao, Junchi Yan, Yu Qiao*

## News:

* [Paper Online] Sep 2023, released the paper titled "[REVO-LION: Evaluating and Refining Vision-Language Instruction Tuning Datasets]()".

## Introduction:
We propose the ``tune-cross-evaluation`` paradigm, which firstly performs the systematic analysis on Vision-Language Instruction Tuning (VLIT) datasets. Based on the holistic evaluation, a comprehensive dataset namly ``REVO-LION`` (REfining VisiOn-Language InstructiOn tuNing) is a proposed built upon public instruction datasets. REVO-LION includes a training set, which can be adopted for developing an all-powerful VLIT model, and an evaluation set, which can serve as a stable yet convenient benchmark.

## Installation
The code base is mostly built upon the [LAVIS](https://github.com/salesforce/LAVIS), please refer to the installation [guidance](https://github.com/salesforce/LAVIS#installation) for environment setup.

## Model Weights
In the proposed tune-cross-evaluation paradigm, we perform instruction tuning using the Q-Former as the projection module. The weights of the Q-Former that has been pre-trained in BLIP2, with Vicuna7B as the language model, before instruction tuning has been released in LAVIS, and can be downloaded [here](https://storage.googleapis.com/sfr-vision-language-research/LAVIS/models/BLIP2/blip2_pretrained_vicuna7b.pth).
