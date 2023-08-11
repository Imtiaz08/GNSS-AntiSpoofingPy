# GNSS-AntiSpoofingPy: Detecting GNSS Spoofing Attacks using Machine Learning

![License](https://img.shields.io/badge/license-MIT-blue.svg)

Welcome to the GNSS-AntiSpoofingPy repository! This project focuses on the development of an innovative anti-spoofing algorithm that harnesses the power of machine learning to detect spoofing attacks in Global Navigation Satellite Systems (GNSS). Our journey involves using a machine learning approach to safeguard the integrity of GNSS signals against malicious spoofing attempts.

## Experiment Overview

Our research journey begins with the utilization of an open-source spoofing signal TEXBAT file. This data serves as our foundation for training and evaluating different machine learning models. The goal is to identify the most effective model that can distinguish between legitimate and spoofed GNSS signals.

## Methodology

### Data Preparation

We preprocess the TEXBAT data and create a comprehensive dataset suitable for machine learning. This dataset includes both clean and spoofed signals, with varying degrees of complexity.

### Model Selection

We explore various machine learning algorithms, including:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Classifier (SVC)
- Decision Tree Classifier

### Training and Evaluation

Each selected model is trained on the prepared dataset and evaluated using various performance metrics. This step helps us understand how well each model can detect spoofing attacks.

### Optimum Model Selection

We compare the performance of the different models and identify the optimum one that demonstrates the highest accuracy, precision, and recall in detecting spoofing signals.

## Experiment Results

After rigorous testing and evaluation, the [Optimum Model] emerged as the most effective solution for our anti-spoofing algorithm. It showcased remarkable accuracy in distinguishing between clean and spoofed signals across diverse scenarios.

## Usage

To explore and use our anti-spoofing algorithm:

1. Clone the GNSS-AntiSpoofingPy repository:
   ```shell
   git clone https://github.com/Imtiaz08/GNSS-AntiSpoofingPy.git
   cd GNSS-AntiSpoofingPy
   ```

2. Install the necessary dependencies:
   ```shell
   pip install -r requirements.txt
   ```

3. Run the experiment:
   ```shell
   python experiment.py
   ```

## Contribution

Contributions to GNSS-AntiSpoofingPy are welcomed! Please refer to our [contribution guidelines](CONTRIBUTING.md) for details on how to participate.

## License

This project is licensed under the MIT License. Check out the [LICENSE](LICENSE) file for more information.

## Contact

For questions or feedback, feel free to raise an issue on our [GitHub repository](https://github.com/Imtiaz08/GNSS-AntiSpoofingPy/issues).

---
*Disclaimer: GNSS-AntiSpoofingPy is a project developed by [Your Name](https://github.com/YourUsername). This project is aimed at enhancing the security of GNSS systems against spoofing attacks and is not affiliated with any official GNSS organization.*
```
