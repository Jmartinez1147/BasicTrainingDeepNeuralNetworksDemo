# Basic Training Deep Neural Networks Demo

## Dataset

Iris Dataset

150 flower samples with four measurements:

- sepal_length_cm
- sepal_width_cm
- petal_length_cm
- petal_width_cm

Target:

- species

## Neural Network

Original Model:
- Hidden Layer 1: 32 neurons
- Hidden Layer 2: 16 neurons
- ReLU activations
- Dropout (0.20)
- Weight Decay
- Early Stopping

Controlled Experiment:
- Reduced network size
- Removed dropout

## Results

Validation Accuracy (Dropout Model): 0.8775

Validation Accuracy (No Dropout): 0.9333

## Controlled Experiment

Removing dropout unexpectedly improved validation accuracy.

The smaller model generalized better on this dataset.

## Recommendation

The smaller model without dropout produced the strongest validation performance and would be the preferred prototype.

## Setup

Install requirements:

```bash
pip install -r requirements.txt
```

Run:

```bash
BasicTrainingDeepNeuralNetworksDemo.ipynb
```

## AI Assistance

Microsoft Copilot was used to assist with notebook organization, code review, interpretation of results, and README preparation.