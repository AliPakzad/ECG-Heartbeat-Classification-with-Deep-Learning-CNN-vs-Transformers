Electrocardiogram (ECG) signals carry crucial information about the electrical activity of the heart, and automatic beat classification has become an important task in modern healthcare and real-time monitoring systems. In this notebook, we explore the ECG heartbeat classification dataset and build two powerful deep-learning models to understand and categorize different heartbeat types.

We begin by loading and visualizing the dataset to gain insight into the structure of ECG beats and the distribution of classes. After understanding the data, we design two separate models:

A Convolutional Neural Network (CNN), well-suited for capturing local patterns in ECG waveforms.
A Transformer-based model, capable of modeling long-range dependencies within the signal.
Since training deep-learning models on imbalanced biomedical data can be challenging, we also apply data augmentation techniques to enrich the dataset and help the models generalize better.

Finally, we train both models and evaluate them using accuracy, precision, and recall, providing a clear comparison between CNN and Transformer architectures on this real-world ECG classification task.

This notebook walks you through the entire pipeline—from dataset exploration to model development and performance analysis—to give you a complete and practical deep-learning workflow for ECG signal classification.
