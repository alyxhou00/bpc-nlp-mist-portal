# Multilingual Instruction Shared Task: Subtasks based on WMT25

Portal linking each sub-repos for the MIST/WMT25 in Bachelor's Practical Course: Projects in Natural Language Processing offered in TUM SS2026.
Click on corresponding links to view the source code.

### 1. [Subtask Linguistic Reasoning](https://github.com/alyxhou00/BPC-NLP-MIST-public)
In this subtask, we benchmark the linguistic reasoning performance of LLMs, following the methods used in the original paper. More specifically, We extend [Linguini](https://github.com/facebookresearch/linguini) to include multilingual instructions in English, German, French, Simplified Chinese, and Taiwanese Hokkien, while retaining reasoning tasks across 80 low-resource languages. 
Given linguistic problems as prompts, both closed-weight and open-weight models provide answers and compare the correctness using exact-match accuracy and chrF scores.

### 2. A Closer Look at a Low-Resource Language: Na'vi
Using data from 300 grammatically correct sentences & translations from the "An Annotated Na'vi Dictionary", we give Qwen and Llama 100 sentences to learn from. The instruction languages are tested in English, German, and French.

### 3. [Subtask LLM-as-a-Judge for Multilingual Cross-Document Summarization](https://github.com/xsboy-12345/MIST_xsml)
We train local open-source LLMs as multilingual summary judges. Given reviews, a generated summary, and one evaluation dimension, the model predicts a human-like quality score from 1 to 7.

