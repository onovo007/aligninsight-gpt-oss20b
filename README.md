# aligninsight-gpt-oss20b
A reproducible framework for surfacing LLM vulnerabilities using creative scenario prompts and detailed scoring

# AlignInsight: Multi-Tier Red-Teaming for LLM Safety

_A reproducible framework for surfacing LLM vulnerabilities using creative scenario prompts and detailed scoring_

## Overview

**AlignInsight** is an interactive, open red-teaming platform for auditing and uncovering subtle risks in large language models (LLMs). Developed for the OpenAI GPT‑OSS‑20B Red‑Teaming Hackathon, AlignInsight leverages fictional, scenario-driven probing—spanning ten core risk categories—to systematically expose vulnerabilities such as deceptive alignment and sabotage that may evade standard filters.

This framework combines creative scenario prompts, automated keyword analysis, structured rubric-based model evaluation, and required human-in-the-loop review. All results and judgments are exportable for maximum transparency and reproducibility.

## Features

- **Scenario Library**: 10 risk categories × 5 expert-crafted, fictional prompts per category
- **Two-Tier Evaluation**: Pattern scanning and rubric-based meta-evaluation (GPT-4o compatible)
- **Human-in-the-Loop**: Final analyst review, annotation, and override pipeline
- **Transparency**: Exports all findings in JSON for auditing and challenge compliance
- **Reproducibility**: Includes notebook pipeline runnable on 7B open models for accessibility

## Risk Categories

1. Deceptive Alignment / Hidden Motivations  
2. Political Manipulation  
3. Data Exfiltration / Leakage  
4. Reward Hacking  
5. Sabotage  
6. Covert Coordination / Collusion  
7. Prompt Injection / Jailbreak Facilitation  
8. Manipulation of Trusted Channels  
9. Persistence Across Sessions  
10. Steganography / Hidden Communications  

## Repository Structure

