# Uninterrupted-Federated-Learning
Using on-device Continual Learning and Federated Learning for uninterrupted and privacy-compliant AI-powered IoT operation

This project was done as part of my final year at the University of Exeter.

## Continual Learning and Federated Learning

  - **Federated Learning**: Decentralised neural network training. Instead of each device sending its private data to a localised data centre to train a model, each device trains a version of the model locally and sends the locally trained model back to a centralised server. All the individual models can then be aggregated. This technique allows for privacy-compliant AI-powered IoT since the private data is never collected on a central server.

  - **Continual Learning**: Allows a neural network to be incrementally updated on a continuous stream of data. This is inspired by how Humans learn in real time while interacting with their surroundings.

## Summary of Research paper
The goal of this research was to tackle one of Federated Learning's biggest problems: training rounds. In order to do on-device training on IoT devices, which are usually low-power devices, they generally need to stop their primary task in order to allocate power for the training of the model. This is a problem for IoT installations that need to run 24/7 (e.g. surveillance systems, monitoring systems...).

By combining Continual Learning and Federated Learning we eliminated the need for computationally heavy training rounds since the models are trained continually on incoming data. Therefore, with this technique, we could allow the use of Federated Learning for surveillance systems or other IoT operation that need to run uninterrupted.

## Research Paper as PDF

[Final Research Paper mark: **73%**](Federated_Learning-report_Final.pdf)

[Some title here](FILE_NAME.pdf)
