# Automated-Research-Paper-Classifier
This project aims to simplify the process of categorizing research papers on submission platforms. By analyzing the title and abstract of papers, our system intelligently predicts the most relevant categories from a set of 57 classes, streamlining the submission workflow and enhancing the user experience.

##Overview
When submitting research papers, authors are often required to manually select categories that best describe their work. Given the vast array of available categories, this task can be daunting and time-consuming. Our solution leverages state-of-the-art NLP models to automate this process, providing category suggestions based on the content of the paper's title and abstract.

##Models Used
We have employed and fine-tuned several advanced models for this task:

RoBERTa: A robustly optimized BERT variant known for its effectiveness in various NLP tasks.
DeBERTa: Enhances BERT and RoBERTa with a disentangled attention mechanism.
DeBERTa-Large: A larger variant of DeBERTa, providing even more powerful contextual embeddings.
An ensemble approach was used to combine the strengths of each model, leading to improved prediction accuracy.

##Performance
The ensemble model achieved an F1 Score of 0.67, indicating a high degree of precision and recall in classifying research papers into the correct categories.

