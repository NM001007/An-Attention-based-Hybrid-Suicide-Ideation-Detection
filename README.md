# An-Attention-based-Hybrid-Suicide/Depression-Ideation-Detection
This is an implementation of the attention-based hybrid architecture (Ghosh et al, 2023) applied on suicide social media notes detection.

## About the Paper
### Abstract
Mental health has become a major concern in recent years. Social media have been increasingly used as platforms to gain insight into a person’s mental health condition by analysing the posts and comments, which are textual in nature. By analysing these texts, depressive posts can be detected. To facilitate this process, this work presents an attention-based bidirectional Long Short-Term Memory (LSTM)- Convolutional Neural Network (CNN) based model to detect depressive Bangla social media texts, which is lighter and more robust than the conventional models and provides better performance. A dataset containing such Bangla texts was also developed in this work to mitigate the scarcity. Different preprocessing stages were followed, and three embeddings were used in this task. Thanks to the attention mechanism, the proposed model achieved an accuracy of 94.3% with 92.63% of sensitivity and 95.12% of specificity. When tested on other languages, such as English, the proposed model performed remarkably. The robustness and explainability of the proposed model were also discussed in this paper. Additionally, when compared with classical machine learning models, ensemble approaches, transformers, other similar models, and existing architectures, the proposed model outperformed them.

-- However the paper is initially focused on the depressive posts on social media, this repository has applied it onto suicidal posts and suicide ideation detection. The results show the effectiveness of this model on both tasks.

## Reference

@article{GHOSH2023119007,
title = {An attention-based hybrid architecture with explainability for depressive social media text detection in Bangla},
journal = {Expert Systems with Applications},
volume = {213},
pages = {119007},
year = {2023},
issn = {0957-4174},
doi = {https://doi.org/10.1016/j.eswa.2022.119007},
url = {https://www.sciencedirect.com/science/article/pii/S0957417422020255},
author = {Tapotosh Ghosh and Md. Hasan Al Banna and Md. Jaber Al Nahian and Mohammed Nasir Uddin and M. Shamim Kaiser and Mufti Mahmud},
keywords = {Depression, Social media, Attention, Mental health, Suicide},
}
