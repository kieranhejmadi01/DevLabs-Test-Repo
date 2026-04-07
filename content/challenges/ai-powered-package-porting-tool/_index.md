---
title: "Build an AI-powered package porting tool for Arm"
minutes_to_complete: 30240
author:
    - Arm Developer Program
weight: 1
subjects: Migration to Arm
skilllevels: Advanced
tools_software_languages:
    - Python
    - Bash
    - Docker
operatingsystems:
    - Linux
    - macOS
    - Windows
community_attempts:
  - link: "https://github.com/arm/mcp"
    title: "Arm Model Context Protocol (MCP) Server"
    author: "Arm Limited and Contributors"
    summary: "An MCP server providing AI assistants with tools and knowledge for Arm architecture development, migration, and optimization."
#challenge_deadline: "There is a short deadline of tomorrow so you can start and complete the challenge at your convenience."
#challenge_prize: "Standout submissions can be featured on this website as formal recognition from Arm, giving you an achievement you can reference on LinkedIn and on your CV."
challenge: true
multi_challenge: false
multichallenge_part: false
layout: challengeall
---

## 🗺️ Overview

As Arm laptops, desktops, and Windows on Arm devices become more common, more developers need native software support outside Linux. Community ecosystems such as Bioconda and R still contain many packages that fall back to emulated x86 environments or fail to build because of architecture-specific assumptions.

In this challenge, you build an intelligent automation tool that helps port packages to Arm-based platforms. The goal is to reduce repetitive manual effort by combining dependency analysis, build automation, and machine-assisted reasoning.


## 🚀 Mission brief

Create an intelligent automation tool that supports package porting for domains such as bioinformatics pipelines with Nextflow or statistics workflows with R.

The outcome should go beyond simple shell scripting. Your solution should use dependency graph analysis and automation to identify unported packages, recommend or generate fixes, evaluate build results, and help contributors upstream support.

## 🎯 Suggested scope

Aim to support tasks such as:

- Identifying packages that lack native Arm support
- Tracing recursive dependency failures
- Recommending or auto-generating build recipes
- Retrying builds intelligently after failures
- Generating pull requests when the tool is confident in a fix
- Suggesting techniques such as SSE2NEON when packages rely on x86 intrinsics

## 💡 Skills you can practice

- Package ecosystem analysis
- Dependency graph reasoning
- Build automation and CI design
- Porting workflows for Arm systems

## ✅ Assessment criteria

Submissions are assessed using broad criteria that reflect technical depth, practical impact, and value to the Arm software ecosystem.

{{< tabpane-normal >}}
    {{< tab header="Use of Arm technology" >}}
Your submission should show a clear benefit for Arm-based platforms. Strong entries demonstrate how the tool improves package porting, validation, or upstream contribution workflows for Arm systems rather than offering a generic automation script.
    {{< /tab >}}
    {{< tab header="Impact on package porting" >}}
Assessors look for solutions that help solve meaningful bottlenecks in real package ecosystems. Strong submissions identify useful targets, improve developer efficiency, or make it easier to move packages from unsupported to working on Arm.
    {{< /tab >}}
    {{< tab header="Code quality and robustness" >}}
Your implementation should be maintainable, reliable, and well structured. Strong entries handle dependency failures clearly, provide sensible automation boundaries, and produce results that developers can trust.
    {{< /tab >}}
    {{< tab header="Documentation and reproducibility" >}}
Your project should be straightforward to evaluate and reuse. Clear documentation, reproducible workflows, and concise evidence of successful package analysis or porting help reviewers validate the submission efficiently.
    {{< /tab >}}
{{< /tabpane-normal >}}


## 🔧 Prepare your approach

These skills and resources are helpful before you begin:

- Access to an Apple silicon or Windows on Arm machine
- Familiarity with Python, Bash, and Nextflow
- Familiarity with genomics, bioinformatics, or R-based statistics workflows
- Experience with nf-core, Conda, Bioconda, and Docker or Singularity

## 📚 Resources

- External resource: [Example porting scripts and Arm64 nf-core pipeline work](https://github.com/dslarm/bioconda-contrib-notes/tree/main)
- External resource: [Arm64 nf-core pipelines](https://github.com/ewels/nf-core-arm-discovery/tree/main)
- Documentation: [nf-core documentation](https://nf-co.re/docs/)
- Documentation: [Bioconductor build reports](https://bioconductor.org/checkResults/)
- Documentation: [CRAN and Bioconductor Windows on Arm package results](https://www.r-project.org/nosvn/winutf8/ucrt3/CRAN_aarch64/install_out/)
- Dataset: [NCBI datasets](https://www.ncbi.nlm.nih.gov/datasets/)

