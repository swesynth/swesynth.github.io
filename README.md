# Synthetic Repo-level Bug Dataset for Training Automated Program Repair Models

This contains the replication package of the paper "Synthetic Repo-level Bug Dataset for Training Automated Program Repair Models".

Source code and data are available in the following links:

Source code: [https://anonymous.4open.science/r/SWE-Synth-4401](https://anonymous.4open.science/r/SWE-Synth-4401)

Survey link: [https://survey.swesynth.com](https://survey.swesynth.com)

Data: [https://huggingface.co/swesynth](https://huggingface.co/swesynth)

The detailed instructions to **replicate the experiments** and the descriptions of the **released data** are available in the `README.md` file in the [source code repository](https://anonymous.4open.science/r/SWE-Synth-4401/README.md).

## Abstract

Automated program repair (APR) aims to autonomously fix software bugs, yet its effectiveness is hampered by the lack of diverse, real-world bug datasets essential for model training. Although combining large-scale mining with human effort can yield such datasets, the associated costs limit scalability. To address this, we introduce a novel, scalable synthetic data pipeline that leverages large language models (LLMs) to generate synthetic bugs through targeted LLM-based code rewriting. Our pipeline is also capable of synthesizing valuable intermediate repair steps and enriches the training signal toward correct fixes. Using our method, we create SWE-Synth, a large and contextually rich dataset of bug-fix pairs that are natural, scalable, automated verifiable, and contain intermediate repair steps. Training LLMs on our synthetic dataset yields context-aware repair strategies, that achieve repair accuracy equivalent to those trained on manually curated datasets from GitHub like SWE-Gym while delivering superior scalability with effortless bug synthesis, as demonstrated on popular benchmarks (SWE-Bench and BugsInPy)
