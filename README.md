# Traffic Sign Recognition

## Overview
This project implements an efficient federated learning framework for traffic sign recognition. Federated learning is a decentralized approach to machine learning where multiple clients collaboratively train a model while keeping their data localized. This project aims to enhance the efficiency and accuracy of traffic sign recognition models by leveraging federated learning techniques.

## Features
- **Federated Learning Framework:** A decentralized training approach to improve privacy and data security.
- **Traffic Sign Recognition:** Models trained specifically for recognizing and classifying traffic signs.
- **Efficient Communication:** Optimized algorithms to reduce communication overhead between clients and servers.
- **Scalability:** Capable of handling multiple clients with large datasets.
- **Preprocessing:** Converts images to grayscale and resizes them to a consistent size.

## Datasets
This project uses the [German Traffic Sign Recognition Benchmark (GTSRB) dataset](https://benchmark.ini.rub.de/gtsrb_dataset.html).

## Training
The training process involves multiple clients sending their local model updates to the server, and aggregating these updates to improve the global model.

