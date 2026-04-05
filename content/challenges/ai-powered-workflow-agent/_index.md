---
title: "Build an AI-powered workflow agent on Arm"
minutes_to_complete: 30240
author:
    - Arm Developer Program
weight: 1
subjects: ML
skilllevels: Advanced
tools_software_languages:
    - Python
    - LLMs
    - MCP
operatingsystems:
    - Linux
    - macOS
    - Windows
challenge_prize: ""
community_attempts:
  - link: "https://github.com/egkoppel/example-papers"
    title: "Mathematics Questions Solver"
    author: "Ronak De et. al"
    summary: "AI Agent to solve mathematics problems from University of Cambridge and create explanatory visualizations in manim"
  - link: "https://github.com/BillLeoutsakosvl346/ElectroNinjaRefined"
    title: "ElectroNinja: A cursor for electrical engineers"
    author: "Bill Leuotsakov et. al"
    summary: "ElectroNinja is an advanced AI-powered application that functions as an electrical engineer. It interprets user requests, generates circuit descriptions, creates LTSpice ASC code, and iteratively refines circuit designs using a combination of GPT-based language models, a vision analysis module, and LTSpice simulation."
challenge: true
multi_challenge: false
multichallenge_part: false
layout: challengeall
---

## Overview

AI agents extend large language models by carrying out user-driven actions, which makes them useful for software development, DevOps, e-commerce workflows, and many other automation tasks. This area is still evolving quickly, and Arm-based systems are well placed to host both local models and the surrounding agent infrastructure.

In this challenge, you build a sandboxed AI workflow agent on Arm hardware. Your solution should use a suitable model and tool stack for cost, reliability, and accessibility while showing how Arm platforms can support secure, practical agentic automation.


## The challenge

Develop an AI-powered agent that automates repetitive or complex workflow tasks in a specific domain, such as software engineering, e-commerce, or DevOps.

Your implementation can use any suitable model and framework. For example, you might combine an API-hosted model with an agent framework such as llama-cpp-agent or an MCP-based toolchain. The key requirement is that the LLM or the agent runtime must execute on an Arm-based system, such as an Arm server, Windows on Arm device, Apple silicon Mac, Raspberry Pi, or Android phone.

## Suggested scope

Your solution should aim to:

- Automate a real workflow rather than only answer chat prompts
- Run in a sandboxed environment with appropriate guardrails
- Select models and tools based on cost, reliability, and accessibility
- Demonstrate a safe and practical Arm-based deployment

## Skills you can practice

This challenge is a good fit if you want to improve in one or more of these areas:

- Agent framework integration
- Tool calling and workflow orchestration
- Secure sandbox design
- LLM deployment on Arm systems

## Assessment criteria

Submissions are assessed using broad criteria that reflect both technical quality and practical usefulness.

{{< tabpane-normal >}}
  {{< tab header="Use of Arm technology" >}}
Your submission should show a clear and meaningful use of Arm-based hardware or software. Strong entries explain why Arm is a good fit for the solution and demonstrate that the agent runtime, model workflow, or supporting tools run effectively on Arm platforms.
  {{< /tab >}}
  {{< tab header="Novelty" >}}
Assessors look for original thinking in the problem you choose, the way you structure the workflow, or the way you combine models and tools. Novelty does not need to mean a completely new idea, but your solution should show a distinctive approach or a thoughtful improvement on existing patterns.
  {{< /tab >}}
  {{< tab header="Code quality and robustness" >}}
Your implementation should be clear, maintainable, and reliable. Strong submissions handle errors well, define sensible boundaries for agent actions, and show evidence that the system can perform the intended workflow consistently.
  {{< /tab >}}
  {{< tab header="Documentation and reproducibility" >}}
Your project should be easy for others to understand, set up, and evaluate. Clear documentation, reproducible steps, and a concise explanation of inputs, outputs, and assumptions help reviewers validate the work efficiently.
  {{< /tab >}}
{{< /tabpane-normal >}}

## Prepare your approach

These skills and resources are helpful before you begin:

- Intermediate experience with an object-oriented language such as Python
- Familiarity with databases such as PostgreSQL, MongoDB, or a vector database
- Access to an LLM through an API or an on-device deployment
- Optional API access to workflow tools such as Jira or Jenkins

## Resources

- Learning Path: [Deploy an MCP server on a Raspberry Pi 5 for AI agent interaction](https://learn.arm.com/learning-paths/cross-platform/mcp-ai-agent/)
- Learning Path: [Deploy an AI agent on Arm with llama.cpp and llama-cpp-agent](https://learn.arm.com/learning-paths/servers-and-cloud-computing/ai-agent-on-cpu/)
