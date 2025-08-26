# aligninsight-gpt-oss20b

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
aligninsight-llm-redteaming/
├── README.md
├── prompts/
│ └── scenario_prompts.json
├── notebooks/
│ └── aligninsight_pipeline_demo.ipynb


## Getting Started

1. **Clone the repository**
    ```
    git clone https://github.com/yourusername/aligninsight-llm-redteaming.git
    cd aligninsight-llm-redteaming
    ```
2. **Install requirements**  
    _See `requirements.txt` for dependencies (e.g., Python ≥3.8, transformers, etc.)._

3. **Run the demo notebook**  
    Execute `notebooks/aligninsight_pipeline_demo.ipynb` to reproduce the two-tier evaluation workflow on open 7B-class LLMs.

4. **Explore and contribute**  
    - Test your own models with scenario prompts
    - Review or suggest rubric/evaluation improvements
    - Extend scenario libraries or risk categorization

## Citation

If you use or build on AlignInsight, please cite and refer back to this repository and the original competition submission.

## Contact

Questions, feedback, or contributions welcome via [GitHub Issues](https://github.com/yourusername/aligninsight-llm-redteaming/issues) or [amobiandrewonovo@gmail.com](mailto:amobiandrewonovo@gmail.com).

---

**For full details and key findings, see the [Kaggle submission](LINK_TO_KAGGLE_SUBMISSION) and [AlignInsight report](./AlignInsight-Report.docx).**

---

_Author: Dr. Amobi Onovo | 2025_

