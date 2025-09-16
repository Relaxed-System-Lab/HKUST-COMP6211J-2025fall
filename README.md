# COMP6211J 2025 Fall

</div>

<h2 style="text-align: center;"> Advanced Large-Scale Machine Learning for Foundation Models </h2>

**Lecturer**: [Binhang Yuan](https://binhangyuan.github.io/site/). 

## Overview

In recent years, foundation models have fundamentally revolutionized the state-of-the-art of artificial intelligence. Thus, the computation in the training, inference, or RL alignment of the foundation model could be one of the most important workflows running on top of modern computer systems. This course unravels the secrets of the efficient deployment of such workflows from the system perspective. Specifically, we will: i) explain how a modern machine learning system (i.e., PyTorch) works; ii) understand the performance bottleneck of machine learning computation over modern hardware (e.g., Nvidia GPUs); iii) discuss four main parallel strategies in foundation model training (data-, pipeline-, tensor model-, optimizer-, sequence-, MoE- parallelism); iv) real-world deployment of foundation model including various inference time optimization; and v) adpation and systematic evaluations of LLMs.


## Syllabus 

| Date | Topic |
|-----|------|
| W1 - 09/02, 09/04  | - Introduction and Logistics [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP6211J-2025fall/blob/main/slides/Lecture%201%20-%20Introduction%20and%20Logistics.pdf)  <br> - Stochastic Gradient Descent [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP6211J-2025fall/blob/main/slides/Lecture%202%20-%20Stochastic%20Gradient%20Descent.pdf) |
| W2 - 09/09, 09/11  | - Auto-Differentiation [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP6211J-2025fall/blob/main/slides/Lecture%203%20-%20Automatic%20Differentiation.pdf)  <br> -  Nvidia GPU Computation and Communication [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP6211J-2025fall/blob/main/slides/Lecture%204%20-%20Nvidia%20GPU%20Computation%20and%20Communication.pdf) |
| W3 – 09/16, 09/18  | - LLM Pretraining [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP6211J-2025fall/blob/main/slides/Lecture%205%20-%20LLM%20Pretraining.pdf) <br> - Data-, Pipeline-, Optimizer- Parallelism [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP6211J-2025fall/blob/main/slides/Lecture%206%20-%20Data-%20Pipeline-%20Optimizer-%20Parallel%20Training.pdf)|
| W4 - 09/23, 09/25  | - Tensor Model-, Sequence-, MoE- Parallelism <br> - Generative Inference Introduction   |
| W5 - 09/30, 10/02  | - Generative Inference Optimization <br> - Prompt Engineering and Inference Scaling |
| W6 - 10/09         | - RAG and LLM Agent   |
| W7 - 10/14, 10/16  | - PEFT and RL Alignment <br> - LLM Evaluation | 
| W8 - 10/21, 10/23  | - Presentation Session-1 <br> - Presentation Session-2 |
| W9 – 10/28, 10/30  | - Presentation Session-3 <br> - Presentation Session-4 |
| W10 - 11/04, 11/06 | - Presentation Session-5 <br> - Presentation Session-6 |
| W11 - 11/11, 11/13 | - Presentation Session-7 <br> - Presentation Session-8 |
| W12 - 11/18, 11/20 | - Presentation Session-9 <br> - Presentation Session-10 |
| W13 - 11/25, 11/27 | - Presentation Session-11 <br> - Final Review |

## Grading

- In-class Presentation (30%), including one target paper only:
  - Clearly organize the material and present the problem definition, motivation, methodology, and evaluation appropriately. (20%)
  - Can answer the questions from the lecturers and other students appropriately. (5%)
  - Submit short feedback for all the other presentation sessions under the same category. (5%)
  - (Other student feedback determines 70% of the grades for this part.)

- Course Report (70%):
  - Literature review (50%):
    - Cover the relevant techniques exhaustively. (10%) 
    - Understand the relevant techniques correctly. (15%)
    - Organize the techniques using good categorization. (15%) 
    - The report is written in professional academic English. (10%)
    - Page limits: 4 pages in NeurIPS template (excluding reference). 
  - Research plan (20%):
    - The proposed research plan is executable. (10%)
    - The proposed research plan includes novelty and a concrete design. (10%) 
    - Page limits: 4 pages in NeurIPS template (excluding reference).


## Topics for Literature Review:
 - [[Presentation Paper List]](https://github.com/Relaxed-System-Lab/HKUST-COMP6211J-2025fall/blob/main/topics.md)
