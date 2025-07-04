# SWE-MERA Evaluation Platform

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

- **Paper:** Coming soon

## Contact & Contributions

For questions, issues, or contributions, please refer to the official repositories and demo site linked above. Contributions to the evaluation platform and dataset are welcome.
