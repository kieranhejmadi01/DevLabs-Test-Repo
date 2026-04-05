---
title: "Build on-device LLM runtime for NPC interaction"
minutes_to_complete: 30240
author:
    - Arm Developer Program
weight: 1
subjects: ML
skilllevels: Advanced
tools_software_languages:
    - C++
    - Python
    - Unity
operatingsystems:
    - Android
    - Linux
    - Windows
challenge: true
multi_challenge: false
multichallenge_part: false
layout: challengeall
---

## Overview

Large language models can make game characters more adaptive and responsive than traditional scripted dialogue trees. Running these models locally on Arm-powered systems can improve responsiveness while avoiding reliance on cloud infrastructure.

In this challenge, you explore novel ways of using on-device LLMs to drive real-time NPC interaction in games. The goal is not only to generate dialogue, but to create convincing, responsive NPC behavior in a playable prototype.


## The challenge

Propose and implement a novel method of using LLMs to control or interact with NPCs during runtime.

Your final prototype should run locally at a stable frame rate and demonstrate a real gameplay scenario. A mobile deployment is ideal, but a PC or laptop proof of concept is acceptable if it shows the design clearly.

## Suggested scope

Your submission should include, where possible:

- Source code with build instructions
- A reproducible setup including datasets or dependencies
- A supporting document that explains the design decisions
- High-quality images and a short demo video that shows the prototype in action

## Skills you can practice

- LLM integration in game engines
- Real-time systems design
- On-device AI optimization
- Gameplay prototyping on Arm

## Assessment criteria

Submissions are assessed using broad criteria that reflect gameplay value, technical quality, and suitability for Arm-based systems.

{{< tabpane-normal >}}
    {{< tab header="Use of Arm technology" >}}
Your submission should show that the prototype runs effectively on an Arm-based system or is clearly designed with Arm deployment in mind. Strong entries explain how the runtime, model setup, or optimization choices support practical play on Arm hardware.
    {{< /tab >}}
    {{< tab header="Gameplay relevance and novelty" >}}
Assessors look for ideas that improve interaction with NPCs in a meaningful way. Strong submissions demonstrate a believable gameplay scenario and show originality in how language models influence player experience or NPC behavior.
    {{< /tab >}}
    {{< tab header="Runtime quality and robustness" >}}
Your implementation should be stable enough to demonstrate the concept clearly. Strong entries show reliable runtime behavior, sensible latency or frame-rate decisions, and good handling of the limits of real-time interaction.
    {{< /tab >}}
    {{< tab header="Documentation and presentation" >}}
Your submission should make the design easy to understand and review. Clear setup instructions, supporting documentation, screenshots, and a short demo help assessors evaluate the project quickly and fairly.
    {{< /tab >}}
{{< /tabpane-normal >}}


## Prepare your approach

These skills and resources are helpful before you begin:

- Familiarity with a game engine such as Unity, Unreal Engine, or Godot
- Experience integrating machine learning models into real-time applications
- Knowledge of C++, Python, or a game scripting language
- Understanding of on-device ML optimization, such as quantization and mobile deployment

## Resources

- Paper: [The future of interaction with mobile game characters](https://dl.acm.org/doi/10.1145/3641234.3671019)
- Paper: [The future is here: verbal interaction with NPCs on mobile](https://doi.org/10.1145/3664294.3664365)
- Blog: [Google AI for game developers](https://developers.googleblog.com/en/google-ai-for-game-developers/)
- Webinar: [Generative AI in game development](https://meet95924766.adobeconnect.com/pkevz158x6tp/)
- Survey: [A survey on large language model-based game agents](https://arxiv.org/abs/2404.02039)

