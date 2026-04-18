**Recognition-Aware Image Processing**

This is a project that implements and extends the work presented in the paper "Exploring Simple and Transferable Recognition-Aware Image Processing". The aim is to close the gap between human perception and machine understanding by making image processing pipelines aware of recognition models.

The core concept is to simultaneously optimize image reconstruction and recognition via the objective:

L = Lproc + λ Lrecog

where Lproc makes sure images are visually similar, and Lrecog ensures that its interpretation and context is consistent with respect to a recognition model.

Further, we investigate the framework's characteristics through experiments and extend it to domain-specific applications in medical imaging.


**Project Demonstrations**

Phase 1 - Mid Implementation

This phase entails the main work of Recognition-Aware framework implementation including baseline pipeline, recognition loss integration, and initial evaluation.
https://drive.google.com/drive/folders/1AlFeMvaKtDo2mmgxUXlLsWUA5nzniX3P?usp=sharing

Phase 2 - Final Implementation

This phase consists of the entire work with lambda trade-off analysis, cross-model transferability validation, medical imaging extension, and the proposed segmentation-aware recognition-aware loss.
https://drive.google.com/file/d/1NNM4RaKcONGOvykJoyr-Ez3l5WEEvn6V/view?usp=sharing


**Datasets Used**

Original Dataset (ImageNet - ILSVRC 2012)

Used to train and assess recognition-aware image processing pipeline. The large-scale image dataset gave us a lot of data and was used to simulate different types of image degradations like noise blur downsampling, and compression.

https://image-net.org/challenges/LSVRC/2012/2012-downloads.php

Medical Dataset (Chest X-Ray Pneumonia)

Dedicated to further developing the framework in a healthcare setting. This dataset offers an assessment of recognition-aware processing when preservation of critical features is essential.

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
