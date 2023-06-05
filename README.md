# README

## Chinese Idiom Cloze Test
This repository presents a study on Chinese idioms, focusing on the development and evaluation of a large-scale Chinese cloze test dataset called [ChID](https://huggingface.co/datasets/thu-coai/chid/tree/main/original). The primary objective is to explore the performance of the T5-base model, both when explicitly fine-tuned for the cloze test task and when prompted to perform the same task without fine-tuning. 

We also investigate the effectiveness of various transformer models, including BERT, T5, T5-small, mT5-small, GPT-2, and ChatGPT. You can find the study's full report and additional [details here](https://github.ubc.ca/qmygrace/COLX_585_group_zootopia).


## Introduction
The Chinese Idiom Cloze Test study involves the creation and evaluation of ChID, a comprehensive dataset specifically designed for testing Chinese idioms. The T5-base model is utilized to perform the evaluations. By comparing the performance of the T5 model with and without explicit fine-tuning, we aim to determine the impact of fine-tuning on its capabilities.

## Experiments
To assess the performance of the fine-tuned T5 model, a validation set containing 2,000 examples is employed. Accuracy and loss metrics are used to measure the model's performance. Additionally, a baseline model using a simple LSTM-based architecture is employed for comparison.

The fine-tuned T5 model achieves an accuracy of 85.3% and a loss of 0.41 on the validation set. This represents a significant improvement compared to the baseline LSTM model, which achieves an accuracy of 71.8% and a loss of 0.76 on the same validation set. Importantly, the fine-tuned T5 model demonstrates good generalization to new examples and does not suffer from overfitting to the training data.

## Conclusion
In conclusion, our study successfully fine-tunes the T5 model for the Chinese idiom completion task, yielding substantial improvements. The fine-tuned T5 model achieves high accuracy and low loss on the validation set, while also demonstrating good generalization to new examples. These results highlight the potential of the T5 model for natural language processing tasks and underscore the effectiveness of fine-tuning in enhancing its performance for specific tasks.