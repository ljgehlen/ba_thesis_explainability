# Übersicht Paper

## Explainability

1. [**Interpretable Machine Learning - A Guide for making Black Box Models Explainable**](https://christophm.github.io/interpretable-ml-book/)
- Übersicht von Explainability und einfache Erklärung vieler Saliency Maps Methoden

2. [**Explainable Artificial Intelligence (XAI): Concepts, Taxonomies, Opportunities and Challenges toward Responsible AI**](https://arxiv.org/abs/1910.10045) || [*PDF*](https://arxiv.org/pdf/1910.10045.pdf)
- Zusammenfassung der Begrifflichkeit und Konzepte in XAI

### Feature Attribution / Saliency Methods

1. [**The (Un)reliability of saliency methods**](https://arxiv.org/abs/1711.00867) || [*PDF*](https://arxiv.org/pdf/1711.00867.pdf)

2. [**"Why Should I Trust You?": Explaining the Predictions of Any Classifier**](https://arxiv.org/abs/1602.04938) || [*PDF*](https://arxiv.org/pdf/1602.04938.pdf)
- LIME (Local Interpretable Model-Agnostic Explanations)
- "local surrogate", ersetzt Lokale Umgebung durch simplere Modelle mit zusätzlich generierten Datenpunkten

3. [**A Unified Approach to Interpreting Model Predictions**](https://arxiv.org/abs/1705.07874) || [*PDF*](https://arxiv.org/pdf/1705.07874.pdf)
- SHAP (SHapley Additive exPlanations)
- testet Einfluss jedes Features auf das Ergebnis durch Bewertung aller möglichen Untergruppen

4. [**Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization**](https://arxiv.org/abs/1610.02391) || [*PDF*](https://arxiv.org/pdf/1610.02391.pdf)
- Grad-Cam (Gradient-weighted Class Activation Map)

5. [**Explaining NonLinear Classification Decisions with Deep Taylor Decomposition**](https://arxiv.org/abs/1512.02479) || [*PDF*](https://arxiv.org/pdf/1512.02479.pdf)

#### Saliency Maps

1. [**Visualizing and Understanding Convolutional Networks**](https://arxiv.org/abs/1311.2901) || [*PDF*](https://arxiv.org/pdf/1311.2901.pdf)

2. [**Sanity Checks for Saliency Maps**](https://arxiv.org/abs/1810.03292) || [*PDF*](https://arxiv.org/pdf/1810.03292.pdf)
- Vergleicht Saliency Maps Methoden
- Methode 1: Vergleich der Saliency Maps auf trainierten Neuronalen Netzwerk gegenüber untrainierten Neuronalen Netzwerk der selben Architektur
- Methode 2: Vergleich der Saliency Maps auf normal trainierten Neuronalen Netzwerk und einem trainierten Netzwerk mit zufällig permutierten Labeln

3. [**Sanity Checks for Saliency Metrics**](https://arxiv.org/abs/1912.01451) || [*PDF*](https://arxiv.org/pdf/1912.01451.pdf)

## Pruning

1. [**Rethinking the Value of Network Pruning**](https://arxiv.org/abs/1810.05270) || [*PDF*](https://arxiv.org/pdf/1810.05270.pdf)

### Lottery Ticket Hypothese

1. [**The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks**](https://arxiv.org/abs/1803.03635) || [*PDF*](https://arxiv.org/pdf/1803.03635.pdf)
- Übersicht LTH (Lottery Ticket Hypothesis), winning tickets und IMP (iterative magnitude pruning)

## Mischung

1. [**Less is More: The Influence of Pruning on the Explainability of CNNs**](https://arxiv.org/pdf/2302.08878.pdf)

2. [**Interpretations Steered Network Pruning via Amortized Inferred Saliency Maps**](https://link.springer.com/chapter/10.1007/978-3-031-19803-8_17)

