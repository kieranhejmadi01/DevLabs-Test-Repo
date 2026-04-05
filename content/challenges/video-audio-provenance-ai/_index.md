---
title: "Build video and audio provenance workflows on Arm"
minutes_to_complete: 30240
author:
    - Arm Developer Program
weight: 1
subjects: Security
skilllevels: Advanced
tools_software_languages:
    - Python
    - C2PA
    - PyTorch
operatingsystems:
    - Linux
    - macOS
    - Windows
challenge: true
multi_challenge: false
multichallenge_part: false
layout: challengeall
---

## Overview

Generative AI has made it much easier to manipulate images, video, and audio, which creates a trust gap for viewers and organizations. Provenance frameworks such as C2PA help address this by attaching signed, machine-verifiable metadata that explains how media was created, edited, or analyzed.

In this challenge, you build an AI-augmented audio or video capture and provenance system on an Arm-powered device. Your solution should combine on-device inference with transparent provenance metadata so others can inspect how media was processed.


## The challenge

Build and evaluate a provenance-aware media pipeline on an Arm-powered device that:

- captures audio or video
- runs AI models on-device
- generates C2PA content credentials that disclose which models ran and what effect they had

## Suggested scope

The best starting point is static audio or video files. If possible, extend the project to streamed media so your system can attach provenance information in real time.

Your final result should demonstrate trust and auditability for use cases such as content integrity validation and responsible media pipelines.

## Skills you can practice

- Content provenance and authentication
- Real-time media processing
- On-device AI inference on Arm
- Responsible media system design

## Assessment criteria

Submissions are assessed using broad criteria that reflect trustworthiness, technical quality, and practical use of Arm-powered media pipelines.

{{< tabpane-normal >}}
    {{< tab header="Use of Arm technology" >}}
Your submission should demonstrate that the provenance-aware pipeline runs meaningfully on an Arm-powered device. Strong entries show how on-device AI inference, media processing, or credential generation benefit from the selected Arm platform.
    {{< /tab >}}
    {{< tab header="Provenance and auditability" >}}
Assessors look for a clear and credible record of what the system did to the media. Strong submissions show that AI processing steps are disclosed accurately and that the resulting credentials support trust, inspection, or downstream validation.
    {{< /tab >}}
    {{< tab header="System quality and robustness" >}}
Your implementation should be reliable enough to demonstrate the complete pipeline. Strong entries handle the media flow, model execution, and credential generation cleanly, with sensible treatment of errors and edge cases.
    {{< /tab >}}
    {{< tab header="Documentation and reproducibility" >}}
Your project should make it easy to understand how the pipeline works and how to test it. Clear setup instructions, input and output examples, and reproducible validation steps help reviewers assess the submission efficiently.
    {{< /tab >}}
{{< /tabpane-normal >}}


## Prepare your approach

These skills and resources are helpful before you begin:

- Experience building applications on your target platform
- Willingness to learn about C2PA and provenance concepts
- Familiarity with optimized inference on Arm-powered CPUs using frameworks with KleidiAI integration

## Resources

- Documentation: [Live video streaming in the C2PA specification](https://spec.c2pa.org/specifications/specifications/2.3/specs/C2PA_Specification.html#live-video)
- Repository: [C2PA Rust implementation](https://github.com/contentauth/c2pa-rs)
- Repository: [Simple C wrapper for a C2PA library](https://gitlab.com/guardianproject/proofmode/simple-c2pa)
- Repository: [AI on Arm course](https://github.com/arm-university/AI-on-Arm)
- Learning Path: [Vision LLM inference on Android with KleidiAI and MNN](https://learn.arm.com/learning-paths/mobile-graphics-and-gaming/vision-llm-inference-on-android-with-kleidiai-and-mnn/)
- Learning Path: [Build a hands-free selfie Android application with MediaPipe](https://learn.arm.com/learning-paths/mobile-graphics-and-gaming/build-android-selfie-app-using-mediapipe-multimodality/)

You are also welcome to contact Arm-Developer-Labs@arm.com to enquire about further support.
