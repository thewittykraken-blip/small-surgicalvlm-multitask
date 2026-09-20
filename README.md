# small-surgicalvlm-multitask
Code and evaluation materials for multitask surgical scene understanding using a parameter-efficient fine-tuned vision-language model

Overview

We fine-tuned Qwen2.5-VL-3B-Instruct using QLoRA for multiple surgical scene-understanding tasks, including:

Instrument recognition
Surgical action recognition
Tissue and organ identification
Instrument–action–tissue triplet prediction
Surgical phase recognition
Safety assessment
Surgical image captioning

The repository contains the scripts, configuration files, prompts, and evaluation tools used in the study.

Dataset Access

This study uses the CholecT50 and SurgSigma datasets.

The original images and annotations are not redistributed in this repository. Users should obtain the datasets directly from their respective providers and comply with all applicable access and licensing conditions.

Dataset-access instructions are provided in docs/dataset_access.md.

Repository Contents
configs/: Training and evaluation configurations
scripts/: Training, evaluation, and analysis scripts
prompts/: Task-specific prompts
results/: Example or permitted prediction outputs
docs/: Reproducibility and dataset-access documentation
Installation

Installation instructions will be provided here.

Usage

Instructions for training and evaluating the model will be provided here.

Reproducibility

The repository will document the model version, training settings, evaluation procedures, and software requirements used in the study.

Data and Code Availability

The original datasets are subject to their respective access and redistribution conditions. Code and permitted evaluation materials will be made available through this repository.

Citation

A citation entry for the associated publication will be added after publication.

License

The license for the original code in this repository is specified in the accompanying license file. Dataset and model licenses may differ and remain subject to their respective terms.
