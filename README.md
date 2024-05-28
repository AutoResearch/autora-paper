# AutoRA: Automated Research Assistant for Closed-Loop Empirical Research

This repository hosts the joint JOSS submission of the [AutoRA](https://github.com/AutoResearch/autora) framework.

The AutoRA framework consists of the following core packages with minimal dependencies:
- [autora](https://github.com/AutoResearch/autora): Main repository that serves to integrate all subpackages and documentation of AutoRA.
- [autora-core](https://github.com/AutoResearch/autora): AutoRA workflow mechanics.
- [autora-synthetic](https://github.com/AutoResearch/autora): Synthetic models for benchmarking in AutoRA.

In addition, the AutoRA framework provides vetted optional dependencies for workflow components, including theorists (for automated model discovery), experimentalists (for automated expeirmental design), and experiment runners (for automated data collection).

Theorist Components:
- [autora[theorist-darts]](https://github.com/AutoResearch/autora-theorist-darts): Automated model discovery with Differentiable Architecture Search. 
- [autora[theorist-bms]](https://github.com/AutoResearch/autora-theorist-bms): Automated model discovery with Bayesian Machine Scientist.
- [autora[theorist-bsr]](https://github.com/AutoResearch/autora-theorist-sr): Automated model discovery with Bayesian Symbolic Regression.

Experimentalist Components:
- [autora[experimentalist-falsification]](https://github.com/AutoResearch/autora-experimentalist-uncertainty): Automated experimental design based on predicted model falsification.
- [autora[experimentalist-inequality]](https://github.com/AutoResearch/autora-experimentalist-inequality): Automated experimental design based on a pairwise distance metric.
- [autora[experimentalist-leverage]](https://github.com/AutoResearch/autora-experimentalist-uncertainty): Automated experimental design based on the leverage of data points on model predictions.
- [autora[experimentalist-mixture]](https://github.com/AutoResearch/autora-experimentalist-uncertainty): Automated experimental design based on mixture of  experimentalists.
- [autora[experimentalist-nearest-value]](https://github.com/AutoResearch/autora-experimentalist-nearest-value): Automated experimental design based on distance to existing pool of experiment conditions.
- [autora[experimentalist-novelty]](https://github.com/AutoResearch/autora-experimentalist-novelty): Automated experimental design based on experiment novelty.
- [autora[experimentalist-model-disagreement]](https://github.com/AutoResearch/autora-experimentalist-model-disagreement): Automated experimental design based on model disagreement.
- [autora[experimentalist-uncertainty]](https://github.com/AutoResearch/autora-experimentalist-uncertainty): Automated experimental design based on model uncertainty.

Experiment Runner Components:


