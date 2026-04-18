**Recognition-Aware Image Processing**

This project implements and extends the paper “Exploring Simple and Transferable Recognition-Aware Image Processing”. The goal is to bridge the gap between human perception and machine understanding by making image processing pipelines aware of recognition models.

The core idea is to jointly optimize image reconstruction and recognition using the objective:
L = Lproc + λ Lrecog
where Lproc ensures visual similarity and Lrecog ensures semantic consistency with respect to a recognition model.

We further analyze the behavior of this framework through experiments and extend it to domain-specific applications in medical imaging.

**Project Demonstrations**

Phase 1 — Mid Implementation
This phase covers the initial implementation of the Recognition-Aware framework, including the baseline pipeline, integration of recognition loss, and initial evaluation.
https://drive.google.com/drive/folders/1AlFeMvaKtDo2mmgxUXlLsWUA5nzniX3P?usp=sharing

Phase 2 — Final Implementation
This phase includes the complete work with lambda trade-off analysis, cross-model transferability validation, extension to medical imaging, and the proposed segmentation-aware recognition-aware loss.
https://drive.google.com/file/d/1NNM4RaKcONGOvykJoyr-Ez3l5WEEvn6V/view?usp=sharing

**Datasets Used**

Original Dataset (ImageNet - ILSVRC 2012)
Used for training and evaluating the core recognition-aware image processing pipeline. The dataset provides large-scale image data and was used to simulate corruption such as noise, blur, downsampling, and compression.

https://image-net.org/challenges/LSVRC/2012/2012-downloads.php

Medical Dataset (Chest X-Ray Pneumonia)
Used for extending the framework to a healthcare setting. This dataset allows evaluation of how recognition-aware processing behaves when preservation of critical features is important.

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
