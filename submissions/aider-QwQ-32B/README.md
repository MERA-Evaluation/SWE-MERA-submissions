" ## 
Simple Submissions for Aider+QwQ-32B

This repository provides a straightforward setup for evaluating a single LLM model using the Aider agentic framework on 728 issue-solving tasks collected between 2024-09-01 and 2025-06-01.

### Overview

- **Framework:** [Aider](https://github.com/Aider-AI/aider) is used to automate issue resolution with LLMs. It is recognized for its competitive performance compared to other state-of-the-art agentic frameworks when evaluated on the same models.
- **Task Protocol:** For each issue, the model is given up to six independent attempts to generate a fix. Each attempt can include up to four internal reflections (such as linting or testing) to improve the output.
- **Repository Modifications:** Minor changes were made to the [Aider](https://github.com/Aider-AI/aider/tree/4f4b10fd868680e0b87511d4bcf755f198089e8d) and [Aider-SWE-bench](https://github.com/Aider-AI/aider-swe-bench/commit/6e98cd6c3b2cbcba12976d6ae1b07f847480cb74) repositories to address backward compatibility issues.
- **Future Support:** While this setup currently supports only one model, future updates aim to include additional frameworks capable of automated issue resolution.

### Evaluation Metrics

- **pass@1:** Success rate on the first attempt.
- **pass@6:** Success rate across any of the six attempts.

If the model succeeds in an early attempt, it immediately proceeds to the next issue, ensuring efficient evaluation.

*For questions or contributions, please refer to the official [Aider repository](https://github.com/Aider-AI/aider).*

[1] https://github.com/Aider-AI/aider
