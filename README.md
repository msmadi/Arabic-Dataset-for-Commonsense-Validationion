# Arabic-Dataset-for-Commonsense-Validationion

# Introduction
The task is to directly test whether a system can differentiate natural language statements that make sense from those that do not make sense. The first task is to choose from two natural language statements with similar wordings which one makes sense and which one does not make sense.

Example
Which statement of the two is against common sense?

Statement 1: He put a turkey into the fridge. (correct)
Statement 2: He put an elephant into the fridge.

# Dataset
The Arabic dataset for commonsense validation is based on the  Commonsense Validation and Explanation (ComVE) task https://github.com/wangcunxiang/SemEval2020-Task4-Commonsense-Validation-and-Explanation We translated the original English dataset for commonsense validation. Each example in the provided dataset is composed of 2 sentences: \{s1, s2\} and a label indicating which one is invalid. The pair of sentences are too similar with a slight difference between there words to identify which sentence does not make sense.

To the best of our knowledge, there is no Arabic dataset publicly available for commonsense validation. The provided dataset has 12k rows and consists of three files: train, validation, and test file. Each row consists of two sentences and the label of the non-sensible sentence.

# Evaluation
The task will be evaluated using accuracy. 

# Citation
If you find this project helpful, you can cite:

Is this sentence valid? An Arabic Dataset for Commonsense Validation
https://arxiv.org/abs/2008.10873

@misc{tawalbeh2020sentence,
    title={Is this sentence valid? An Arabic Dataset for Commonsense Validation},
    author={Saja Tawalbeh and Mohammad AL-Smadi},
    year={2020},
    eprint={2008.10873},
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}

# License
The dataset is distributed under the CC BY-SA 4.0 license.
