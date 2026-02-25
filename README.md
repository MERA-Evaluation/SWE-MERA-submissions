# SWE-MERA Evaluation Platform

[![arXiv](https://img.shields.io/badge/arXiv-2507.11059-b31b1b.svg)](https://arxiv.org/abs/2507.11059)

The **SWE-MERA evaluation platform** offers a reproducible and transparent environment for benchmarking software engineering agents. This repository provides all the resources and instructions needed to participate in the evaluation, submit your results, and appear on the public leaderboard.

## Demo and Leaderboard

- **Main Demo & Leaderboard:**  
  [https://mera-evaluation.github.io/demo-swe-mera/leaderboard](https://mera-evaluation.github.io/demo-swe-mera/leaderboard)

The web interface features an interactive slider to visualize evaluation metrics across different dates and inspect potential contamination events in the dataset.

## Submission Workflow

To participate and have your agent's results displayed on the leaderboard, follow these steps:

1. **Dataset Acquisition:**  
   Download the SWE-MERA dataset from Hugging Face:  
   [https://huggingface.co/datasets/MERA-evaluation/SWE-MERA](https://huggingface.co/datasets/MERA-evaluation/SWE-MERA)

2. **Agent Execution:**  
   Run your software engineering agent on the provided dataset.

3. **Submission:**  
   Submit your results by creating a pull request to the evaluation repository.

4. **Validation and Leaderboard Update:**  
   Submissions are reviewed, and valid results are integrated into the public leaderboard within two working days.

## Dataset and Evaluation Updates

- The SWE-MERA dataset is updated monthly and made available via Hugging Face.
- Participants are encouraged to include links to their agent's execution trajectories. If not provided, the system will display data from the corresponding GitHub pull request by default.

## Leaderboard and Data Visibility

- The dashboard automatically updates to reflect new submissions.
- If a model does not have sufficient data to compute evaluation metrics for a selected time period, it will not be displayed on the leaderboard for that interval.

## Evaluation Toolkit

- **Evaluation Package (.whl):**  
  [https://pypi.org/project/repotest/](https://pypi.org/project/repotest/)  
  Source: [https://github.com/MERA-Evaluation/repotest](https://github.com/MERA-Evaluation/repotest)

Use this package to evaluate your agent's results before submission.

## Paper

We have presented our paper on EMNLP 2025. Please use this for citation:
```
@inproceedings{adamenko-2025-swe,
    title = "{SWE}-{MERA}: A Dynamic Benchmark for Agenticly Evaluating Large Language Models on Software Engineering Tasks",
    author = "Adamenko, Pavel and
      Ivanov, Mikhail  and
      Valeev, Aidar  and
      Levichev, Rodion  and
      Zadorozhny, Pavel  and
      Lopatin, Ivan  and
      Babaev, Dmitrii  and
      Fenogenova, Alena  and
      Malykh, Valentin",
    editor = {Habernal, Ivan  and
      Schulam, Peter  and
      Tiedemann, J{\"o}rg},
    booktitle = "Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing: System Demonstrations",
    month = nov,
    year = "2025",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.emnlp-demos.30/",
    doi = "10.18653/v1/2025.emnlp-demos.30",
    pages = "440--452",
    ISBN = "979-8-89176-334-0"
}
```

## Contact & Contributions

For questions, issues, or contributions, please refer to the official repositories and demo site linked above. Contributions to the evaluation platform and dataset are welcome.
