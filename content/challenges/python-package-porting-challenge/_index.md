---
title: "Port Python packages to Windows on Arm"
minutes_to_complete: 30240
author:
    - Arm Developer Program
weight: 1
subjects: Libraries
skilllevels: Advanced
tools_software_languages:
    - Python
    - CI
    - C++
operatingsystems:
    - Windows
community_attempts:
  - link: "https://github.com/arm/mcp"
    title: "Arm Model Context Protocol (MCP) Server"
    author: "Arm Limited and Contributors"
    summary: "An MCP server providing AI assistants with tools and knowledge for Arm architecture development, migration, and optimization."
challenge: true
multi_challenge: false
multichallenge_part: false
layout: challengeall
---

## Overview

Windows on Arm brings Arm performance and efficiency to more desktop systems, but developers still hit package ecosystem gaps. Many widely used Python packages do not ship `win_arm64` wheels, which forces users to rebuild from source and often exposes architecture-specific issues.

In this challenge, you help improve the Windows on Arm Python package ecosystem by validating packages, fixing compatibility issues, and upstreaming support for Arm-native binaries.


## The challenge

Advance the Windows on Arm Python ecosystem by validating and optimizing third-party packages so they build and run successfully on `win_arm64`.

## Suggested scope

Aim to complete work such as:

- Turn at least five amber projects green on [Windows Arm64 Wheels](https://tonybaloney.github.io/windows-arm64-wheels/)
- Identify packages without `win_arm64` wheels
- Diagnose porting bugs such as x86-specific intrinsics or unsupported toolchain assumptions
- Create patches that allow packages to build and run correctly
- Collaborate with maintainers to upstream your fixes

## Skills you can practice

- Python packaging
- Continuous integration testing
- Porting native extensions to Arm
- Collaboration with upstream open source maintainers

## Assessment criteria

Submissions are assessed using broad criteria that reflect ecosystem impact, technical quality, and effectiveness on Windows on Arm.

{{< tabpane-normal >}}
    {{< tab header="Use of Arm technology" >}}
Your submission should make a clear contribution to the Windows on Arm Python ecosystem. Strong entries demonstrate that packages build, install, or run correctly on `win_arm64`, with fixes that are directly relevant to Arm users and maintainers.
    {{< /tab >}}
    {{< tab header="Ecosystem impact" >}}
Assessors look for work that improves real packages and benefits the broader community. Strong submissions unblock multiple packages, turn visible ecosystem gaps into working solutions, or help move fixes upstream.
    {{< /tab >}}
    {{< tab header="Code quality and maintainability" >}}
Your changes should be clear, reliable, and appropriate for long-term use. Strong entries include well-scoped fixes, sensible CI or packaging updates, and good evidence that the package behaves correctly after the changes.
    {{< /tab >}}
    {{< tab header="Documentation and reproducibility" >}}
Your project should make the porting work easy to review and repeat. Clear notes on the issue, the fix, the validation steps, and any upstream coordination help reviewers understand both the problem and the outcome.
    {{< /tab >}}
{{< /tabpane-normal >}}


## Prepare your approach

These skills and resources are helpful before you begin:

- Intermediate to advanced Python experience
- Experience creating Python packages and CI workflows
- Familiarity with Rust, Java, or C++ if you choose non-pure-Python packages

## Resources

- Documentation: [Windows on Arm environments](https://linaro.atlassian.net/wiki/spaces/WOAR/pages/29005479987/Windows+on+Arm+Environments)
- Documentation: [Python packages without Windows on Arm wheels](https://tonybaloney.github.io/windows-arm64-wheels/)
- Documentation: [Additional Windows on Arm wheels resource](http://www.winarm64wheels.com/)
- Learning Path: [Sampling CPython with WindowsPerf](https://learn.arm.com/learning-paths/laptops-and-desktops/windowsperf_sampling_cpython/)
- Community post: [Python on Windows Arm64](https://discuss.python.org/t/python-on-windows-arm64/104524)
- GitHub repository: [cibuildwheel](https://github.com/pypa/cibuildwheel)

