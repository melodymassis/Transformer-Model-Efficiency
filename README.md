# Fine-Tuning Transformers for Toxicity Detection: A Sentiment-Informed Approach

Detecting toxic comments in online forums is crucial for fostering healthy discussions, especially in domains like personal health, where users may share sensitive information. This research explores the progression from traditional machine learning approaches, such as logistic regression, to advanced transformer-based models like DistilBERT and RoBERTa. To address the challenges of class imbalance and the nuanced nature of toxicity, it incorporates sentiment analysis as an additional feature and leverages a knowledge distillation framework to train a sentiment-enhanced student model.

The sentiment-aware student model outperformed its teacher (toxicity-only DistilBERT) in precision, recall, and F1-score, particularly for the minority toxic class. This demonstrates the potential of sentiment weighting to improve performance in imbalanced datasets. Visual analyses, including confusion matrices and error breakdowns, illustrate the significant reduction in false negatives and false positives achieved by the student model. Furthermore, this study highlights the importance of efficient memory usage and optimization for deploying transformer models in resource-constrained environments.

This work underscores the value of sentiment-informed training in improving toxicity detection while offering a scalable approach for real-world applications. Future efforts will focus on further refining the model and expanding its application to other domains with nuanced and imbalanced data.