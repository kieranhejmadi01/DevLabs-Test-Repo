---
title: "Apply quantization-aware training for mobile deployment"
minutes_to_complete: 30240
author:
    - Arm Developer Program
weight: 1
subjects: ML
skilllevels: Advanced
tools_software_languages:
    - Python
    - PyTorch
    - Android Studio
operatingsystems:
    - Android
    - Linux
    - macOS
challenge: true
multi_challenge: false
multichallenge_part: false
layout: challengeall
---

## Overview

Quantization-aware training helps preserve model accuracy while reducing model size and inference latency, which makes it especially useful for Arm-powered mobile devices. It is a practical way to build efficient on-device AI without sacrificing usability.

In this challenge, you apply PyTorch quantization-aware training to computer vision models intended for Arm-based mobile deployment and publish the resulting artifacts for the wider community.


## The challenge

Train a model using a non-restrictively licensed dataset, apply quantization-aware training, and deploy the result to an Arm-powered mobile target such as an Android phone or emulator.

## Suggested scope

Consider real-time applications such as:

- Sign language recognition for accessibility
- Visual anomaly detection in manufacturing
- Personal health and activity monitoring from camera feeds

The final quantized model should be suitable for sharing with the Hugging Face community and, where relevant, for inclusion in the Arm space on Hugging Face.

## Skills you can practice

- Quantization-aware training
- Model deployment on Arm mobile devices
- Android integration for AI inference
- Reproducible model publishing

## Assessment criteria

Submissions are assessed using broad criteria that balance model quality, deployability, and value for Arm-powered mobile systems.

{{< tabpane-normal >}}
    {{< tab header="Use of Arm technology" >}}
Your submission should show that the trained and quantized model runs successfully on an Arm-powered mobile target. Strong entries demonstrate that deployment choices are appropriate for real Arm mobile devices rather than only desktop evaluation.
    {{< /tab >}}
    {{< tab header="Model quality and suitability" >}}
Assessors look for models that are both useful and well matched to the chosen task. Strong submissions show that quantization-aware training preserves practical quality while keeping the model efficient enough for mobile use.
    {{< /tab >}}
    {{< tab header="Engineering quality and robustness" >}}
Your implementation should be reliable and well organized across training, export, and deployment. Strong entries show clear workflows, sensible validation steps, and robust handling of model conversion or runtime issues.
    {{< /tab >}}
    {{< tab header="Documentation and reproducibility" >}}
Your work should be easy to understand, run, and evaluate. Strong submissions provide dataset information, training settings, deployment steps, and enough detail for reviewers to reproduce the quantized model and mobile inference flow.
    {{< /tab >}}
{{< /tabpane-normal >}}


## Prepare your approach

These skills and resources are helpful before you begin:

- Familiarity with Python, PyTorch, and optionally Java or Kotlin for Android
- Intermediate understanding of PyTorch
- Familiarity with Android Studio and mobile deployment
- Access to an Arm-based Android device or emulator

## Resources

- Documentation: [Quantization in PyTorch](https://pytorch.org/docs/stable/quantization.html)
- Blog: [Bring your AI model to Android devices](https://android-developers.googleblog.com/2024/10/bring-your-ai-model-to-android-devices.html)
- Dataset documentation: [Hugging Face Datasets](https://huggingface.co/docs/datasets/en/index)
- Repository: [AI on Arm course](https://github.com/arm-university/AI-on-Arm)